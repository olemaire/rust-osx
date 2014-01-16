
[tutorial]: http://static.rust-lang.org/doc/tutorial.html
[rust]: http://www.rust-lang.org/ 
[repo]: https://github.com/olemaire/rust-osx
[packagemaker]: https://discussions.apple.com/thread/4083583?tstart=199

# RUST Installer for OSX

RUST install package for OSX: install and use [rust] without having to compile it from source.

## Install rust package
Download and install a `RUST-x.y.pkg` from builds/`your osx master release`/ 

I'm running OSX 10.9.1, so I need to download and install `builds/10.9/RUST-0.9.pkg` to install RUST 0.9 on my OSX station.

Once installed, you will have:

* rust compilator and utils (rustc, rustpkg and rustdoc) in `/usr/local/bin/` 
* rust libraries in `/usr/local/lib/`
* rust documentation (man pages) in `/usr/local/share/man/man1`

Start use [rust] as indicated in rust [tutorial]: 

    me@home:~/ $ rustc helloworld.rs

## Build you own rust package
Don't trust me - build your own rust install package using Apple [packagemaker]:

* install XCode, its command line tools, and [packagemaker]
* git clone the present Git [repo]
* open your desired `rust-x.y-installpackage.pmdoc` with [packagemaker]
* enjoy (and contribute if willing to)

## Contribution welcone
You're feedback is warmly welcome: use the issue tracker or drop me (<olivier.lemaire@me.com>) a mail.

Modify and distribute: join this Github repository.

## Credits
Many Thank's to FIXME
