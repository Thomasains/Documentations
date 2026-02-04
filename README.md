# Documentations

Document all external ports, if you can open your desktop also identify all internal connectors. Please take 6-10 labeled photos (ports + any internal components you can safely access) A one page "connector map" (diagram/table) that matches port/connector -> purpose -> common issue (ex: USB C data + power + video sometimes: common issue: wrong cable (Thunderbolt))

If you have a laptop:

Use system tools to identify motherboard / platform details
Collect screenshots: 
System Information (Model/Bios), 
Device Manager (Network adapters, Display adapters), 
Storage type (disk drives / task manager) (HDD/SATA SSD, NVMe SSD (Capacity vs storage left))
OS Name
In general (specs)
Manufacturer and Model of Device
CPU
Cores + threads
RAM Amount
RAM Speed 
On board or dedicated GPU (Model?)

UEFI or Legacy BIOS Mode?
Secure Boot Enabled?
Do you have a TPM? - Yes "Ready for use"

# My PC Build Documentation*tbd

## My PC Snapshot

[screeshot* PowerShell?]
**System Information**

<img width="828" height="123" alt="image" src="https://github.com/user-attachments/assets/f509f9a6-d5df-4ec6-be70-3778c34505ec" />

<img width="278" height="93" alt="image" src="https://github.com/user-attachments/assets/f0573b1b-dd79-46c5-8a78-bc0f804d6d60" />


```
Lenovo ThinkPad X1 Carbon 7th
Model: 20QD0000US
BIOS version: N2HET84W (1.67 )
Mode: UEFI
Secure Boot: On
TPM: Yes - Ready for use
```
**Device Manager**

  <img width="424" height="351" alt="image" src="https://github.com/user-attachments/assets/cf99f62c-1ad5-4fe6-a590-ed70157b9448" />;
  
   
   <img width="298" height="59" alt="image" src="https://github.com/user-attachments/assets/fa612535-1084-43e7-891e-03050de9026d" />

**OS**
   
   <img width="571" height="69" alt="image" src="https://github.com/user-attachments/assets/0e4e3b3d-e4cf-481e-8c10-3ff11b719782" />

```
Windows 11 Home
Version	10.0.26200 Build 26200
64-bit operating system, x64-based processor
```
**CPU**

<img width="1074" height="26" alt="image" src="https://github.com/user-attachments/assets/02718eb2-9098-43ed-9033-48b7a460c925" />

```
Processor: Intel(R) Core(TM) i7-8565U CPU @ 1.80GHz
4-cores 8-threads
```
**RAM**

<img width="385" height="151" alt="image" src="https://github.com/user-attachments/assets/21d41083-643b-4d8e-8805-4da5591dbf7f" />

```
Installed RAM: 16 GB (15.8 GB usable)
```
**Storage**

<img width="308" height="236" alt="image" src="https://github.com/user-attachments/assets/510d41c6-9aba-4b0c-840f-22240f7d295f" />

```
SAMSUNG MZVLB512HBJQ-000L7
SSD
Nvme
343 GB of 477 GB used

```

### How To:
Use PowerShell to retrieve this information:
- 05 name, version, 32/62 bit
- CPU model & Cores/threads
- RAM Modules Size + Speed
- Storage Model + Type (NVMe/SATA) + Media Type + Size

** Find out your current TimeZone **
*** powershell
Get-TimeZone
