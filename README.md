# suhosin-windows



Suhosin Extension for windows

if you do not want to bother compiling suhosin

you can download the file to the php_suhosin.dll <a href="https://github.com/andykimpe/suhosin-windows/tree/master/binary"> binary file </a>

SEVERAL file you find the one you should choose

depends on the architecture and php version only wish use

If want to compile manually suhosin

I invite you to follow the directions on this page http://wiki.php.net/internals/windows/stepbystepbuild

Note that you should replace the configure command by the latter

configure --disable-all --enable-cli --enable-session --enable-zlib --enable-suhosin="shared"









