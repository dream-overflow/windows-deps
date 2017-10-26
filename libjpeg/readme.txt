All files in this directory are NOT under the Dream Overflow Team Copyright

If you need to recompile libjpeg.lib you need to download the full archive
at http://www.ijg.org.

The makefile already present is for Visual C++ in multi-threaded (/MT)
Use this command line for a release .lib:

@nmake nodebug=1 clean all

FireBird, objective3d@free.fr

NB: If you use Objective-3D in BGR pixel format recompile libjpeg in BGR
format too. See jmorecfg.h (RGB_RED,RGB_BLUE). These four includes file must
be preserved for keep the compatibility with O3D.