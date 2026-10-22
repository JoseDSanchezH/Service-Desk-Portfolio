# Overview 

Customer Support PC is completely dead, agent can't take calls
Reported by: Quinn Adams (qadams@servicedesk-simulator.com)
Department: Customer Support | Location: Floor 1
Contact: x2280

Issue Description:
My desktop on the Customer Support floor won't turn on at all this morning. No lights, no fan, nothing when I press power. I have a full queue of calls waiting and I can't do anything until I have a working machine.

Troubleshooting performed by user:
- Pressed the power button several times
- Checked the wall outlet with another device (it works)
- Completely dead, no lights, no fan, no beep

Business Impact:
Customer Support agent offline; calls queueing with no one to take them.

<img width="1542" height="454" alt="image" src="https://github.com/user-attachments/assets/abcd03a5-5c46-475d-a1d0-3d9754ce9038" />


# Steps Taken 
1. Determined that the desktop is not repairable remotely and needs to be replaced.

2. I would need to deploy a new desktop and would have to set up the imaging server task sequence and make sure that I follow the correct procedural steps given by the company. 

<img width="1518" height="306" alt="image" src="https://github.com/user-attachments/assets/a0c99bb5-d6fb-4dca-9de1-11843bbb68f1" />

<img width="502" height="530" alt="Screenshot 2026-10-20 101227" src="https://github.com/user-attachments/assets/e0e678a1-b714-45e3-b4f0-14bb00758766" />


3. I started operating system deployment via the imaging server and followed the procedure. I gave it a name and the value, which would be the next value opened in our Asset management list. In this case, it was "SD2036".  

<img width="1124" height="776" alt="Screenshot 2026-10-20 101029" src="https://github.com/user-attachments/assets/7f6c67cd-2773-4d50-86d8-c035838449ec" />

 
<img width="1884" height="824" alt="Imaging Server 2026-10-20 100521" src="https://github.com/user-attachments/assets/f2af720a-41ab-45f4-9c4d-7c430f14ae24" />

<img width="984" height="736" alt="Added Value SD2036 2026-10-20 101136" src="https://github.com/user-attachments/assets/8cb73966-56ee-4ffc-83f6-d261f3de013d" />


4. After setting up the configurations, I went to the computer name settings and changed the domain to "servicedesk0simulator.local"

<img width="1130" height="790" alt="Screenshot 2026-10-20 101232" src="https://github.com/user-attachments/assets/b78ec46a-7009-45f4-91fd-e26e9d107fb8" />

<img width="684" height="550" alt="Screenshot 2026-10-20 103150" src="https://github.com/user-attachments/assets/8fe52e27-60d1-4b03-a270-340320e16060" />

5. After connecting it to our domain, I was able to start the shipping process.

<img width="1290" height="716" alt="Screenshot 2026-10-20 105630" src="https://github.com/user-attachments/assets/e6f6b060-45a4-4213-a667-6240ae506209" />



# Ticket Notes 
User reported the desktop was completely unresponsive: no lights, no fan noise, no beep codes.
User tested a different power outlet; same result. Device still completely dead.
Determined the desktop is not repairable remotely and needs to be replaced.
Deployed a new desktop using PXE boot and an imaging server task sequence.
Configured the new desktop with the correct credentials for the user.
Used the asset management system to label the new desktop SD 2036 and assign it to the correct employee, Quinn Adams.
Shipped the new desktop to Quinn Adams.


<img width="840" height="140" alt="image" src="https://github.com/user-attachments/assets/89f2dac5-ab20-4c70-9a6a-c376198cc372" />













