Let's say that you handle the IT systems administration for your company. There's a server inside of your organization that checks how often client machines access it. If a client machine hasn't accessed the server in three months, the server won't allow the client machine to access its resources anymore. What can you set to make sure that your client machines and the server times are in sync?

FTP

->NTP
Correct
You nailed it! NTP is commonly used in organizations to keep time synchronized across machines in a fleet.

Proxy

Intranet




Which of the following options allow you to access a computer remotely? Check all that apply.

NTP

->SSH
Correct
Great job! There are lots of ways to access a computer remotely.


Server

->VPN
Correct
Great job! There are lots of ways to access a computer remotely.





When you make a DNS query, where does your computer first check to find an IP address to name mapping?

ISP DNS servers

->Your local machine
Correct
Awesome! When you do a DNS query, your computer first checks locally, in a file like /etc/hosts, to find local DNS mappings.

Root servers

Top-level domains




A network technician sets up an internal DNS server for his local network. When he types in a URL, which is checked first?

External public DNS servers

->Local hosts file
Correct
Woohoo! The local hosts files are always checked first.

External ISP DNS servers

Local DNS servers




A website is inaccesible via its URL. You've pinged the site and see no problem there. What is the next troubleshooting step?

Ping localhost

Turn the device off and on again

Access host file and check for inconsistencies

->Use nslookup in the terminal to rule out DNS issues
Correct
Right on! We can rule out if DNS is an issue by verifying that the hostname points to a nameserver. If we copy the IP address of the results and paste it into the web browser, it should resolve the website name if the DNS is working.





What does PXE Boot stand for?

Post Boot Extraction

->Pre Boot Execution
Correct
Right on! PXE Boot stands for Pre Boot Execution. This allows you to boot into software that’s available over the network.

Past Boot Examination

Pay-to-Boot Extortion