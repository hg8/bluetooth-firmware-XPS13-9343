# Linux bluetooth firmware for XPS 13 (2015) 9343

Installation :         
```
wget https://github.com/hg8/bluetooth-firmware-XPS13-9343/raw/master/BCM20702A0-0a5c-216f.hcd 
sudo cp BCM20702A0-0a5c-216f.hcd /lib/firmware/brcm/
```    

Reload bluetooth module :    
```
sudo modprobe -r btusb   
sudo modprobe btusb
```    
