# ch340
### modified version of CH340/CH341 drivers for arch linux

Make sure not to use zen kernel, else it complains about /lib/modules/?.?.?-zen1-1-zen/build missing 




## Compile 
compile
```sh
make
```
load
```sh
sudo make load
```

copy
```sh
sudo cp -v ch34x.ko /lib/modules/$(uname -r)/kernel/drivers/usb/serial
```

uinstall brltty
```sh
yay -R orca brltty
```

## Instructions (not from me)
https://cdmana.com/2022/04/202204051838283142.html

http://www.wch.cn/download/CH341SER_LINUX_ZIP.html
