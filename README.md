<h1>Reconnaissance with NMAP, Zenmap, and Masscan</h1>

<h1 align="center">
 
<h2>Description</h2>
<b>Utilized a Kali Linux machine to run some useful Security tools that typically help with Network Reconnaissance (possibly before pentesting) I will demonstrate the use of the tools NMAP, Zenmap, and Masscan.
</b>
<br />
<br />

<h2>Recon with NMAP</h2>
<b>- Prior to Using NMAP, make sure to stop docker. If it is in use as there may be a segmentation issue. Otherwise install NMAP by running the command "sudo apt install nmap". Once it is installed you can run scans of any machine on the network utilizing the target's IP address. You can see port states along with specifying certain ports to be scanned:</b> 
<br />
<br />

Here is an example of nmap being run:
<p align="center"

![NMAP Scan ](https://github.com/jlam744/NetworkAnalysis/assets/95711303/0a9bc240-7d53-4b7c-a343-e594bba09649)
![NMPA Popular ports](https://github.com/jlam744/NetworkAnalysis/assets/95711303/cc6e7a0b-7fad-426f-8b98-ebc820dd9ea1)
![NMAP Specific TCP scan](https://github.com/jlam744/NetworkAnalysis/assets/95711303/f81c4fad-f2b7-4d04-b71b-5bef09d050d0)


NMAP being used to identify versions of software running on ports:

<p align="center"

![NMAP Softwware Version](https://github.com/jlam744/NetworkAnalysis/assets/95711303/33bfb6f9-1274-40d4-bdf5-1dab111ab2df)


Nmap has scripts to test for vulnerabilities

<p align="center"

![NMAP Vulnerability Scan](https://github.com/jlam744/NetworkAnalysis/assets/95711303/ca072424-65e1-4950-a4a6-87955324deb7)


</p>
<h2>Recon with Zenmap</h2>
- <b>When Zenmap is installed input the target IP and the command you want to be executed in this instance I compared the result to the previous NMAP scan:</b>

<p align="center"

![Zenmap scan](https://github.com/jlam744/NetworkAnalysis/assets/95711303/6425cc30-6cff-4eee-af9e-cd7c908d0918)
![Zenmap results](https://github.com/jlam744/NetworkAnalysis/assets/95711303/e8bc4ff1-754d-4f21-a112-18aa607b7ba9)
![Zenmap Portshosts page](https://github.com/jlam744/NetworkAnalysis/assets/95711303/ce03dd42-5f74-4b44-8d66-b3fbf962cc66)


</p>

<h2>Recon with Masscan</h2>
- <b>Use Masscan nmap like features or use a simple scan with ip address with a certain port:</b>
<p align="center"
 
![Masscan Nmap](https://github.com/jlam744/NetworkAnalysis/assets/95711303/f46aebaf-fbbd-4a98-bd65-cca46e732130)
![Masscansimplescan](https://github.com/jlam744/NetworkAnalysis/assets/95711303/6c69ee4d-fd80-43f1-b89b-feb643a10d40)

</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
