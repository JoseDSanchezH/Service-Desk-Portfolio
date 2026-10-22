# Overview 

VPN disconnected and won't reconnect
Reported by: Andrew Kim (akim@servicedesk-simulator.com)
Department: Sales | Location: Remote (Working from home)
Contact: x5630

Issue Description:
VPN disconnected and won't reconnect

Business Impact:
Working remotely and lost VPN. Cannot access any internal resources.

## Steps Taken


1. I was advised by IT professionals that whenever you promote an employee's computer, you always want to check if their system is updated, so I'm updating just to be sure. 

<img width="516" height="508" alt="image" src="https://github.com/user-attachments/assets/181886b6-636e-4829-b5f5-2bd8f9d9b651" />


2. I wanted to see what type of message I'm getting from the VPN that's not allowing the VPN to connect, and it says to open the terminal and run "ipconfig /flushdns" to clear the DNS cache first.

<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/92675cf6-5c85-4fb7-809f-62834bba87ca" />

3. I opened the terminal, and I ran **"ipconfig /flushdns"**. It successfully flushed the DNS resolver cache.

<img width="526" height="284" alt="image" src="https://github.com/user-attachments/assets/2f61e88b-f8b4-4159-bd23-6024e2751cd2" />

4. Now it says the terminal stack needs a fresh start. Restart the computer & back in before reconnecting to the VPN. Let me do that. 

<img width="550" height="558" alt="image" src="https://github.com/user-attachments/assets/5b4eb670-37b7-40f2-9954-aa7ac6c64a00" />

5. After restarting the computer, I went back to the VPN client GUI and connected to the VPN. It's now routing traffic through the corporate network.

<img width="570" height="582" alt="image" src="https://github.com/user-attachments/assets/b9ec6d37-9b86-441d-b3f5-f33a68193d52" />

## Ticket Notes 

- Check the computer for system updates to rule them out.
- Open the VPN client and read the error. It said to run "ipconfig /flushdns" first.
- Ran "ipconfig /flushdns" in the terminal. It flushed the DNS resolver cache.
- The VPN then asked for a restart, so I restarted the computer.
- Reconnected through the VPN client. It connected and is routing traffic through the corporate network.

<img width="534" height="378" alt="image" src="https://github.com/user-attachments/assets/1dbc0439-4478-4da2-a31c-8d334b4d212f" />








