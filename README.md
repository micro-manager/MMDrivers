# MMDrivers

Drivers to be used with several devices supported in Micro-Manager on Windows OS.  Currently, these are all libusb-based drivers that enable sending/receiving messages to the device (a task carried out by the Micro-Manager device adapter).  These drivers are alternatives to the vendor-supplied drivers, and can not be used at the same time (i.e. the vendor-supplied driver will need to be uninstalled before installing the MMDriver, and vice versa).  

Currently, there are drivers for the Velleman K8055, K8061, Nikon AZ100 and Eclipse 90i. The drivers are unsigned, so you will need to bypass the Windows security alerts to install them.  
