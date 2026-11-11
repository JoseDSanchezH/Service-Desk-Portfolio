# Overview 


Print jobs just sit in the queue and never print
Reported by: Nina Patel (npatel@servicedesk-simulator.com)
Department: Engineering | Location: Floor 1
Contact: x6195

Issue Description:
Everything I send to the printer just sits in the queue and never comes out. The printer is still in my list and I can pick it like normal, and the printer itself says Ready on its screen. Canceling a job does not clear it, it just sits there saying deleting. A colleague printed to the same printer earlier with no problem.

Troubleshooting performed:
- Restarted my computer, the queue came back with the same jobs in it
- Canceled the jobs, they will not clear
- The printer is on and says Ready

Business Impact:
Cannot print anything at all from this machine.

<img width="750" height="492" alt="image" src="https://github.com/user-attachments/assets/8309a04d-4a01-4fb4-adb0-6241dc921cc4" />


## Steps Taken

1. I asked Nina when the last time it was working. I then remoted into her computer and realized there was no printer connected. I then referred to the company documentation to find the IP Address of the Printer. I was able to connect and asked Nina if she could run a test page, but nothing happened. 

<img width="398" height="614" alt="image" src="https://github.com/user-attachments/assets/9b770282-b0c2-46c7-abbf-c52439a962b1" />

<img width="734" height="270" alt="Screenshot 2026-11-11 104259" src="https://github.com/user-attachments/assets/bdba95b8-098e-4bf1-a689-c9150b696efa" />


2. I then thought maybe there was a driver I needed to install from the manufacturer, so I searched for the model number and downloaded the driver onto her computer. Then asked her if she could run a print test, and she still had the same issue.

<img width="570" height="280" alt="Screenshot 2026-11-11 104411" src="https://github.com/user-attachments/assets/218b5d18-c625-40b1-846a-063d4c32f146" />


<img width="408" height="240" alt="image" src="https://github.com/user-attachments/assets/d923df54-425a-4e52-8397-a69585b66d99" />

3. Since that didn't work, I went to Computer Management --> Services and Applications --> Searched for Print Spooler in Services and realized that the status was stopped. I right-clicked on Print Spooler and selected Start, then entered my domain credentials.

<img width="942" height="614" alt="image" src="https://github.com/user-attachments/assets/20f6889a-5cfd-4184-a091-d60229a8ef1b" />

<img width="796" height="250" alt="image" src="https://github.com/user-attachments/assets/ca7ea9f9-50fe-483e-aa74-15e98b12f677" />


4. Then, I asked Nina to run a test page again.
 

<img width="398" height="198" alt="image" src="https://github.com/user-attachments/assets/779a6c66-0a87-4d7e-ad7a-031c66822a61" />

## Ticket Notes

- User's print jobs are at the printer and in the queue. Other users could print to the same printer.
- Asked the user when it last worked, then remoted in and found no printer connected.
- Found the printer's IP address in the company's documentation, and the test page did not print.
- Downloaded and installed the manufacturer's driver, and the test page still did not print.
- Opened Computer Management, then Services, and found the Print Spooler stopped.
- Started the Print Spooler.
- Asked the user to print a test page and confirmed it's now working.


<img width="622" height="386" alt="image" src="https://github.com/user-attachments/assets/4e893503-dc0f-45c2-9385-7b644c4f63c1" />



















































