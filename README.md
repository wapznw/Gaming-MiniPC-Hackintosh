# Gaming-MiniPC-F7-Hackintosh

|  规格   | 详细信息  |
|  ----  | ----  |
| 电脑型号  | gaming mini pc f7 |
| 处理器  | 英特尔 酷睿 i9 - 8950HK |
| 内存  | 24G |
| 硬盘  | 海康威视C2000PRO - 1T |
| 显卡  | 核显 |
| 网卡  | intel 3165 |

---

# BIOS设置

### 禁用以下项
1. Fast Boot
2. Secure Boot
3. Serial/COM Port
4. Parallel Port
5. VT-d (can be enabled if you set DisableIoMapper to YES)
6. CSM
7. Thunderbolt(For initial install, as Thunderbolt can cause issues if not setup correctly)
8. Intel SGX
9. Intel Platform Trust
10. CFG Lock (MSR 0xE2 write protection)(This must be off, if you can't find the option then enable AppleXcpmCfgLock under Kernel -> Quirks. Your hack will not boot with CFG-Lock enabled)

### 启用/设置以下项
1. VT-x
2. Above 4G decoding
3. Hyper-Threading
4. Execute Disable Bit
5. EHCI/XHCI Hand-off
6. OS type: Windows 8.1/10 UEFI Mode
7. DVMT Pre-Allocated(iGPU Memory): 64MB
8. SATA Mode: AHCI

# 截图

![Screenshot](Screenshot/cc554687-0792-4717-ab7a-4ed10c745635.jpg)

![Screenshot](Screenshot/1.png)

![Screenshot](Screenshot/2.png)

![Screenshot](Screenshot/3.png)
