
# INTRODUCTION TO SAMBA

Samba is open source software that implements the Server Message Block (SMB) protocol. Many operating systems, including Linux, Microsoft Windows, UNIX use the SMB protocol for client-server networking. Samba enables Linux / Unix machines to communicate with Windows machines in a network. 


• Serve directory trees and printers to Linux, UNIX, and Windows clients.   
• Assist in network browsing (with or without NetBIOS).    
• Authenticate Windows domain logins    
• Provide Windows Internet Name Service (WINS) name server resolution.


# SETUP


Step 1: Install Samba.
Step 2: Create a Shared Directory.
Step 3: Configure Samba's Global Options. Browsing/Identification. Networking. Debugging. ...
Step 4: Set Up a User Account.
Step 5: Configure Samba Share Directory Settings.
Step 6: Update the Firewall Rules.
Step 7: Connect to the Shared Directory.
    

`sudo apt install samba –y`    
`sudo systemctl status smbd`    
`mkdir /home/std/sharingFolder`    
`chmod 777 /home/std/sharingFolder`    
`sudo useradd user1`    
`Sudo ambpasswd –a user`    
`Sudo nano /etc/samba/smb.conf`     

# Learnings : 
- Introduction to SAMBA.
- Installation and SAMBA setup.
- Features.
