UnZip Beta 6.10b, December 10th 2010, is a beta release and considerable additional
work is planned before UnZip 6.10 is released.

Quick list of major changes in UnZip 6.10b:

- Implement Windows full Unicode support.  This support should be automatic now
   on NT and later platforms.
- Add -I and -O options for setting ISO and OEM character sets, respectively,
   used by UnZip when doing character set translations.  This support is based
   on the unzip60-alt-iconv-utf8 patch suggested in an Info-ZIP forum thread
   and uses the iconv library which must be available.  These options are enabled
   using the USE_ICONV_MAPPING compiler macro.  Suggestions welcome on how to
   improve this limited character translation support.
- Various cleanup of VMS and Unicode code.
- Better handling of the PKWare verification bit.
- Fix bug in DLL code that prevented compiling.
- Minor updates to the VB6 example code showing use of the DLL.
- Implement Acorn port changes based on patch provided by J.L. that updates
   the port to use current compilers, increases allowed file path lengths to
   1024 characters, adds directory attributes support, and updates documentation.

See the UnZip manual page and the extended help in UnZip for details of UnZip
features and how to use them.

As always, send in your feature suggestions and bug reports as they influence
development efforts.

Enjoy!
