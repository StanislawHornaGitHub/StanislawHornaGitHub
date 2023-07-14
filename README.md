![image](/Banner.png)
# Hi there, I'm Stanislaw 👋
- 🔭 I’m currently working on Universal **PowerShell GUI** to run any script
- 🌱 I’m currently learning **Bash** and **Swift**
- 🤔 I’m looking for help with some good tutorials for **Swift code development**
- 💬 Ask me about **PowerShell Automations** or **LAN infrastructures**

## Work experience
I am **certified ICT Technician**, who loves **PowerShell scripts** development.
Developing automation for repetetive tasks is really usefull and pleasant for me.
Sometimes I event can not sleep as I am still thinking about the solution.

I worked for 2+ years for **Ministry of Justice UK** as a Nexthink Administrator building **Nexthink Remote Actions** and automated processes for generating reports based on Nexthink and other tools data.

The most challenging always was bulding scripts to generate reports, where I used **PowerShell Background Jobs and Runspaces** to find the best balance between operation time and the resource consumption.
I am also really keen on to **solve algorithmic problems** to deliver same result without additional resources use.

## Personal time
I am a part-time student of Engineer's degree Information Technology at the Lodz University of Technology.

What is more interesting, IT is also my hobby. I have my pretty complex **HomeLAB**, where I am able to test any ideas which came to my mind.
Basically it consists of 2 servers:
- the first one is a pretty standard PC which runs Windows Server Core with VM under **Hyper-V**. 
- the second one is an IBM server with 16 cores and 192GB of RAM memory, where I am able to create virtualized environments for testing purposes.

As the **IBM** is more like a playground, so I think that more interesting part is the one which is running constantly.
The fundament of whole infrastructure is my **Cisco C3650**, where I have separate VLANs for physical devices and separate one for VMs,
according to the needs I am also creating additional VLANs, especially when I am testing something related to routing software mostly based on FreeBSD.

My main Router is **pfSense** running on Hyper-V VM which has Failover Loadbalancing. It is also responsible for VPN connections to my home network and all Firewall, DNS filtering. I really like pfSense for posibilities in DHCP and DNS server configuration.

Another VM which is constantly running is my **Ubuntu Server** responsible for Zabbix server, Guacamole Server, TrueNAS Core. 

I use **Zabbix** for monitoring all endpoints including network devices to have all parameters such like temperatures, errors, bandwidths under control. It also allows me to build maps which represent different layers of my network to be able to identify the root cause of an issue easily.

**Guacamole** is really usefull, because I can connect start any RDP connection or SSH connection from one place, including devices like tablets, phones without need to install any external applications.

**TrueNAS** is just a small storage to keep some available immediately ISOs, system images and backups. It is also configured to sync some data with OneDrive storage to be compliant with 3-2-1 backup rule:
 - 3 different coppy
 - 2 different storage types (TrueNAS & IBM)
 - 1 copy offsite (OneDrive)

**All those services are integrated with Active Directory**, so everywhere I can access using AD account with approppriate groups added.

The Domain Controller is the last VM running on the first server.
Moreover I also have a sync with **Azure Active Directory** and **Azure Application Proxy** configured, to be able to access some services directly from the browser without the VPN connection needed, using AAD account for Authentication and Authorization.

To minimize RAM memory consumtion I installed **Windows 2019 Standard Core** with Features on Demand to be able to run standard MMC, however some configs still requires running it from PowerShell console even on Full desktop experience eddition, such like deep configuration of VM switches.

## My GitHub
I used to have a git only as a version control for PowerShell scripts, but I would like to start with some Open-source projects and build something which may be usefull for other users. 

Unfortunatelly **not every repository can be public** (work & studies stuff), but I though that it would be a good idea to push almost all my programs to have the backup of them and be able to generate the statistics what I was doing since I have started my IT studies.

![Top Langs](https://github-readme-stats-nine-ivory-60.vercel.app//api/top-langs/?username=StanislawHornaGitHub&langs_count=8&custom_title=Top%20Used%20%28incl.%20private%20repos%29)
