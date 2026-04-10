# KaOS-Notes

## Printing

* cups and pyqt5-python3 are dependencies of hplip
* Then use HP Device Manager to add the printer.
* FWIW, choosing the IPP listing for the device is best.

## Oracle VirtualBox
```
sudo modprobe -r kvm_intel
```

## KCP Notes
```
pckcp
updpkgsums
```

## Boot Immediately
```
sudo bootctl set-timeout 0
```

## Disable WiFi Power-saving
```
sudo vim /etc/NetworkManager/conf.d/wifi-powersave.conf
i
[connection]
wifi.powersave = 2
<esc>
:wq
```
