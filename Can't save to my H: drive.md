# Overview 

Can't save to my H: drive - says there's no space
Reported by: Tom Wilson (twilson@servicedesk-simulator.com)
Department: Engineering | Location: Floor 2
Contact: x6001

Issue Description:
Every time I try to save something to my H: drive I get a message saying there isn't enough space, and the file doesn't save. I can still open everything on it. Saving to my Desktop works, and my laptop has loads of space left, so I don't understand how H: can be full. Nobody else on my team has mentioned it.

Troubleshooting performed:
- Restarted my laptop, no change
- Deleted some old files from my Downloads folder, still the same message
- Saving to the Desktop works fine

Business Impact:
I keep all my working files on H: and I can't save changes to any of them. For now I'm saving copies to my Desktop.

<img width="744" height="502" alt="image" src="https://github.com/user-attachments/assets/527d4f2b-eeea-49a0-a6f8-2c449318f927" />


# Steps Taken

1. I let Tom know that I will remote into his computer since this seems to be on his device only.


<img width="420" height="392" alt="image" src="https://github.com/user-attachments/assets/160ffb71-1828-4a6b-ad39-e853d0008982" />



2. I went to his File Explorer, looked for his H drive, and clicked on Properties. 


<img width="774" height="494" alt="image" src="https://github.com/user-attachments/assets/9e54e324-fa11-4b49-a4f7-0f4be414e689" />


3. I clicked into each folder on the H drive, and when I stumbled upon the photo archive, I saw that it held the most space on this drive. I decided to right-click on that folder and choose Cut, open the cloud drive, right-click on the space, and click Paste. He will still have access to those files, but now they'll be on the cloud drive, where he can log in at any time with the VPN and take a look at his files; it now frees up space on his H drive.


<img width="768" height="266" alt="image" src="https://github.com/user-attachments/assets/72b90bb1-5c67-4c1d-a3ee-d1eb39afa205" />



<img width="763" height="340" alt="image" src="https://github.com/user-attachments/assets/c61edd2c-5825-451d-8902-63bb48e4f3b5" />


<img width="762" height="412" alt="image" src="https://github.com/user-attachments/assets/72409f42-3f02-4f8e-a603-307f9fcc7707" />

4. I then checked the H drive and clicked on properties to view the free space after the file transfer.

<img width="396" height="346" alt="image" src="https://github.com/user-attachments/assets/45d89ab0-5908-4d51-a303-698da2c89534" />


## Ticket Notes 

- The user could not save to their H drive. Their laptop and desktop had plenty of space, and no one else was affected.
- Remoted into their computer and checked the H drive properties.
- Reviewed each folder and found the photo archive using the most space.
- Moved the photo archive from the H drive to their cloud drive.
- Rechecked the H drive properties and confirmed the free space increased.



<img width="700" height="148" alt="image" src="https://github.com/user-attachments/assets/c062923f-91b7-42a6-9102-335306414730" />



















































