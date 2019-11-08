# Install-Windows-Server-through-VMware-ESXi
**How to Install Windows Server 2016 using VMware ESXi(6.5 Web Client)**

Through out this Tutorial, I am going to use https://oneprovider.com dedicated servers [https://oneprovider.com/dedicated-servers]

Oneprovider is a world leading company for web servers. And one of the cheapest DEDI/BOX provider in the industry(with 0 setup fee).


Also their support system is very useful.

Their payment method includes Paypal with many other payment methods.

In maximum cases, their servers comes with "one click installer", which includes VMware ESXi Web Client.

After receiving server information from Oneprovider, go to "Server manage" page and click on 'reinstall' tab

From there you can choose to install ESXi. [Remember- server re-installation would take 45 to 60 minutes]
  
Every server comes with an IP(ipv4) address. So, when installation of ESXi is finished, one can access WMware ESXI web interface, simply through a web browser.

Just open

`https://SERVER_IP_ADDRESS`

And use your credential to log into it. [Note- use credential, which you had created during ESXi installation]

Anyway, you are welcome to choose any other Dedicated provider, which can allow you to install ESXi on your server.

## Now what is VMware ESXi?

Technical term :

VMware ESXi is an enterprise-class, type-1 hypervisor developed by VMware for deploying and serving virtual computers.
As a type-1 hypervisor, ESXi is not a software application that is installed on an operating system; instead, 
it includes and integrates vital OS components, such as a kernel.

In common words:

Using VMware ESXi, one can create virtual machines. And its virtualization technique allow users to install own custom OS, for example Windows OS trail copy or macOS or any other OS.
 
## Download the OS
### Widows Server 2016 (evaluation copy/180 days free trial)
https://archive.org/download/windowsserver2016datacenterevaluationcopy/Windows_Server_2016_Datacenter%28EVALUATION-copy%29.ISO

### Widows Server 2012 R2 (evaluation copy/180 days free trial)
https://archive.org/download/WS2012R2/WS2012R2.ISO

### Widows Server 2008 R2 (evaluation copy/180 days free trial)
https://archive.org/download/windowsserver2008r2evaluationcopy/WS2008R2.iso

## Download extra dependent server software
https://archive.org/download/extradependentsoftwares/Extra-Dependent-Softwares.iso

## Server Speedtest
Tested on 1Gbps France(Paris) Server 
https://www.speedtest.net/result/8743894889

