# ROCK Pi SATA

[Quad SATA HAT](<https://wiki.radxa.com/Dual_Quad_SATA_HAT>) for Raspberry Pi 4B+/3B+

![sata-hat](https://setq.me/static/img/quad-sata-hat.png)

## Description
Mirror the latest version with additional minor changes.


[Seller in DE](https://shop.allnetchina.cn/collections/sata-hat/products/quad-sata-hat-case-for-raspberry-pi-4).


## Setup
Script ```get-rockpi-sata.sh ```
references raspbi-sata-0.14.deb which has also been uploaded under files.

[Youtube guide](https://www.youtube.com/watch?v=Eix0PCB0byQ).

Original location of install script:  
```curl -sL https://rock.sh/get-rockpi-sata | sudo -E bash -```


## Miscellaneous

### Possible issues and resolutions
https://forum.radxa.com/t/quad-sata-kit-and-openmediavault-5-raspberry-pi-4/3193


### Software configuration
Edit ```/etc/rockpi-sata.conf ``` then ```sudo systemctl restart rockpi-sata.service``` to take effect. Under ```conf``` you can find the ```/etc/rockpi-sata.conf```, which you can modify accordingly.