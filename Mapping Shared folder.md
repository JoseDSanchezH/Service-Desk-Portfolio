# Overview 

Need access to shared department folder
Reported by: Michael Brown (mbrown@servicedesk-simulator.com)
Department: Engineering | Location: Floor 3
Contact: x6270

Issue Description:
I just transferred to this department and the team's shared folder isn't on my computer like it is for everyone else. When I try the path, I get "network path not found." I need it to do my daily work.

Troubleshooting performed:
- My manager said I should have access
- The drive isn't mapped on my PC

Business Impact:
Cannot access department documentation and templates needed for daily work.

<img width="1026" height="566" alt="image" src="https://github.com/user-attachments/assets/a5d85d08-7e0f-4f97-9851-185d113028c9" />


## Steps Taken 

1. I went to the documentation station. I could find answers to certain questions, for instance, access controls, configuration details, playbooks, etc. I looked for Standard Shares files and which file paths users should use to get to the department files.

\\FILESERV01\departments\Engineering - Engineering team files

<img width="584" height="398" alt="image" src="https://github.com/user-attachments/assets/8db04605-3fee-45fe-ae57-46c8e8263cbb" />


2. I remoted into his computer, I went to File Explorer, and clicked on "This PC"; then on the right-hand side I clicked on 3 dots (ellipsis) and clicked on Map Network Drive.

Drive Letter: D: 
Folder: \\FILESERV01\departments\Engineering - Engineering team files



<img width="496" height="310" alt="image" src="https://github.com/user-attachments/assets/3f2c346e-263d-497c-ba90-edf8032ede49" />




3. I can see the Engineering Department Drive file on his drive, which he now has access to.  

<img width="863" height="532" alt="image" src="https://github.com/user-attachments/assets/642ac344-ab0d-44f9-a8f6-9d89d233472d" />


## Ticket Notes 

- User transferred departments and could not open the Engineering shared folder.
- Looked up the standard Engineering share path in the company documentation: \\FILESERV01\departments\Engineering
- Remoted into his computer, opened This PC in File Explorer, and chose Map Network Drive.
- Mapped drive D: to the Engineering share.
- Confirmed the Engineering Department Drive now appears and opens. 



<img width="492" height="310" alt="image" src="https://github.com/user-attachments/assets/b83e2655-9a50-4a4c-9ce8-0e3b81bbacf6" />


































