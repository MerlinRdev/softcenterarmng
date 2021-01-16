# Softcenter for ARM

本软件中心是基于armv7l平台路由器的软件中心,适用于linux内核为4.1和3.14的armv7l架构的路由器！

## 兼容机型

支持的机型：
1. 华硕 `RT-AX56U` `RT-AX58U` `RT-AX3000` `RT-AX82U` `TUF-AX3000` `RT-ACRH17`
2. 网件 `RAX20` `RAX50`

## 开发须知：

如果你是开发者，想要开发新的插件，并用离线包的方式进行传播，请了解以下内容：

1. 在程序方面：由于固件采用了版本为4.1/3.14的linux内核，和armv7的编译器，所以请确保你编译的程序是armv7架构的。
2. 仅支持有FPU的armv7l架构cpu.

**软件中心各架构列表：**

|  软件中心   |                        mips软件中心                        |                 arm软件中心                  |                      arm64软件中心                       |                    armng软件中心                    |            mipsle软件中心             |
| :---------: | :----------------------------------------------------------: | :---------------------------------------------: | :----------------------------------------------------------: | :-----------------------------------------------: |:-----------------------------------------------: |
|  项目名称   | [softcenter](https://github.com/paldier/softcenter) | [softcenterarm](https://github.com/paldier/softcenterarm) |       [softcenterarm64](https://github.com/paldier/softcenterarm64)        | [softcenterarmng](https://github.com/paldier/softcenterarmng) |[softcentermipsle](https://github.com/paldier/softcentermipsle) |
|  适用架构   |                            mips                            |                     armv7l                      |                       aarch64                     |                        armv7l                        |                mipsle             |
|    平台     |                             mips                              |                       arm                       |                          hnd/axhnd                           |                     arm                      |            mipsle             |
|  linux内核  |               3.10.104                |                2.6.36.4             |             4.1.27/4.1.51            |             4.x.x/3.x.x            |         3.10.14          |
|     CPU     |                          grx500                           |                    bcm4708/9                    |                          bcm490x                           |                     bcm675x/ipq4/5/6/80xx/mt7622                    |               mtk7621              |
|     FPU     |                          soft                          |                    no                    |                         hard                           |                     hard                     |               soft              |
|  固件版本   |                    MerlinR 5.0.0                     |              MerlinR 5.0.0              |                     MerlinR 5.0.0                      |                  MerlinR 5.0.0                    |                MerlinR 5.0.0                    |
| 软件中心api |                          **1.1/1.5** 代                          |                   **1.1/1.5** 代                    |                          **1.1/1.5** 代                          |                    **1.1/1.5** 代                     |                **1.1/1.5** 代                     |
| 代表机型-1  | [BLUECAVE](https://github.com/paldier/bluecave-merlin) |              [RT-AC68U](https://github.com/paldier/rtac68u)               | [RT-AC86U](https://github.com/paldier/86u-merlin) |                         [TUF-AX3000](https://github.com/paldier/tuf-ax3000)                        |          [RT-AC85P](https://github.com/paldier/ac85p-merlin) | 
| 代表机型-2  | [K3C](https://github.com/paldier/K3C-merlin) |              [K3](https://github.com/paldier/K3-merlin.ng)              | [GT-AC2900](https://github.com/paldier/gt-ac2900) |                         [RT-AX58U](https://github.com/MerlinRdev/rt-ax58u)                        |         RT-ACRH26
| 代表机型-3  | [RAX40](https://github.com/paldier/rax40-merlin) |         [SBRAC1900P](https://github.com/paldier/sbrac1900p-merlin)                                        | [R8000P](https://github.com/paldier/r8000p-merlin) |                        [RT-AX89X](https://github.com/MerlinRdev/rtax89x)                         |         TUF-AC1750         |
| 代表机型-4  | DIR2680 |  [RT-AC5300](https://github.com/MerlinRdev/rt-ac5300)                              | RAX80 |                       [RT-ACRH17](https://github.com/paldier/acrh17-merlin)                         |            [RM-AC2100](https://github.com/paldier/ac85p-merlin)              |

