# mpv DUMMY

[mpv](https://mpv.io) is a cross-platform media player. Its primary interface is the command-line. It can be built as an app on macOS—which is convenient for file type associations—but [app builds](https://mpv.io/installation/) are unofficial and may lag behind the command-line version.

[Homebrew](https://brew.sh) is a package manager for macOS. It can install and keep mpv up to date, but it does not build the app bundle.

mpv DUMMY is a macOS app generated with [Automator](https://en.wikipedia.org/wiki/Automator_(macOS)) and edited by hand. All it does is take your files and pass them along to the Homebrew-installed mpv command-line, providing the best of both worlds.

So it works as a (mostly) drop-in replacement, mpv DUMMY uses the same app name and icon as mpv. The bundle identifier is different so it can coexist with another installation of mpv on your system. mpv DUMMY is signed and notarised.

[⤓ Download mpv DUMMY](https://github.com/vitorgalvao/mpv-dummy/releases/latest/download/mpv.DUMMY.zip)
