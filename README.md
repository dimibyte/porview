**Porview**
---
![Select a set to analyze](https://raw.githubusercontent.com/dimibyte/porview/master/screenshots/1.png)
![Overview installed atoms](https://raw.githubusercontent.com/dimibyte/porview/master/screenshots/2.png)

---
#### Dependencies:
- sys-devel/autoconf
- sys-devel/automake
- x11-libs/fltk
- dev-libs/boost
- app-portage/gentoolkit
---
#### Compile and install

`fltk -c porview.fl`
`autoreconf --install`
`mkdir build`
`cd build`
`../configure`
`make`
`sudo make install`