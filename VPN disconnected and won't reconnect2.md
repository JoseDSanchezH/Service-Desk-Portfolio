# Overview 

VPN disconnected and won't reconnect

Reported by: Beth Collins (bcollins@servicedesk-simulator.com)
Department: Sales | Location: Remote (Working from home)
Contact: x5520

Issue Description:
VPN disconnected and won't reconnect

Business Impact:
Working remotely and lost VPN. Cannot access any internal resources.

<img width="746" height="344" alt="image" src="https://github.com/user-attachments/assets/1958de3c-686d-4323-b948-00320e09013b" />

# Steps Taken 

1. I asked Beth if they were working from home, if they had internet to go to a website (Google.com), and if they saw an error code. I then remoted in.

<img width="392" height="792" alt="image" src="https://github.com/user-attachments/assets/c3e5c2e8-814b-4653-ae43-2980cd809747" />

<img width="412" height="638" alt="image" src="https://github.com/user-attachments/assets/5dcf867e-dfb1-475e-bf03-ee266d3bea5d" />

2. Once I remoted into her computer I opened VPN Client and clieck on Connect and was given an error code. 
"VPN connection failed — stale DNS entries are blocking the tunnel. Open the Terminal and run "ipconfig /flushdns" to clear the DNS cache first"


<img width="534" height="516" alt="image" src="https://github.com/user-attachments/assets/1d511390-0def-4fc6-8580-1bc6c8ab449c" />



3. I opened Terminal and ran "ipconfig /flushdns"

<img width="704" height="368" alt="image" src="https://github.com/user-attachments/assets/2a8a2635-9ed4-4f3b-b325-2eb1eecf2600" />


4. I restarted her computer and tested her VPN connection.  


<img width="524" height="518" alt="image" src="https://github.com/user-attachments/assets/a8a75e9c-f4d9-4ddc-b312-2a5cc1e5fc19" />



## Ticket Notes

- Ask the user if they were working from home, if they can reach a website (Google.com), and if they saw an error code.
- Remoted into her computer and opened the VPN Client. Clicking on Connect gave an error message: stale DNS entries blocking the tunnel, with a prompt to run "ipconfig/flushdns"
- Ran "ipconfig/flushdns" and restarted the computer.
- Tested the VPN, and it connected. 


<img width="504" height="336" alt="image" src="https://github.com/user-attachments/assets/5bb1445e-93c2-4963-96a3-0bc4d6e5c156" />


















