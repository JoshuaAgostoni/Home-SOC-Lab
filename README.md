<h1>Home SOC Lab</h1>



<h2>Project Overview</h2>
This project demonstrates a complete virtual Security Operations Center (SOC) lab environment, including Windows 10, Kali Linux, and Ubuntu Splunk Server VMs. It showcases attack simulations, centralized logging, detection engineering, alert creation, and dashboard visualization. 

<h2>2.	Architecture Design:</h2>

Project Components:
* Create Host-Only Network
* Splunk Server Setup (Ubuntu VM)
* Windows 10 VM Setup 
* Kali Linux VM Setup
* Attack Simulation
* Detection Engineering
* Security Principles Demonstrated


<h2>Environments Used: </h2>

<b> Ubuntu Linux VM - Windows 10 VM - Kali Linux </b>

<h2>Program walk-through:</h2>

<p align="center">
Shows VirtualBox Network Manager with Host-Only network created and DHCP enabled. <br/>
<a href="https://imgur.com/ALBoTav"><img src="https://i.imgur.com/ALBoTav.png" title="source: imgur.com" /></a>
<br />
<br />
Shows Splunk Server(Ubuntu) VM RAM and Host-Only network adapter configuration.  <br/>
<a href="https://imgur.com/kDJtsFV"><img src="https://i.imgur.com/kDJtsFV.png" title="source: imgur.com" /></a>
<br />
<br />
Displays IP address assigned to Splunk Server VM. <br/>
<a href="https://imgur.com/L9vXrMA"><img src="https://i.imgur.com/L9vXrMA.png" title="source: imgur.com" /></a>
<br />
<br />
Splunk dashboard after successful login.  <br/>
<a href="https://imgur.com/IaTZKzJ"><img src="https://i.imgur.com/IaTZKzJ.png" title="source: imgur.com" /></a>
<br />
<br />
Shows receiving port 9997 enabled for forwarder data.  <br/>
<a href="https://imgur.com/5d6k5Gu"><img src="https://i.imgur.com/5d6k5Gu.png" title="source: imgur.com" /></a>
<br />
<br />
Shows Windows 10 RAM and Host-Only network adapter configuration.  <br/>
<a href="https://imgur.com/vo7Lcyt"><img src="https://i.imgur.com/vo7Lcyt.png" title="source: imgur.com" /></a>
<br />
<br />
Event Viewer showing Sysmon logs with Event IDs.
<a href="https://imgur.com/sKQfGCz"><img src="https://i.imgur.com/sKQfGCz.png" title="source: imgur.com" /></a>
<br />
<br />
Splunk showing Windows host logs ingested.
<a href="https://imgur.com/AKwYU3n"><img src="https://i.imgur.com/AKwYU3n.png" title="source: imgur.com" /></a>
<br />
<br />
Terminal showing Kali VM IP address.
<a href="https://imgur.com/VgcHklk"><img src="https://i.imgur.com/VgcHklk.png" title="source: imgur.com" /></a>
<br />
<br />
Terminal displaying port scan results from Kali.
<a href="https://imgur.com/xVVBM4s"><img src="https://i.imgur.com/xVVBM4s.png" title="source: imgur.com" /></a>
  <br />
<br />
Splunk logs detecting port scan activity.
<a href="https://imgur.com/YD9holI"><img src="https://i.imgur.com/YD9holI.png" title="source: imgur.com" /></a>
<br />
<br />
Splunk showing repeated failed login attempts (brute force simulation).
<a href="https://imgur.com/M5kSKLy"><img src="https://i.imgur.com/M5kSKLy.png" title="source: imgur.com" /></a>
<br />
<br />
SPL query detecting repeated failed logins and results table.
<a href="https://imgur.com/hZeS0ZC"><img src="https://i.imgur.com/hZeS0ZC.png" title="source: imgur.com" /></a>
<br />
<br />
Splunk alert setup triggered when suspicious activity detected.
<a href="https://imgur.com/aoLGhxn"><img src="https://i.imgur.com/aoLGhxn.png" title="source: imgur.com" /></a>
<br />
<br />
Full dashboard visualizing failed logins, top attacked accounts, and port scan events.
<a href="https://imgur.com/jzBkgcF"><img src="https://i.imgur.com/jzBkgcF.png" title="source: imgur.com" /></a>
</p>

<h2>7.	Security Principles Demonstrated</h2>

* Centralized log collection and analysis 
* Threat simulation and detection 
* Alert creation and monitoring 
* Dashboard visualization for situational awareness 
* Network isolation and lab segmentation 
* Hands-on SOC analyst skills with Windows and Linux endpoints

