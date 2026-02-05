# Documentations

# My PC Build Documentation

## My PC Snapshot

**System Information**

<img width="510" height="76" alt="image" src="https://github.com/user-attachments/assets/c92b7144-c067-4f8e-888f-22e060ce77d5" />;


<img width="227" height="73" alt="image" src="https://github.com/user-attachments/assets/2c7e5b17-8912-46d9-8b67-3a90099ca6b2" />



```
Lenovo ThinkPad X1 Carbon 7th
Model: 20QD0000US
BIOS version: N2HET84W (1.67 )
Mode: UEFI
Secure Boot: On
TPM: Yes - Ready for use
```
**Device Manager**

  <img width="322" height="266" alt="image" src="https://github.com/user-attachments/assets/e178d441-cb16-4556-a725-186507b50943" />;
  
   
   <img width="221" height="44" alt="image" src="https://github.com/user-attachments/assets/e5007e1a-00dd-4f4c-b4e2-4b0a56226049" />


**OS**
   
   <img width="472" height="57" alt="image" src="https://github.com/user-attachments/assets/3dabdba5-82d3-4f93-823c-9ce6f050d953" />


```
Windows 11 Home
Version	10.0.26200 Build 26200
64-bit operating system, x64-based processor
```
**CPU**

<img width="641" height="35" alt="image" src="https://github.com/user-attachments/assets/2aae2116-6d4d-4889-b88c-ed5880948c42" />


```
Processor: Intel(R) Core(TM) i7-8565U CPU @ 1.80GHz
4-cores 8-threads
```
**RAM**

<img width="352" height="138" alt="image" src="https://github.com/user-attachments/assets/765c8cff-5ff7-40b8-9042-ecbf096a8e1a" />


```
Installed RAM: 16 GB (15.8 GB usable)
```
**Storage**

<img width="179" height="134" alt="image" src="https://github.com/user-attachments/assets/97970d0d-9a19-4ee1-8bf0-f376850c708e" />


```
SAMSUNG MZVLB512HBJQ-000L7
SSD
Nvme
343 GB of 477 GB used

```

### How To:
PowerShell commands to retrieve the following:
- 0S name, version, 32/62 bit
```
Get-ComputerInfo | Select-Object OsName, WindowsVersion, OsArchitecture
```
<img width="367" height="52" alt="image" src="https://github.com/user-attachments/assets/0c7035f6-bd8a-4119-bacc-497a89b62a2b" />

- CPU model & Cores/threads
```
```
- RAM Modules Size + Speed
```
```
- Storage Model + Type (NVMe/SATA) + Media Type + Size
```
```

- TimeZone
```
Get-TimeZone
```
