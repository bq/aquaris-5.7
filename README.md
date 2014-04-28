WHAT IS THIS?
=============

Linux Kernel source code for the device bq Aquaris 5.7

BUILD INSTRUCTIONS?
===================

Specific sources are separated by branches and each version is tagged with it's corresponding number. First, you should
clone the project:

	$ git clone git@github.com:bq/aquaris-5.7.git

After it, choose the version you would like to build:

	$ cd aquaris-5.7/
	$ git checkout 1.0.3-20140313-1640


Finally, build the kernel:

	$ ./makeMtk -t eastaeon89_wet_jb2 n k

