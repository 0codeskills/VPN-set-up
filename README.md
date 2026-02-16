# VPN set up

## Objective

The  requirements for this project are two linux Virtual Machines and OpenVPN software. One of the VMs will be set up as VPN server and another one as VPN client, which will allow to test the VPN connectivity and configuration.

### Skills Learned

- Installation of SpiderFoot tool with use of terminal on Linux based VM.
- Use of SpiderFoot to complete threat intelligence data mapping.
- Ability to read the results of scan.
- Enhanced knowledge of OSINT automation tool.

### Tools Used

- Kali Linux virtual machine as controlled environment.
- Linux terminal to intall and run cybersecurity tools.
- SpiderFoot to map threat intelligence data.

## Steps

1. I went to google.com and searched for SpiderFoot. Second result took me to a github reposytory of <a href="https://github.com/smicallef/spiderfoot">SpiderFoot</a>.
2. I have downloaded the zip file to the Kali Linux VM.



3. I have extracted the files from the zip file in the /Downloads directory.


4. I have initiated the SpiderFoot tool. It is very important to use the correct options with the command.



5. I have opened the provided URL in web browser, selected 'New Scan' from the menu, set up 'Scan Name' and 'Scan Target' and started scan. We can select from range of different target types i.e. domain name, IPv4 address, IPv6 address, hostname, subnet, e-mail address, phone number, human name, username, etc. 



6. Scan run for couple of minutes before returning the results.



In conclusion email in question had total of 15 hits across multiple sites with one distinct correlation showing that email might have been hacked on two different application domains.


