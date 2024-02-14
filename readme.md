### Q: Printer is not working. Printer job queue is filling up but the printer itself is not actually receiving the print job itself. 
- A: Restart the Printer Spooler service in services.msc. 

### Q: If you have a computer that is infected with malware on your domain, what is the first step you should take?
- A: Immediately remove the connection to the rest of the domain and Internet. Contain the infection as soon as possible and then follow company policy to assess. 

### Q: What troubleshooting steps will you take if someone is having issues with their docking station. The mouse and keyboard is not working and nor is the monitor but the laptop is functioning totally fine.
- Verify power cable is plugged into the docking station. Verify that the laptop is properly seated in the docking station. Double check that the monitor is sharing to external monitors. Verify drivers are up-to-date.

### Q: How could you verify that a computer is on a domain by looking at the sign in window?
- A: There will be the "Other User" option.

### Q: If you want to log into locally on the machine instead of the domain, how would you achieve this?
- A: You would use .\\UserName. 

### Q: If a user was no longer on a domain, how would you add them back?
- A: Log in as a local account and readd them to the domain by changing the DNS to the IP address of the domain server.

### Q: How do you add a new local user?
- A: Type "Other Users" in Windows search or open cmd and type `net user username password /add`

### Q: I am receiving errors or failure to load pages when trying to visit other web pages. I am connected to the internet and everything was working fine.
- A: First, try to ping the website or the IP address of the website. If this is successful, it is likely a DNS problem. Try releasing and flushing DNS. If this does not work, checking `Internet Options`, `LAN settings`, and check `Proxy server` status. If there is a proxy configured, try to uncheck it and try the web page again.

### Q: User is trying to connect via VPN and get this error message: "DNS resolution has failed. Please try again later." Why would they get this error message?
- A: Occurs when your profile is corrupted on a certificate level. You have to remove and reinstall the certificate. This can also happen if your Internet, such as Wi-Fi is not working. You could try to restart the computer. You could also try release and renew the IP address.

### Q: The user cannot use the internet at all and the date and time say it's 1995. What is the problem?
- A: The user needs a new CMOS battery. 

### Q: Excel keeps crashing. How can you help this user?
- A: Try restarting the computer. If this doesn't work, put Excel into safe mode by running `excel.exe /safe` . This will disable add-ins. If this does not work, try reinstalling Excel. If this doesn't work, have user open task manager and go to performance and view hardware to see if memory or CPU is crashing. 

### Q: A user is trying to open a file, but there is an error message that says "Cannot open file because it is open by another user."
- A: You could copy the file and paste it to create two versions of the file. 

