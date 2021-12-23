[中文请移步](https://markipop.github.io/posts/ff690038/)


[English Guide]
### Configuration Information
Model : lenovo G50-70m
| Hardware         | Properties                                           |
| ---------------- | ---------------------------------------------------- |
| Cpu              | i5-4210u                                             |
| nGPU             | Intel(R) HD Graphics 4400                            |
| iGPU             | GF820M（GPU code name GT117）                        |
| Memory           | DDR3L 8*2                                            |
| Hard Disk        | 500G ssd                                             |
| Wireless network | Replaced with BCM95342Z                              |
| Ethernet         | Realtek RTL8168/8111                                 |
| BIOS ver         | Build Number: 2179 PC 14.34 10/07/2013 10:03:35      |
| Audio            | Intel Lynx Point-LP PCH（ Conexant CX20751/CX20752） |

oc version: 0.7.7
Boot start macOS：Big Sur（can also be Boot start Monterey,But there maybe some problems with the Bluetooth function）


### Normal items:
- Wi-Fi
- Bluetooth
- Onboard
- Relay
- Airdrop
- Brightness adjustment (control center slider adjustment)
- Sound adjustment (button + control center adjustment)
- HDMI output
- Nuclear display acceleration
- Battery status
- ...
- ...

### Anomaly items:
- Touchpad buttons
- Brightness adjustment (button adjustment)
- ...


### Screenshot
![](https://pic.imgdb.cn/item/61c4496a2ab3f51d919b13c8.png)

![oc ver](https://pic.imgdb.cn/item/61c41cea2ab3f51d91861fdf.png)

![](https://pic.imgdb.cn/item/61c41cea2ab3f51d91861fe8.png)

![](https://pic.imgdb.cn/item/61c44a2d2ab3f51d919b6617.png)

![](https://pic.imgdb.cn/item/61c44a752ab3f51d919b80d0.png)

![](https://pic.imgdb.cn/item/61c44ab52ab3f51d919b96cf.png)


### lenovo Old model bios whitelist
As far as I know, older HP and Lenovo computers have bios whitelist restrictions, which means that the wireless network card 
cannot be directly upgraded or replaced. There are two methods:

- Delete the whitelist module
- Write the hardware ID of the wireless network card that needs to be replaced and upgraded into the bios whitelist

Both methods involve brushing bios, so they are risky. I prefer to choose the first one, because the whitelist restriction 
has been removed, and the network card needs to be replaced in the future, and there is no need to rewrite the new network 
card id into the bios. For this part of the question, there will be a separate tutorial, you can go to see if you need it.


### Contect me
If you encounter any problems during this period, you can email me or go to the forum for help.

e-mail: kaiup6@gamil.com
