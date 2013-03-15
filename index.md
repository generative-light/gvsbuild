---
layout: default
title: main page
---

## About

This page is intended to guide you through the process of building the whole GTK+ stack (and some additional libraries required by HexChat) on Windows using Visual C++ a.k.a. MSVC, version 10 that comes with Visual Studio 2010. It is largely based on Chun-wei Fan's [Compiling the GTK+ stack using Visual C++](https://live.gnome.org/GTK%2B/Win32/MSVCCompilationOfGTKStack). Thanks!

You can also skip the building process and right off just **download** and use the Visual C++ builds of GTK+ so that you don't have to <del>waste</del>spend weeks (months?) on getting it to work like I had. So without further ado:

## GTK+ Visual C++ Builds:

This is the redistributable and a bundle of all the GTK+ stuff. **This is most likely what you need**.

<table>

<tr>
<td>Microsoft Visual C++ Redistributable Package</td>
<td>2010 SP1</td>
<td><a href="http://www.microsoft.com/en-us/download/details.aspx?id=8328">32 bit</a></td>
<td><a href="http://www.microsoft.com/en-us/download/details.aspx?id=13523">64 bit</a></td>
</tr>

<tr class="even">
<td>GTK+ bundle</td>
<td>2.24.15</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/gtk-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/gtk-x64.7z">64 bit</a></td>
</tr>

</table>

These are the separate packages for advanced users. These also require the redistributable to be installed.

<table>

<tr>
<td>zlib</td>
<td class="current">1.2.7</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/zlib-1.2.7-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/zlib-1.2.7-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>win-iconv</td>
<td class="current">0.0.6</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/win-iconv-0.0.6-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/win-iconv-0.0.6-x64.7z">64 bit</a></td>
</tr>

<tr>
<td>FreeType</td>
<td class="current">2.4.11</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/freetype-2.4.11-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/freetype-2.4.11-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>libffi</td>
<td class="current">3.0.12</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/libffi-3.0.12-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/libffi-3.0.12-x64.7z">64 bit</a></td>
</tr>

<tr>
<td>libxml2</td>
<td class="current">2.9.0</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/libxml2-2.9.0-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/libxml2-2.9.0-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>gettext-runtime</td>
<td class="current">0.18</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/gettext-runtime-0.18-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/gettext-runtime-0.18-x64.7z">64 bit</a></td>
</tr>

<tr>
<td>OpenSSL</td>
<td class="current">1.0.1e</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/openssl-1.0.1e-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/openssl-1.0.1e-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>libpng</td>
<td class="current">1.5.14</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/libpng-1.5.14-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/libpng-1.5.14-x64.7z">64 bit</a></td>
</tr>

<tr>
<td>Fontconfig</td>
<td class="outdated">2.8.0</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/fontconfig-2.8.0-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/fontconfig-2.8.0-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>Pixman</td>
<td class="outdated">0.26.2</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/pixman-0.26.2-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/pixman-0.26.2-x64.7z">64 bit</a></td>
</tr>

<tr>
<td>GLib</td>
<td class="current">2.34.3</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/glib-2.34.3-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/glib-2.34.3-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>HarfBuzz</td>
<td class="current">0.9.13</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/harfbuzz-0.9.13-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/harfbuzz-0.9.13-x64.7z">64 bit</a></td>
</tr>

<tr>
<td>Enchant</td>
<td class="current">1.6.0</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/enchant-1.6.0-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/enchant-1.6.0-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>ATK</td>
<td class="current">2.7.5</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/atk-2.7.5-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/atk-2.7.5-x64.7z">64 bit</a></td>
</tr>

<tr>
<td>GDK-PixBuf</td>
<td class="current">2.26.5</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/gdk-pixbuf-2.26.5-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/gdk-pixbuf-2.26.5-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>cairo</td>
<td class="outdated">1.12.8</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/cairo-1.12.8-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/cairo-1.12.8-x64.7z">64 bit</a></td>
</tr>

<tr>
<td>Pango</td>
<td class="outdated">1.32.5</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/pango-1.32.5-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/pango-1.32.5-x64.7z">64 bit</a></td>
</tr>

<tr class="even">
<td>GTK+</td>
<td class="current">2.24.15</td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x86/gtk-2.24.15-x86.7z">32 bit</a></td>
<td><a href="http://dl.hexchat.org/gtk-win32/vc10/x64/gtk-2.24.15-x64.7z">64 bit</a></td>
</tr>

</table>

## Building from Source

If you feel brave enough to build these on your own, bear in mind, GTK+ on Windows is **pain in the ass**. You're warned.

<img src="images/dependency-graph.png" alt="gtk dependency graph" />

If this graph wasn't enough to frighten you off and you still think you want to do this, you'll need to install:

 * [Visual Studio 2010 Professional Trial](http://www.microsoft.com/en-us/download/details.aspx?id=16057)
 * [CMake 2.8](http://www.cmake.org/cmake/resources/software.html)
 * [MozillaBuild](http://ftp.mozilla.org/pub/mozilla.org/mozilla/libraries/win32/)
 * Perl 5.16 [x86](http://dl.hexchat.org/misc/perl/perl-5.16.3-x86.7z) or [x64](http://dl.hexchat.org/misc/perl/perl-5.16.3-x64.7z) (extract to _C:\mozilla-build\perl-5.16\Win32_ or _C:\mozilla-build\perl-5.16\x64_)
 * [NASM](http://www.nasm.us/pub/nasm/releasebuilds/?C=M;O=D) (extract to _C:\mozilla-build\nasm_)
 * [msgfmt](http://dl.hexchat.org/gtk-win32/msgfmt-0.18.1.7z) (extract to _c:\mozilla-build_)
 * [Ragel](http://dl.hexchat.org/gtk-win32/ragel-6.8.7z) (extract to _c:\mozilla-build_)

As you can see, these libraries have a quite complex dependency order, so it's really recommended to build them in the order they're explained here, otherwise you'll probably encounter quite a few problems (you'll most likely encounter too many problems already, at least initially). After you built something, always extract the resulting package to _C:\mozilla-build\hexchat\build\Win32_ or _C:\mozilla-build\hexchat\build\x64_. When in Visual Studio, always select the _Release_ configurations, others most likely won't work.

### zlib
 * download [zlib 1.2.7](http://dl.hexchat.org/gtk-win32/src/zlib-1.2.7.7z)
 * extract as _C:\mozilla-build\hexchat\zlib-1.2.7_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/zlib) to this folder
 * open VS x86 or x64 command prompt
 * run _build-x86.bat_ or _build-x64.bat_

### win-iconv
 * download [win-iconv 0.0.6](http://dl.hexchat.org/gtk-win32/src/win-iconv-0.0.6.7z)
 * extract as _C:\mozilla-build\hexchat\win-iconv-0.0.6_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/win-iconv) to this folder
 * open VS x86 or x64 command prompt
 * run _build-x86.bat_ or _build-x64.bat_

### FreeType
 * download [FreeType 2.4.11](http://dl.hexchat.org/gtk-win32/src/freetype-2.4.11.7z)
 * extract as _C:\mozilla-build\hexchat\freetype-2.4.11_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/freetype) to this folder
 * open _builds\win32\vc11\freetype.sln_ and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### libffi
 * download [libffi 3.0.12](http://dl.hexchat.org/gtk-win32/src/libffi-3.0.12.7z)
 * extract as _C:\mozilla-build\hexchat\libffi-3.0.12_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/libffi) to this folder
 * start a shell with _start-msvc10.bat_ or _start-msvc10-x64.bat_ from MozillaBuild
 * in this shell, run _build-x86.bat_ or _build-x64.bat_
 * in a regular command prompt, run _release-x86.bat_ or _release-x64.bat_

### libxml2
 * download [libxml2 2.9.0](http://dl.hexchat.org/gtk-win32/src/libxml2-2.9.0.7z)
 * extract as _C:\mozilla-build\hexchat\libxml2-2.9.0_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/libxml2) to this folder
 * open _win32\vc11\libxml2.sln_ and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### gettext-runtime
 * download [gettext-runtime 0.18](http://dl.hexchat.org/gtk-win32/src/gettext-runtime-0.18.7z)
 * extract as _C:\mozilla-build\hexchat\gettext-runtime-0.18_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/gettext-runtime) to this folder
 * convert _gettext-runtime\intl\intl.def_ to Unix EOL
 * open VS x86 or x64 command prompt
 * apply the patch with `patch -p1 -i gettext-runtime.patch`
 * run _build-x86.bat_ or _build-x64.bat_

### OpenSSL
 * download [OpenSSL 1.0.1e](http://dl.hexchat.org/gtk-win32/src/openssl-1.0.1e.7z)
 * extract as _C:\mozilla-build\hexchat\openssl-1.0.1e_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/openssl) to this folder
 * open VS x86 or x64 command prompt
 * run _build-x86.bat_ or _build-x64.bat_

### libpng
 * download [libpng 1.5.14](http://dl.hexchat.org/gtk-win32/src/libpng-1.5.14.7z)
 * extract as _C:\mozilla-build\hexchat\libpng-1.5.14_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/libpng) to this folder
 * open _projects\vstudio\vstudio.sln_ and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### Fontconfig
 * download [Fontconfig 2.8.0](http://dl.hexchat.org/gtk-win32/src/fontconfig-2.8.0.7z)
 * extract as _C:\mozilla-build\hexchat\fontconfig-2.8.0_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/fontconfig) to this folder
 * apply the patch with `patch -p1 -i fontconfig.patch`
 * open _fontconfig.sln_, set _build_ as startup project and compile for Win32 or x64 (you might have to press F7 a few times)
 * run _release-x86.bat_ or _release-x64.bat_

### Pixman
 * download [Pixman 0.26.2](http://dl.hexchat.org/gtk-win32/src/pixman-0.26.2.7z)
 * extract as _C:\mozilla-build\hexchat\pixman-0.26.2_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/pixman) to this folder
 * apply the patch with `patch -p1 -i pixman.patch`
 * open _build\win32\vc11\pixman.sln_, set _install_ as startup project and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### GLib
 * download [GLib 2.34.3](http://dl.hexchat.org/gtk-win32/src/glib-2.34.3.7z)
 * extract as _C:\mozilla-build\hexchat\glib-2.34.3_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/glib) to this folder
 * open _build\win32\vc11\glib.sln_, set _install_ as startup project and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### HarfBuzz
 * download [HarfBuzz 0.9.12](http://dl.hexchat.org/gtk-win32/src/harfbuzz-0.9.12.7z)
 * extract as _C:\mozilla-build\hexchat\harfbuzz-0.9.12_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/harfbuzz) to this folder
 * open _win32\harfbuzz.sln_ and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### Enchant
 * download [Enchant 1.6.0](http://dl.hexchat.org/gtk-win32/src/enchant-1.6.0.7z)
 * extract as _C:\mozilla-build\hexchat\enchant-1.6.0_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/enchant) to this folder
 * open VS x86 or x64 command prompt
 * run _build-x86.bat_ or _build-x64.bat_

### ATK
 * download [ATK 2.7.5](http://dl.hexchat.org/gtk-win32/src/atk-2.7.5.7z)
 * extract as _C:\mozilla-build\hexchat\atk-2.7.5_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/atk) to this folder
 * open _build\win32\vc11\atk.sln_, set _install_ as startup project and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### GDK-PixBuf
 * download [GDK-PixBuf 2.26.5](http://dl.hexchat.org/gtk-win32/src/gdk-pixbuf-2.26.5.7z)
 * extract as _C:\mozilla-build\hexchat\gdk-pixbuf-2.26.5_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/gdk-pixbuf) to this folder
 * open _build\win32\vc11\gdk-pixbuf.sln_, set _install_ as startup project and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### cairo
 * download [cairo 1.12.8](http://dl.hexchat.org/gtk-win32/src/cairo-1.12.8.7z)
 * extract as _C:\mozilla-build\hexchat\cairo-1.12.8_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/cairo) to this folder
 * open _msvc\vc11\cairo.sln_, select the _Release\_FC_ configuration and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### Pango
 * download [Pango 1.32.5](http://dl.hexchat.org/gtk-win32/src/pango-1.32.5.7z)
 * extract as _C:\mozilla-build\hexchat\pango-1.32.5_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/pango) to this folder
 * apply the patch with `patch -p1 -i pango.patch`
 * open _build\win32\vc11\pango\_fc.sln_, set _install_ as startup project and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_

### GTK+
 * download [GTK+ 2.24.15](http://dl.hexchat.org/gtk-win32/src/gtk-2.24.15.7z)
 * extract as _C:\mozilla-build\hexchat\gtk-2.24.15_
 * copy the [HexChat fixes](https://github.com/hexchat/gtk-win32/tree/master/gtk) to this folder
 * apply the patch with `patch -p1 -i gtk.patch`
 * open _build\win32\vc11\gtk+.sln_, set install as startup project and compile for Win32 or x64
 * run _release-x86.bat_ or _release-x64.bat_