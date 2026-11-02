# Overview 

VPN disconnected and won't reconnect
Reported by: Tyler Grant (tgrant@servicedesk-simulator.com)
Department: Sales | Location: Remote (Working from home)
Contact: x5570

Issue Description:
VPN disconnected and won't reconnect

Business Impact:
Working remotely and lost VPN. Cannot access any internal resources.

<img width="1670" height="442" alt="image" src="https://github.com/user-attachments/assets/fec980c9-fa1f-41e0-b588-b124b8a3c0ee" />


## Steps Taken 


1. I want to know if he has a stable internet connection; I will ask him if he can get to Google.com. If he can, then I will remote in and check if he is getting any error code. 

<img width="394" height="456" alt="image" src="https://github.com/user-attachments/assets/4f4a2a0a-d2c5-4f22-850a-bbe14fa82512" />


<img width="398" height="178" alt="image" src="https://github.com/user-attachments/assets/6a3298db-5bb9-46fe-b358-4104fce5f437" />


2. Once I remoted in, I checked to see what the VPN said.

<img width="544" height="534" alt="image" src="https://github.com/user-attachments/assets/204fcb2e-bc59-4843-90e5-8c0bfe75a7c8" />

"VPN connection failed — stale DNS entries are blocking the tunnel. Open the Terminal and run "ipconfig /flushdns" to clear the DNS cache first."


3. I then went to Terminal and entered "ipconfig /flushdns".

<img width="722" height="566" alt="image" src="https://github.com/user-attachments/assets/b5071fca-1f3d-461f-93d0-3ef7fd5c755f" />


4. The VPN commanded me to restart the computer. 

<img width="520" height="518" alt="image" src="https://github.com/user-attachments/assets/665908fe-d3e1-4c28-a7a3-ced96da5dc5a" />


5.  After restarting, the VPN was able to connect to the corporate network.

<img width="512" height="520" alt="image" src="https://github.com/user-attachments/assets/3e6df521-4832-4b84-97ce-67a4fea1d78c" />



## Ticket Notes

- Asked the user if he has an internet connection; asked if they can go to google.com
- After confirming internet, I remoted in and checked the VPN Application.
- Given an error message: "VPN connection failed — stale DNS entries are blocking the tunnel. Open the Terminal and run "ipconfig /flushdns" to clear the DNS cache first."
- Went to Terminal and entered "ipconfig /flushdns" to clear the DNS cache.
- Restarted the computer and then connected to the VPN successfully. 


<img width="500" height="338" alt="image" src="https://github.com/user-attachments/assets/34a2e811-c732-4312-ae3c-06f14e20b0de" />










































