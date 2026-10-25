## Overview 

VPN disconnected and won't reconnect

Reported by: Derek Chang (dchang@servicedesk-simulator.com)
Department: Marketing | Location: Remote (Working from home)
Contact: x4305

Issue Description:
VPN disconnected and won't reconnect

Business Impact:
Working remotely and lost VPN. Cannot access any internal resources.


<img width="800" height="362" alt="image" src="https://github.com/user-attachments/assets/c7b09a02-a850-4702-8f29-1e3974b96fdf" />



## Steps Taken

1. I checked in with Derek to see if he is working remotely.


<img width="446" height="364" alt="image" src="https://github.com/user-attachments/assets/25333980-8ef9-44fa-8f2b-06977b3b3b78" />



2. I then remoted into his computer and wanted to see for myself on the VPN application.


<img width="506" height="502" alt="image" src="https://github.com/user-attachments/assets/c008d9af-aa87-43b6-987b-4a0ad5c20eac" />

3. I then went to the terminal and ran "ipconfig /flushdns"  to clear stale DNS entries

This command clears the DNS cache, so the computer requests a fresh one. 

<img width="490" height="282" alt="image" src="https://github.com/user-attachments/assets/d4161ab8-4ed9-4040-9a4a-fca3331a9671" />

4. I then restarted the computer and tested to see if the VPN would connect.

<img width="732" height="600" alt="image" src="https://github.com/user-attachments/assets/5ebe8c20-fff7-4718-a31b-d03a44dd8a08" />


<img width="562" height="530" alt="image" src="https://github.com/user-attachments/assets/5bb05e53-0b0a-4dec-a8f4-4c59031b5b0a" />

## Ticket Notes

- Confirmed with Derek that he is working remotely.
- Remoted into his computer and checked the VPN application.
- Ran "ipconfig/flushdns" in the terminal to clear stale DNS entries.
- VPN connected


<img width="500" height="336" alt="image" src="https://github.com/user-attachments/assets/939cb3e3-e73e-4142-8ec1-be031280f392" />




















































