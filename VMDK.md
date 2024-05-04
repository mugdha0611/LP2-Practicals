for virtual machine thing
download vmdk from : https://drive.google.com/drive/u/0/folders/1me_nJJh0fvdDOXX3ew2jzGQpoP7f_iFt
then ls
ifconfig
touch filename.txt
cat filename.txt (to show contents)
nano filename.txt (built in editor)
to transfer:
scp filename.txt vagrant@ipadd(inet):/home/vagrant


Find a procedure to transfer two text files from one virtual machine to another virtual machine. Also, add some text in the file and display it before and after transfer on both the VMs.

- [VMDK File](https://drive.google.com/drive/folders/1me_nJJh0fvdDOXX3ew2jzGQpoP7f_iFt)
- SCP Command:
  ```sh
  scp <filename> <hostname>@<inet>:/home/vagrant
  ```
  (Here, the hostname is of the destination VM.)