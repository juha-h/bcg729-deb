Directory 'debian' for building Debian package of https://github.com/BelledonneCommunications/bcg729:
```
$ git clone https://github.com/BelledonneCommunications/bcg729.git -b release/1.1.1
$ cd bcg729
$ git clone https://github.com/juha-h/bcg729-deb.git debian
$ dpkg-buildpackage -rfakeroot -b -us -uc
```
