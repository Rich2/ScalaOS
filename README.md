# ScalaOS

An operating system built from scratch with just a Linux Kernel. Don't know if this project wil ever get anywhere.
git clone git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux-stable.git
cd linux-stable
git checkout -b stable v6.16.9
make defconfig
y to include n to exclude
sudo apt install libelf-dev
sudo apt install elfutils