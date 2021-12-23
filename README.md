# Lenovo G50-70m opencore-0.7.7

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
- sleep/wake
- ...
- ...

### Anomaly items:
- Touchpad buttons
- Brightness adjustment (F11/F12)
- ...


### Screenshot  
<img width="698" alt="WeChat51f065c064275773be0759decbe75e60" src="https://user-images.githubusercontent.com/61401619/147232962-ee505eb3-3b35-4089-86d0-ef9a10ff32da.png">

<img width="1280" alt="截屏2021-12-23 14 50 49" src="https://user-images.githubusercontent.com/61401619/147233075-71820e54-adfc-443d-ae61-3531ffa850d7.png">


<img width="1271" alt="WeChat4ad293db781322d7d666d2b90e5d8076" src="https://user-images.githubusercontent.com/61401619/147232974-3f91a5cc-700d-4511-8f0a-16744c83a559.png">

<img width="1289" alt="WeChatede2d6ff3b49c05d8812e71f4fb9a954" src="https://user-images.githubusercontent.com/61401619/147232984-019e8d7f-bddf-459f-bddd-ff188deff623.png">


<img width="1266" alt="WeChat955775ed0e2bb32bb26a837e5e75752f" src="https://user-images.githubusercontent.com/61401619/147233003-56d1c251-0b13-46fd-8eb6-29f3f582c7b1.png">


### lenovo old model bios whitelist
As far as I know, older HP and Lenovo computers have bios whitelist restrictions, which means that the wireless network card 
cannot be directly upgraded or replaced. There are two methods:

- Delete the whitelist module
- Write the hardware ID of the wireless network card that needs to be replaced and upgraded into the bios whitelist

Both methods involve brushing bios, so they are risky. I prefer to choose the first one, because the whitelist restriction 
has been removed, and the network card needs to be replaced in the future, and there is no need to rewrite the new network 
card id into the bios. For this part of the question, there will be a separate tutorial, you can go to see if you need it.


### Contect me
If you encounter any problems during this period, you can email me or go to the [forum](https://www.tonymacx86.com/threads/guide-lenovo-z50-70-z40-70-g50-70-g40-70-using-clover-uefi.261787/) for help.

e-mail: kaiup6@gamil.com

