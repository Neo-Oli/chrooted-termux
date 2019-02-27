# Run Termux in Termux

A script to setup a chroot jail containing a seperate termux evironment on termux. It can be used for example for testing packages to see if all the requirements are correctly set, because you can start out with a fresh installation of Termux without having to have a dedicated testing device.

After running it you can run "./start.sh" to switch into the the chrooted termux.

## Using Proot

You can use the prooted-termux script to create a jail using proot. This will work without root, but doesn't work correctly with Android 8

## Using proper chroot

Using the chrooted-termux script you can create a jail using unshare and chroot. This will require a rooted device.
