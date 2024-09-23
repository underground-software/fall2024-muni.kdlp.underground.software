# Compile smallest custom kernel
Configure, build and test your own kernel for the x86 64 bit architecture from Linuses git tree. Smallest as possible.

# What to submit:
-   Gzipped custom configuration kernel file
-   Achieved size of the kernel with the compiled modules
-   Time spend on assignment in hours

# Procedure:
-   Clone Linuses git tree.
-   Checkout release version 6.10
-   Do “make defconfig” to load default configuration (try to not cheat and avoid using tiny config)
-   Start the configuration process using “make menuconfig” (You will probably have to install several system packages like gcc, make, ncurses-devel)
-   Build the kernel using “make”
-   Repeat the configuration and build steps until you achieve the smallest bootable kernel (including kernel modules)
-   Hint, you can copy the modules to a separate directory to check for their size using “make modules_install INSTALL_MOD_PATH=\<path\>”

# Requirements:
-   The compiled kernel must boot on a default qemu x86 64-bit machine with ext4 FS and a ttyS0 console.

# Points
-   Maximum points for this assignment are 10.
