# cpgdemo0
### c language and fortran demo programs using pgplot library ###
# instructions for linux  / MacOS 
# to install
./configure
# to compile
make simple
# to run
./simple
# a postscript file containing a plot
# named simple.ps will be created in the
# current directory
# and/or
make run
# instructions for win / msys2 or wine
# to install
./configure
# to compile
make -f Makefile.win simple
# to run
cd i686-w64-mingw32-gfortran
./simple
# a postscript file containing a plot
# named simple.ps will be created in the
# current directory
# and/or
./pgdem1
# if running on ms cmd or wineconsole
pgdem1
