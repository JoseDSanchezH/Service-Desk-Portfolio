# Overview 

Cannot connect to Floor 2 printer

Reported by: Chris Nguyen (cnguyen@servicedesk-simulator.com)
Department: Engineering | Location: Floor 2
Contact: x6150
Printer: Floor2-Printer-B

Issue Description:
I can't print to the Floor 2 printer from my PC anymore. Every job I send just fails saying "printer offline." My coworkers can still print to it fine, so it seems like it's just my computer. It started after the maintenance last week.

Troubleshooting performed:
- Print jobs fail with "printer offline"
- Coworkers on the same printer are unaffected
- Started after the maintenance

Business Impact:
I cannot print to the Floor 2 printer from my workstation - blocking the reports I need.


<img width="1026" height="612" alt="image" src="https://github.com/user-attachments/assets/3422a02f-f054-4468-be0c-68f0b2bdc662" />


## Steps Taken 

1. If no one else is having trouble, this could be a problem with his own device. I will remote into his computer and see if it needs an update and go on from there.

<img width="942" height="656" alt="image" src="https://github.com/user-attachments/assets/d8de565a-49e8-4a4a-99a7-2c3605a9b844" />

<img width="924" height="548" alt="image" src="https://github.com/user-attachments/assets/75fa5055-4fe9-45e3-86f4-57d8357c01c0" />


2. I then checked the devices in his settings and noticed that it says offline with the IP address.

<img width="776" height="428" alt="image" src="https://github.com/user-attachments/assets/0d110605-be56-422a-8832-129f88d939d4" />


<img width="474" height="528" alt="image" src="https://github.com/user-attachments/assets/b9ec2eb2-9e53-4c73-8342-5968bd66c244" />



3. I removed it from the list and tried scanning again to see if the printer in the office would be picked up.

Seemed like it did not, so I will add it to the computer by clicking "PRINTER THAT I WANT ISN'T LISTED."

<img width="816" height="252" alt="image" src="https://github.com/user-attachments/assets/0e6e6b1e-0f3f-47d0-8a98-d8c515e98bb9" />



4. I would need to check the company's documentation about our devices and what the IP address is.  

<img width="773" height="452" alt="image" src="https://github.com/user-attachments/assets/40ad278b-5abc-4f1e-9a08-0ce5001bd4e4" />

Given the information, I would need to search for the IP Address: 10.0.2.51


5. I have successfully connected the printer to the computer. I will now run a test and ask Chris if he can print a test page to confirm. 

<img width="546" height="256" alt="image" src="https://github.com/user-attachments/assets/87250139-842d-419f-a14d-9eeafb6faa09" />


6. <img width="546" height="314" alt="image" src="https://github.com/user-attachments/assets/c69f3a10-2871-4e5a-9dd7-a18f94ada099" />



## Ticket Notes

- Checked that no one else was affected.
- Remoted into Chris computer and checked for updates.
- Checked Printers and Scanners in his settings. The printer showed offline with its IP Address.
- Removed the offline printer and scanned again; no printer was found.
- Checked company device documentation.
- Added the printer manually and entered the IP Address.
- Printer connected successfully.
- Tested with a test page.

<img width="504" height="336" alt="image" src="https://github.com/user-attachments/assets/97f62597-ca74-4cd2-99ef-d2375468a929" />




























