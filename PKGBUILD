# Maintainer: Moritz Lipp <mlq@pwmt.org>

_pkgname=Flask-CouchDBKit
pkgname=python2-flask-couchdbkit
pkgver=0.3.5
pkgrel=1
pkgdesc="Adds CouchDBKit support to Flask"
arch=(any)
url="http://packages.python.org/Flask-CouchDBKit/"
license=('BSD')
depends=('python2' 'python2-flask' 'couchdb')
makedepends=('python2-distribute')
source=("http://pypi.python.org/packages/source/${_pkgname:0:1}/$_pkgname/$_pkgname-$pkgver.tar.gz")
md5sums=('6f93cf99b59e66731b8a0f964780d6ac')

package() {
  cd "$srcdir/$_pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir/" --prefix=/usr --optimize=1
}

# vim:set ts=2 sw=2 et:
