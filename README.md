# Running cmsShow in VirtualBOx
## 1. Install virtual box
 Download dmg for OSX. Att installation time grant *all* security permissions asked the install time (e.g. network) 

https://www.virtualbox.org/wiki/Downloads

## 2. Download centos-7 image 
https://cernbox.cern.ch/index.php/s/qmOGnySELgvA8d1

## 3. Create VM with the centos iamge

Run VirtualBox and create a new VM with the downloaded Centos-7 image
<br>
<img src="https://raw.githubusercontent.com/alja/fireworks-virtualbox/main/doc/NewVM-virtualdisk.png" height="400px">

## 4. Run Centos-7 VM 
Start VM and login as user *osboxes.org* and password which is the same as the username *osboxes.org*

### Set autoresize or fixed resolution in the bottom right toolbar 

<img src="https://raw.githubusercontent.com/alja/fireworks-virtualbox/main/doc/vbox-autresize.png" height="500px">

### 5. Download and run cmsShow
```
wget https://cmsshow-rels.web.cern.ch/cmsShow-rels/cmsShow-11.1.2.tar.gz
tar xzf  cmsShow-11.1.2.tar.gz
cd  cmsShow-11.1.2
./cmsShow data.root
```


