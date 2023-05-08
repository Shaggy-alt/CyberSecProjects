This will instruct on how to install vitrual box along with oracle extension. I will also include kali/metasploitable machines installation guide here. 


NOTE: Some Vulnerable machines if misconfigured can be left open to the public. 

_____________________________________________________________
INSTALLING
_____________________________________________________________


Visit https://www.virtualbox.org/wiki/Downloads to download the most current version. I would also advise installing the oracle extension pack aswell. 
The extension pack provides the following added functionality:

VirtualBox Remote Desktop Protocol (VRDP) support. See Section 7.1, “Remote Display (VRDP Support)”.

Host webcam passthrough. See Section 9.5, “Webcam Passthrough”.

Intel PXE boot ROM.

Disk image encryption with AES algorithm. See Section 9.29, “Encryption of Disk Images”.

Cloud integration features. See Section 1.16, “Integrating with Oracle Cloud Infrastructure”.

For details of how to install an extension pack, see Section 2.5, “Installing an Extension Pack”.

This video provides a walkthrough from downloading to installing a windows 7 machine. 
( I recommend installing A windows 10 instead for pen-test practice, win7 is also no longer being provided by microsoft.)

Video below:
| https://www.youtube.com/watch?v=NwCYnOab2Zo&ab_channel=ComputerSupport |



Once installed you can follow the same process for the kali machine OR you can download the virtual machine version's of kali

vm link below:
| https://www.kali.org/get-kali/#kali-virtual-machines |


_____________________________________________________________
NETWORK SETUP
_____________________________________________________________


TO reach the network setting. Right click on the machine you'd like to edit. 
Select settings, from here a pop up should happen and you will see the network selction between Audio & Serial Ports. 
You will have 4 adaptors. Ensure that only one is being used at a time unless you know what you are doing. 

---------------------
NETWORK TROUBLE SHOOT: Sometimes when I use legacy machines and I want to connect with another vm machine I would need to change its adapter type within Advanced. 
Normally you wouldnt want to touch anything in advanced but incase here are why you would want to change this. 

  -AMD PCnet-PCI II (Am79C970A). This network adapter is based on AMD chip and can be used in many situations. 
   As for Windows guests, this network adapter can be used for older Windows versions (such as Windows 2000) because newer Windows versions such as Windows 7, 8 and 10 do not contain a built-in driver for this adapter. 
   Originally, the Am79C970A PCI device contained a single chip 10-Mbit controller and the DMA engine was integrated. This network adapter also supports AMD’s Magic Packet technology for remote wake-up.

  -AMD PCnet-FAST III (Am79C973). This virtualized network adapter is supported by almost all guest operating systems that can run on VirtualBox. 
  GRUB (the boot loader) can use this adapter for network boot. Similarly to the previous network adapter, this one is based AMD chip.

  -Intel PRO/1000 MT Desktop (82540EM). This adapter works perfectly with Windows Vista and newer Windows versions. The most of Linux distributions support this adapter as well.

  -Intel PRO/1000 T Server (82543GC). Windows XP recognizes this adapter without installing additional drivers.

  -Intel PRO/1000 MT Server (82545EM). This adapter model is useful to import OVF templates from other platforms and can facilitate import process.

  -Paravirtualized Network Adapter (virtio-net) is a special case. Instead of virtualizing networking hardware that is supported by most operating systems, a guest operating system must provide a special software interface for virtualized environments. 
   This approach allows you to avoid the complexity of networking hardware emulating and, as a result, can improve network performance.
---------------------

HOW I SETUP MY NETWORK FOR OFFLINE PENTESTING: This is for when I can't have any internet access to or from my victim machine as I might be using an 
untested vulnerablilty/malware on said victim machine that could result in data loss/hardware loss. 
  -
