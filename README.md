related
=======

Here you can download files for the related package.

GenotypeData.txt = example genotype file that can be used for testing.

related_0.8.tar.gz = source code that can be downloaded and compiled on Linux (or any) machines (tested on Ubuntu 14 - Trusty Tahr)

related_0.8.tgz = binary for Mac OS X (tested on Mac OS X 10.9 - Mavericks, Mac OS X 10.8 - Mountain Lion, and Mac OS X 10.7 - Lion)

related_0.8.zip = binary for Windows (tested on Windows 7 and Windows Vista)

*******************************
Problems - Mac Users
*******************************
Note that some Mac users are getting the following error message:


Error in dyn.load(file, DLLpath = DLLpath, ...) : 
  unable to load shared object '/Library/Frameworks/R.framework/Versions/3.1/Resources/library/related/libs/related.so':
  dlopen(/Library/Frameworks/R.framework/Versions/3.1/Resources/library/related/libs/related.so, 6): Library not loaded: /usr/local/lib/libgfortran.2.dylib
  Referenced from: /Library/Frameworks/R.framework/Versions/3.1/Resources/library/related/libs/related.so
  Reason: image not found

If you get this, you need to install gfortran (a FORTRAN compiler). This can be done by downloading and then installing the gfortran-4.2.3.dmg file from this website: http://cran.r-project.org/bin/macosx/tools/

********************************
Problems - Windows Users
********************************
Some Windows users are getting the following error message:


Error\: package ‘related’ is not installed for 'arch = x64'
In addition: Warning message:
package ‘related’ was built under R version 3.1.0  

If you get this, you need to change the default R settings in RStudio to the 32-bit version. You can do this from RStudio by going to Tools -> global options.
