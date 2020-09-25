# Maintainer: 0xpanic <kwswesey at gmail dot com>

pkgname=fortune-mod-dril
pkgver=20200708
pkgrel=1
pkgdesc="Fortune quotes from @dril"
url="https://cooltweets.herokuapp.com/dril/old"
arch=('any')
license=('custom:none')
depends=('fortune-mod')
source=('dril')
groups=('fortune-mods')


build()
{
	strfile $(srcdir)/dril
}

package()
{
    install -D -m644  dril $pkgdir/usr/share/fortune/dril
    install -D -m644  dril.dat $pkgdir/usr/share/fortune/dril.dat

}

