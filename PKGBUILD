pkgname=git-cinnabar
pkgrel=1
pkgver=0.5.8
arch=(x86_64)
source=(https://github.com/glandium/git-cinnabar/releases/download/0.5.8/git-cinnabar.windows.x86_64.zip)
sha256sums=('1744f52c644872e72d1982cb852ad945679ef0fa8e5758e88a2a015e8bc24850')
prepare(){
    cd "$srcdir/$pkgname"
}
build(){
    cd "$pkgname"
    
}
package(){
    cd "$srcdir/$pkgname"
    mkdir -p "$pkgdir/usr/bin/"
    cp -rf cinnabar "$pkgdir/usr/bin/"
    cp -rf helper "$pkgdir/usr/bin/"
    cp -rf git-cinnabar "$pkgdir/usr/bin/"
    cp -rf git-remote-hg "$pkgdir/usr/bin/"
}