# Overview 


High
Everyone who emails me gets a bounce saying recipient not found

Reported by: Priya Sharma (psharma@servicedesk-simulator.com)
Department: Engineering | Location: Floor 1
Contact: x6225

Issue Description:
Nobody can get an email to me. Every single person who tries gets it bounced straight back, and one of them forwarded me the rejection so I could show you what it says: 550 5.1.1 recipient not found, and it quotes my own address. My mailbox is still there, everything already in it is still there, and I sign in without any trouble at all. The only thing I can think of is that a while back my record got caught up in the paperwork for somebody who actually did leave. Somebody sorted that out the same afternoon and I was told it was fine. I have no idea whether the two things are connected, but this started around then and I am missing a lot of work.

Troubleshooting performed:
- Asked three people here to try again, all three got the same rejection back
- Asked a friend outside the company to try, same rejection
- Checked the junk folder, nothing new in there either
- Signed in to webmail, the mailbox opens and all my old mail is still in it

Business Impact:
Nothing at all is reaching me. Every request, every approval and every handover for my work arrives by email, and all of it is going back to whoever sent it.

<img width="930" height="652" alt="image" src="https://github.com/user-attachments/assets/6d6ce455-5215-4f55-b410-ab4eaa26a3ab" />


## Steps Taken 


1. 550 5.1.1 is a permanent SMTP error indicating that the recipient's mailbox does not exist or the address is invalid.  It is classified as a hard bounce, meaning the email will not be delivered even if retried, and immediate action is required to resolve the issue. Common causes include typos in the email address, deleted or inactive accounts, and corrupted Auto-Complete entries in email clients like Outlook. For administrators, it can also stem from misconfigured MX records, invalid forwarding rules, or outdated Offline Address Books

I went to the Directory and looked in the Authentication settings to see if the email is active or disabled. 

<img width="838" height="508" alt="image" src="https://github.com/user-attachments/assets/b02fcac6-7d82-4211-9c4a-24df4fc362fe" />


2. I then went to the Mailbox Menu (tab) and looked at the Proxy Address, and noticed the SMTP email was lowercase. I then clicked on Restore Primary Address.


<img width="502" height="448" alt="image" src="https://github.com/user-attachments/assets/9809e751-d56f-41a3-899d-a9d7e6033a9a" />

3. It then restored the primary address. In Active Directory and Exchange environments, the case of SMTP prefix in the proxy addresses attribute determines whether an address is primary or secondary. Uppercase SMTP designates the primary e-mail, meaning that this address is used as the default address for outgoing mail and the main identifier for the recipient object. Lowercase SMTP designates the secondary aliases for the proxy address. These addresses allow the recipient to receive mail at different addresses, but they are not used as a default reply address.


The way I would describe this to someone who doesn't know what I'm talking about basically the main address is printed on the return label and that's what the post office uses when you send someone and it's how people recognize you. But the extra addresses are like the old names or nicknames, and mail sent to them, but you never put a return label. 

4. I asked Priya if she could have someone send a test e-mail. 

<img width="400" height="250" alt="image" src="https://github.com/user-attachments/assets/467af5bf-616f-4230-94d7-3b813c1c6d35" />



## Ticket notes

- User reported that all senders inside and outside the company get a 550 5.1.1 recipient not found bounce; their mailbox opens, and old mail is intact.
- Identified 550 5.1.1 as a permanent error, meaning the system cannot find a valid recipient for the address.
- Checked authentication in the directory to confirm the account was active and not disabled.
- Opened the mailbox tab and found the SMTP entry in her proxy address written in lowercase. With no uppercase SMTP entry, no address was marked as the primary.
- Clicked Restore Primary Address, which set their main address correctly.
- Asked the user to have someone send a test email. It worked. 



<img width="488" height="358" alt="image" src="https://github.com/user-attachments/assets/4022f229-99a2-493c-b3a7-e02632bfa1be" />
























