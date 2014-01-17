
[tutorial]: http://static.rust-lang.org/doc/tutorial.html
[rust]: http://www.rust-lang.org/ 
[Github repository]: https://github.com/olemaire/rust-osx
[Build repository]: https://www.dropbox.com/sh/rkfg8z980z14q6m/gYDSRd33LB
[Xcode]: https://developer.apple.com/xcode/
[packagemaker]: https://discussions.apple.com/thread/4083583?tstart=199

# RUST Installer for OSX

OSX install packages to install and use [rust] without having to compile it from source.


## Just use precompiled install packages
Download and install a `RUST-x.y.pkg` from the DropBox [Build repository], selecting your OSX release (10.x). 

Example: I'm running a Maverick Mac Book Air, so I need to download and install `/10.9/RUST-0.9.pkg` to install RUST 0.9 on my OSX 10.9.1 station.

Once installed, you will have:

* rust compilator and utils (rustc, rustpkg and rustdoc) in `/usr/local/bin/` 
* rust libraries in `/usr/local/lib/`
* rust documentation (man pages) in `/usr/local/share/man/man1/`

Start use [rust] as indicated in rust [tutorial]: 

    me@home:~/ $ rustc helloworld.rs

## Build you own rust package
Don't trust me - build your own rust install package using Apple [packagemaker]:

* install [XCode], its command line tools, and [packagemaker]
* git clone the present [Github repository]
* open your desired `packagemaker/rust-x.y-installpackage.pmdoc` with [packagemaker]
* enjoy (and contribute if willing to)

The present work is released under BSD revised license - so use feel free to {re,ab}use.


## Contribution welcome
You're feedback is warmly welcome: use the issue tracker or drop me a mail.

Modify and distribute: join this [Github repository].

## Credits
Many Thank's to 

* Alexander Stavonin who did a [RustInstaller] package using [Iceberg] for [rust] 0.6.
* The [rust] development team, and folks from #rust (irc.mozilla.org)

[IceBerg]: http://s.sudre.free.fr/Software.html
[RustInstaller]: https://github.com/astavonin/RustInstaller
