# Overview 

Shared warehouse laptop is dead, inventory counts are stuck
Reported by: Carlos Rodriguez (crodriguez@servicedesk-simulator.com)
Department: Facilities | Location: Floor 1
Contact: x1110

Issue Description:
The shared laptop on the warehouse inventory cart won't power on at all. Everyone on the floor signs into it to scan and log stock. No lights, no fan when we press power, and we already tried a different charger. Counts are due today and the whole team is blocked.

Troubleshooting performed:
- Held the power button several times
- Tried a second charger and a known-good outlet
- Completely dead, no lights, no fan

Business Impact:
Shared Facilities laptop down; stock scanning and inventory logging blocked in the warehouse.

<img width="978" height="590" alt="image" src="https://github.com/user-attachments/assets/b8eca7c9-21af-4b50-a820-883ada894b67" />


## Steps Taken

1. I checked in with Carlos and wanted to make sure the cables are connected properly. 


<img width="400" height="390" alt="image" src="https://github.com/user-attachments/assets/56c21340-ee92-4b29-9da3-a7e57dec2df0" />
<img width="406" height="270" alt="image" src="https://github.com/user-attachments/assets/3c781385-0d12-4a0e-8eb6-78ecc4fe275c" />


2.  I went to Tools --> Computer Deployment and clicked on Manual Domain Enrollment. 

<img width="668" height="644" alt="image" src="https://github.com/user-attachments/assets/a8b3b17b-79ca-435f-a110-69a0452cc263" />



3. Choose the Workstation to deploy in this case: Laptop Deployment. 

<img width="630" height="468" alt="image" src="https://github.com/user-attachments/assets/c5b9443b-1eb0-4ea0-9db2-ee16a2781994" />


4. I connected every cable to the matching port. I connected the USB-C charger to the power input and the Ethernet cable to the Ethernet port. 


<img width="1124" height="588" alt="image" src="https://github.com/user-attachments/assets/0d0be831-a4b2-4895-b75c-97d6cf35fb15" />


5. Selected United States and the Country.

<img width="536" height="640" alt="image" src="https://github.com/user-attachments/assets/a1c043d0-4b53-4089-b95e-eff143d96627" />


6. Selected the right keyboard layout. 
  
 <img width="542" height="682" alt="image" src="https://github.com/user-attachments/assets/38453a04-5916-40b2-aff0-da80685cf80e" />


7. The PC is already on the wired network.

<img width="548" height="526" alt="image" src="https://github.com/user-attachments/assets/4b54d2cb-e928-4b59-bb6f-a63b331b0950" />


8. Agree to the Service Desk Sim License agreement.

<img width="528" height="578" alt="image" src="https://github.com/user-attachments/assets/b76167f4-c804-45eb-8972-9bc261e00c0a" />


9. I need to name the Device. I'll check the Asset Management spreadsheet to assign the next available tag.

<img width="1116" height="626" alt="image" src="https://github.com/user-attachments/assets/83e046e7-1563-4c8c-843f-c12adc3ce0cb" />

I will assign this Laptop as SD2039


10. Set this device as Work or School.


<img width="538" height="326" alt="image" src="https://github.com/user-attachments/assets/16d05702-1fae-4a03-bad8-fb9578134707" />


11. Create a Username and Password. I followed the procedure in the documentation titled Choosing a PC Setup: Device Profiles & Deployment Methods
(Note: I did not screenshot the procedure)

<img width="800" height="712" alt="image" src="https://github.com/user-attachments/assets/f73845d2-2e0f-4339-bc50-26ed240a1a2a" />




12. I unchecked all of the privacy settings for the device. 


<img width="632" height="596" alt="image" src="https://github.com/user-attachments/assets/b6956675-75eb-4e37-9cd4-6779a7047093" />



13. After logging in, I went to System Properties --> Computer Name --> Change --> 

<img width="478" height="570" alt="image" src="https://github.com/user-attachments/assets/82cf3ea5-0aa5-4f26-8a25-dd3c0b069bf7" />


14. I changed the Computer name to SD2039 and changed the domain to  servicedesk-simulator.local



<img width="490" height="402" alt="image" src="https://github.com/user-attachments/assets/c6088b09-d389-45da-900a-d5f4040e890d" />

<img width="436" height="340" alt="image" src="https://github.com/user-attachments/assets/3d850619-e322-42df-88a8-c6a6b79180ae" />



15. <img width="560" height="224" alt="image" src="https://github.com/user-attachments/assets/a3623ec6-5fe9-4eee-a549-073fd8e68a89" />
Restart the Computer.


16. I now need to install the VPN Client, Team Chat, and our Mail software. 

<img width="598" height="572" alt="image" src="https://github.com/user-attachments/assets/52cc1d99-bcbe-483b-835a-e5cb566d479f" />

<img width="584" height="558" alt="image" src="https://github.com/user-attachments/assets/eb156ea6-e182-4695-99de-38d8d3d7dbf1" />

<img width="544" height="562" alt="image" src="https://github.com/user-attachments/assets/d27fd99d-4961-4f9e-a298-f9ed70f30259" />


<img width="470" height="416" alt="image" src="https://github.com/user-attachments/assets/7d61130e-0705-4221-a23e-031484af82d8" />

17. Then, in Asset Management, I changed the status to Ready to Deploy.
<img width="574" height="340" alt="image" src="https://github.com/user-attachments/assets/96e873f9-4254-4f51-b6c5-ffa93f94aaf2" />

18. I then asked Carlos what the address was and created the label to ship the new laptop.

<img width="404" height="312" alt="image" src="https://github.com/user-attachments/assets/1a56f4dd-8a3c-4b51-bb36-482679b4e000" />

<img width="706" height="688" alt="image" src="https://github.com/user-attachments/assets/7361d3bf-e50a-46d3-aeb0-bc292c5bb874" />



## Ticket Notes

- User reported the shared warehouse laptop would not power on: no lights, no fan, and a second charger and outlet did not help.
- Checked with the user that all cables were connected properly; the laptop was still dead, so a replacement was needed.
- Deployed a replacement laptop using computer deployment, then manual domain enrollment with the laptop deployment profile.
- Completed setup (region, keyboard, wired network, work account user profile per the deployment documentation.
- Named the laptop SD2039 from the asset manager spreadsheet and joined it to the servicedesk-simulator.local domain.
- Restarted and installed the VPN client, Teams chat, and mail software.
- Updated SD2039 to be ready to deploy in asset management.
- Received the address from Carlos and created the shipping label.
- Shipped to the user; resolved. 


<img width="496" height="334" alt="image" src="https://github.com/user-attachments/assets/0b0595ff-73cb-4467-a573-8e51517e2167" />




















