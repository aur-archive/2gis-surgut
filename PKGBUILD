# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-surgut
pkgver=24
pkgrel=1
pkgdesc="Map of Surgut for 2GIS, February 2013"
arch=('i686' 'x86_64')
url="http://surgut.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Surgut-24.orig.zip")
md5sums=('2abcfa79ce5613398ced97e50694868b')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Surgut.dgdat "${startdir}/pkg/opt/2gis/surgut.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Surgut.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Surgut.dglf" || return 1
     
}

