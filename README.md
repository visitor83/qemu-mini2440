git clone git://repo.or.cz/qemu/mini2440.git

patch mini2440.patch.tar
patch -p1 -i path/to/mini2440.patch

./configure --target-list=arm-softmmu

