# HRED J2000
## Summary
From the marketing materials: 
>The HRED J2000 -- a 4-lane PCIe board that contains a highly parallel JPEG2000 encoding/decoding engine capable of processing multiple video streams simultaneously. The streams can compress video from its PCIe interface or from its up to two DVI-I dual link interfaces, decompress video over its PCIe interface, and perform raw frame captures from its up to two DVI-I dual link interfaces. The HRED J2000 is ideal in command and control scenarios where high resolution video must be moved between multiple video sources, storage devices, and display surfaces. In effect, the HRED J2000 is a JPEG 2000 hardware accelerator!

### Technologies

* Device
    * Type - [Altera Nios2](https://en.wikipedia.org/wiki/Nios_II)
    * Developed Firmware - C/C++
* PCIe integration
    * Developed Device Drivers
        * Linux character device driver - C kernel module
        * Windows device driver - C kernel mode driver (KMDF)
* Developed Customer SDK
    * Based on [Qt 4.8 framework](https://en.wikipedia.org/wiki/Qt_version_history#Qt_4)
    * C++ with OpenGL view of media stream

