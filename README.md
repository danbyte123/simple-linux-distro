# simple-linux-distro
you can run it using qemu or vmware
and it is  used for testing and fun (becuse it has some setup problems ) and its non graphical 
 

You can run it using QEMU or VMware.

And it is used for testing and fun (because it has some setup problems) and is non-graphical.

## How to Run
download it first 
```bash
git clone https://github.com/danbyte123/simple-linux-distro-s1-.git
```
navigate to it 
```bash
cd simple-linux-distro-s1-
```
download the boot file from here and put it in the simple-linux-distro-s1- folder
```
https://drive.google.com/file/d/1v1Iiqd56J2kKsk66vGKOPPN4u7B003xp/view?usp=sharing
```

give root premission
```
sudo su
```

start qemu 
```bash
qemu-system-x86_64 boot
```
sys linux will boot up copy and paste this in the boot 
```bash
/bzImage -initrd=/init.cpio
