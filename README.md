
<div align="center">
  <a >
    <img src="images/impleo_logo.png" alt="Logo" >
  </a>
</div>

# KlvStreamInjector
**KlvStreamInjector** - command line utility that adds MISB 0601.X metadata to a transport stream sent over UDP.  
More [info](https://www.impleotv.com/content/klvstreaminjector/help/index.html).

## System Requirements
OS: Windows 10 64 bit.

## Installation

**KlvStreamInjector** can be downloaded as a **zip** file that contains the installer.  
Unzip the **SetupKlvStreamInjector.zip** file and run the **SetupKlvStreamInjector.exe**  

## Download link

| Software | Version             | Download link                                                           | 
|:---------|:-------------------:|:------------------------------------------------------------------------|
| **STANAG KlvStreamInjector** |  v2.2.12 | [SetupKlvStreamInjector.zip](https://github.com/impleotv/klv-stream-injector-release/releases/latest/download/SetupKlvStreamInjector.zip) | 

*Released on Thu, 15 May, 17:31 GMT+3*

## License

No license is needed for application evaluation - it will work in demo mode (with some restrictions). 

**KlvStreamInjector** is a node-locked software, so you have to get a license (after purchasing the SW) in order to lift demo restrictions. Please install it and fill out an [online form](https://docs.google.com/forms/d/e/1FAIpQLSd_XW6bDsFce1G1cpds4gMQNlwNax0CvkWzcMbscxZ5rLaIbA/viewform), providing the ***Node Info*** string (IMPORTANT!!!) for the target machine.  
***Node Info*** string can be seen when you run the application (or press N - Show NodeInfo), as shown below.

```
C:\Program Files\ImpleoTV\KlvStreamInjector\Bin\x64\KlvStreamInjectorProc.exe
```

![NodeInfo string](images/license.png)

Copy and paste the Node Info string into the online form, or email it to support@impleotv.com.
If your computer is offline or you're unable to copy the Node Info text, take a photo of the window with the QR code clearly visible and send it to us instead.

![NodeInfo QR](images/licenseQR.png)

You'll receive a license file (or both a license file and a key for legacy licensing mechanism) that can be passed as arguments:

Use *--licenseFile* for example:
```
 --licenseFile "D:\Licenses\KlvStreamInjector.lic" 
```

Or, for legacy versions,  *--licenseFile* and *--licenseKey* as arguments, for example:
```
 --licenseFile "D:\Licenses\KlvStreamInjector.lic"  --licenseKey DDD8460B-8419FF85-0B36C1B5-3FC6143C
```
If the license file is in the same directory as the .exe, you can skip the path.
