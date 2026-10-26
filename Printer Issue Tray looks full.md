# Overview 

Printer says it is out of paper but the tray looks full

Reported by: Michael Brown (mbrown@servicedesk-simulator.com)
Department: Engineering | Location: Floor 3
Contact: x6270
Printer: Floor3-Printer-C

Issue Description:
The printer keeps saying load paper and will not print anything, but the tray is full. I took the paper out and put it back in and it still says the same thing. It worked yesterday.

Troubleshooting performed:
- Took the paper out and put it back
- The tray looks full to me
- Printed fine yesterday

Business Impact:
Cannot print anything from this printer.

<img width="592" height="522" alt="image" src="https://github.com/user-attachments/assets/906b33cf-c1ef-4c14-a0a3-9e0d06383045" />


## Steps Taken


1. I wanted to check in with Michael and see if anyone else is having issues or just him. So I asked him whether anyone else was having issues.

<img width="380" height="384" alt="image" src="https://github.com/user-attachments/assets/eeed3269-3458-4a51-a9e9-d1de11cabbcf" />

2. Since no one else is having issues, I went to the documentation for our devices and looked for our IP address for the floor 3 printer.

<img width="818" height="468" alt="image" src="https://github.com/user-attachments/assets/333e14ba-b5c5-4506-ab7a-385e81cfbbc9" />

3. I then remoted into his computer and checked for a system update

<img width="924" height="554" alt="image" src="https://github.com/user-attachments/assets/03fe00b4-8b55-4b27-9289-c76b1cc65274" />


4. After that, I went to Devices and checked the printer on floor 3 to see if it had the correct IP address, and then went to Properties and clicked on Print Test Page.

<img width="790" height="558" alt="image" src="https://github.com/user-attachments/assets/a804316d-c742-4017-8e20-257be8e7425d" />

<img width="428" height="238" alt="image" src="https://github.com/user-attachments/assets/bebd7203-dafc-404d-8b22-ab39bba2008a" />

5. This is an interesting problem because the computer is telling me that the printer for floor 3 is connected. We checked that the IP address is correct, it even allowed me to print a test page and said it was going to be printed.
Then I asked Michael to check if the test page was printed, and he replied that it still says out of paper even though he refilled it. Could this be a paper jam that's not letting us, or maybe he overstacked it? He did. 


<img width="398" height="512" alt="image" src="https://github.com/user-attachments/assets/a3da9272-b64a-4f1a-a1c0-eae1f03b43e2" />

6. Resolved.


# Ticket Notes 

- Asked Michael whether anyone else was affected. No one else was.
- looked for floor 3's printer IP address in the device documentation
- Remoted into Michael's computer and checked for system updates
- checked devices and confirmed that the printer was connected with the correct IP address
- printed a test page from properties and the computer reported it has sent but the printer still showed out of paper.
- ruled out the computer and network problem and asked Michael about the tray to see if he had overstacked the paper
- Michael reduced the paper in the tray, and the printer started printing. 

<img width="476" height="318" alt="image" src="https://github.com/user-attachments/assets/40347c83-c60f-4334-8568-ecfebfe20036" />















