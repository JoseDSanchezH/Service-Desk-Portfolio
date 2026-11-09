# Overview

Unable to log in to PCs - cannot access anything across the office

Reported by: Tom Wilson (twilson@servicedesk-simulator.com)
Department: Engineering | Location: Floor 2
Contact: x6001

Issue Description:
A bunch of us can't log into our computers this morning. The error says something about "no logon servers available." A few people who were already logged in are saying they can't open anything from the network either.

Troubleshooting performed:
- Most of the office is affected
- A few people say they can still log in fine

Business Impact:
Approximately 40 users cannot start their workday. Morning standup meetings being missed.

<img width="1036" height="578" alt="image" src="https://github.com/user-attachments/assets/63536c48-9bb2-452e-a840-14f41350891e" />

## Steps Taken 

1. Since multiple people are having issues, I went to the Server room and looked at the Domain Controller Server A. The CPU and Memory were high, and the status was degraded. I decided to reboot the domain controller. 

<img width="1108" height="480" alt="image" src="https://github.com/user-attachments/assets/5bc7a9b1-647e-4b08-9aa4-436d53d5f9ef" />


2. Looks like everyone is back online.

<img width="836" height="486" alt="image" src="https://github.com/user-attachments/assets/bb2417a1-4422-46b1-b3f5-a60405278143" />

<img width="390" height="136" alt="image" src="https://github.com/user-attachments/assets/5f53d8a7-c01d-4d9c-90cd-77dbd083b48c" />


## Ticket Notes

- Many users were affected; checked the servers in the server room.
- Found a Domain Controller in Server Room A with high CPU and memory usage and degraded status.
- Rebooted the Domain Controller.
- Confirmed users are back online and can log in. 

<img width="496" height="340" alt="image" src="https://github.com/user-attachments/assets/e21af22c-beb7-4c18-8d9b-94b6ab61c544" />



















































































