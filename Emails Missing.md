# Overview 


Emails to me are going missing, the sender says they were sent

Reported by: Jessica Tran (jtran@servicedesk-simulator.com)
Department: Engineering | Location: Floor 3
Contact: x6255

Issue Description:
Priya Raman sent me something yesterday and says it went through fine, but it never arrived. Same thing with another message this morning. Can you check what is happening to my mail? I have not changed anything on my end. I've never actually met Priya Raman, they're an outside contact at Kestrel Ridge Supply. They keep calling and messaging me to say they've sent it again and I should check my email, and nothing ever turns up.

Troubleshooting performed:
- Asked the sender to resend, still nothing
- Restarted Mail

Business Impact:
Incoming mail to the user has not been delivered since yesterday; replies and attachments from colleagues are being lost.

<img width="922" height="576" alt="image" src="https://github.com/user-attachments/assets/026eeffb-b275-4690-ab36-dd518754aab8" />


## Steps Taken

1. I wanted to double-check with Jessica to see if she can connect to the internet.

<img width="402" height="690" alt="image" src="https://github.com/user-attachments/assets/f0429830-8c88-47f8-8fe4-15644589eaf0" />


2. It seems like there can be an issue with her email inbox configuration. I wanted to see if there were any failure or error codes, so I went to Mail Admin, a tool I can use to check dates, sender, recipient, subject, and status.

<img width="1120" height="304" alt="image" src="https://github.com/user-attachments/assets/00528992-b2c2-460a-bc12-f73ecaab9566" />


3. After doing some research, I found out that the SMTP error 550 5.7.1 is a permanent rejection code indicating that the receiving mail server refused the message due to a security policy violation or authentication failure. It is not a temporary network issue but is definitively blocking this message. This error often triggers when directory-based edge blocking occurs because the recipient address doesn't exist in a tenant directory or the message violates specific mail flow rules.


Jessica said that Priya sent a message, and they were outside contacts at Kestrel Ridge Supply. 

<img width="1120" height="304" alt="image" src="https://github.com/user-attachments/assets/685895cf-d8ed-4f01-be36-ba5c61a0755f" />




4. I went to Mail Security and looked for jtran@servicedesk-simulator.com to look for Priya's mail. I released it to Jessica. 


<img width="1153" height="806" alt="image" src="https://github.com/user-attachments/assets/b5b8fdb2-4f92-4f73-9263-d3b886904da7" />


## Ticket Notes

- User reported that the email from Priya Raman (Krestrel Ridge Supply) Resending did not help.
- Confirmed with Jessica that her internet connection works.
- Checked Mail Admin for the sender, recipient, subject, and status of the messages.
- Found the messages rejected with SMTP error 550 5.7.1, a permanent rejection for a security policy violation.
- Checked Mail Security for jtran@servicedesk-simulator.com and found Priya's email held there.
- Released the email to Jessica. 

<img width="378" height="280" alt="image" src="https://github.com/user-attachments/assets/d17a0f54-7e1a-4c6a-912e-7df0dd341269" />














































































