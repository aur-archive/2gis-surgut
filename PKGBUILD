pkgname=2gis-surgut
pkgver=28
pkgrel=1
pkgdesc="Map of Surgut for 2GIS, June 2013"
arch=('i686' 'x86_64')
url="http://surgut.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.5.1')
source=("http://download.2gis.ru/arhives/2GISData_Surgut-28.orig.zip")
md5sums=('07b7558116b0caa2c4d95143c350c29a')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Surgut.dgdat" "${pkgdir}/opt/2gis/surgut.dgdat" || return 1
  install -D -m 644 "${srcdir}/2gis/3.0/Plugins/DGisLan/Surgut.dglf" "${pkgdir}/opt/2gis/Plugins/DGisLan/surgut.dglf" || return 1
}
