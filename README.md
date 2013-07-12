Debian packaging of SGABIOS
===========================

This git repository contains the Debian packaging of SGABIOS. It is not meant
to be used for developing SGABIOS itself. If you want to contribute to SGABIOS
please visit: https://code.google.com/p/sgabios/


Reporting bugs
--------------
Bugs regarding SGABIOS in Debian or issues with the packaging itself can be
reported using Debian's bugtracker at: http://bugs.debian.org/sgabios


About SGABIOS
=============
The Google Serial Graphics Adapter BIOS or SGABIOS allows one to interact with
a physical or emulated system independent from the operation system on BIOS
level. It does that by providing over a serial port the output capabilities
normally featured by a VGA graphics card and the input capabilities normally
handled by a keyboard. This is useful for selecting a boot-device during
startup or to access feature provided by option roms (e.g. accessing a gPXE
console). Further details can be found
* in the file [README.Debian](sgabios/debian/README.Debian)
* in the file [design.txt](sgabios/design.txt)
* online at https://code.google.com/p/sgabios/


Legal
-----
* SGABIOS is Licensed under the Apache License, Version 2.0 - see [sgabios/COPYING](sgabios/COPYING)
* The Debian packaging is released [GNU General Public License (GPL) 3.0](http://www.gnu.org/licenses/gpl-3.0.txt)

ANY CONTENT IN THIS REPOSITORY IS PROVIDED "AS IS" AND THE AUTHORS DISCLAIMS
ALL WARRANTIES WITH REGARD TO ANY CONTENT IN THIS REPOSITORY INCLUDING ALL
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE
AUTHORS BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES
OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER
IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF ANY CONTENT IN THIS REPOSITORY.
