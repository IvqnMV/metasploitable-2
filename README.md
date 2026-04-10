# metasploitable-2
Virtual machine Metasploitable2 
A test environment provides a secure place to perform penetration testing and security research. For your test environment, you need a Metasploit instance that can access a vulnerable target. The following sections describe the requirements and instructions for setting up a vulnerable target:

### Metasploitable is an intentionally vulnerable Linux virtual machine. 
This VM can be used to conduct security training, test security tools, and practice common penetration testing techniques.

####The default login and password is msfadmin:msfadmin.

Never expose this VM to an untrusted network (use NAT or Host-only mode if you have any questions what that means).

###Identifying Metasploitable 2’s IP Address

After you log in to Metasploitable 2, you can identify the IP address that has been assigned to the virtual machine. Just enter ifconfig at the prompt to see the details for the virtual machine.

msfadmin@metasploitable:~$ ifconfig

The command will return the configuration for eth0. You’ll need to take note of the inet address. This will be the address you’ll use for testing purposes.

### for more information: https://docs.rapid7.com/metasploit/metasploitable-2-exploitability-guide/
