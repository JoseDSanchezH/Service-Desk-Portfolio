# Overview 

Reported by: Sarah Mitchell (smitchell@servicedesk-simulator.com)
Department: Marketing | Location: Remote (Working from home)
Contact: x4892
Issue Description:
I can't get to my files on the Marketing shared drive today. I keep getting "The network path was not found" when I try to open it. I'm working from home today. My internet and email both work fine.

Troubleshooting performed by user:
- Restarted my computer (no change)
- Internet and email work normally
- The mapped drives say disconnected

Business Impact:
Unable to access marketing campaign files. Deadline for Q1 campaign materials is EOD tomorrow.
<img width="978" height="596" alt="image" src="https://github.com/user-attachments/assets/66ff9a58-f1e5-49ee-8de2-b106c23952ca" />


## Steps Taken

1. I needed to gather some information about file paths for shared files employees use and where to find them. I was able to find this information in the Server Documentation that the company has.

<img width="1474" height="176" alt="image" src="https://github.com/user-attachments/assets/2c22144f-becf-4412-a6aa-b700ae54b00f" />



2. I then remote desktop into Sarah Mitchell laptop and looked at File Explorer to see what files she has access to. I noticed that Local Disk was the only file.

<img width="178" height="230" alt="image" src="https://github.com/user-attachments/assets/7b5537be-dd1f-49a6-a69b-3a78769fec63" />


3. I then connected to the VPN since the data sits in our database. Since she is a remote employee or is working from home, she wouldn't have access to this sensitive data unless she is connected through the VPN.

 <img width="542" height="536" alt="image" src="https://github.com/user-attachments/assets/5dbf4b39-2b05-4acf-8898-923cad78986f" />

 
 
4. Then I went to File Explorer and noticed the Cloud Drive and D: Marketing file were available. 

<img width="816" height="512" alt="image" src="https://github.com/user-attachments/assets/9bc86641-d25c-4cd6-99d9-be050f95c8f3" />


<img width="418" height="548" alt="image" src="https://github.com/user-attachments/assets/a0697221-8bd9-48d9-b5ec-bbd8f1f908db" />


## Ticket Notes

- Found the shared drive paths in the server documentation.
- Remoted into Sarah Mitchell's laptop. File Explorer showed only Local Disk.
- Sarah was working remotely without VPN, which is needed to reach the company's data.
- Connected the VPN and cloud drive, and the shared file appeared.

<img width="510" height="378" alt="image" src="https://github.com/user-attachments/assets/72ff5d6a-f473-4ff2-b9e5-23009596449a" />



















 































