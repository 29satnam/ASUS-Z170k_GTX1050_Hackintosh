# Hackintosh built on Skylake Asus-Z170k and Sapphire RX580 Pulse 8GB GPU 
![alt text](https://raw.githubusercontent.com/29satnam/Skylake-RX580-Hackintosh/master/simage.png)

### OpenCore
  - I removed the MBL, SystemSerialNumber and SystemUUID for privacy. You can look one for yourself.
  - And I will be uploading OpenCore EFI builds 10.15.3 (19D76) onwards.

#### Why OpenCore?
  - Better memory management, 8 seconds bootup time.
  - Dual screen issue with the newer clover builds, I've not been able to update clover for some time.
  - OpenCore seems like the future of hackintosh machines.

#### BIOS Settings
  - Serial Port = OFF
  - OS Type = Other OS
  - Fast Boot = Works both way
  - CSM = Enabled
  - Intel Platform Trust = Disable
  - VT-d = Disable
  - VT-x = Enable
  - Above 4G decoding = Enable
  - CFG Lock = Disabled

### What works?

  - Multi-Monitor with full acceleration
  - Ethernet
  - And all necessary stuff you need
  - BCM94360CD Wireless/Bluetooth card OOB
  - Sleep and Wake

### Hardware Acceleration:
![alt text](https://raw.githubusercontent.com/29satnam/Skylake-RX580-Hackintosh/master/videoprocapp.png)

### Geekbench 4 GPU:
![alt text](https://raw.githubusercontent.com/29satnam/Skylake-RX580-Hackintosh/master/geekbenchgpu.png)
[Link to Geekbench](https://browser.geekbench.com/v4/compute/4339920)

### Geekbench 4 CPU:
![alt text](https://raw.githubusercontent.com/29satnam/Skylake-RX580-Hackintosh/master/geekbench.png)
[Link to Geekbench](https://browser.geekbench.com/v4/cpu/14036508)
