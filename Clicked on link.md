# Overview 

Critical
I clicked a link in an email and now my PC is acting up

Reported by: Ivana Petrova (ipetrova@servicedesk-simulator.com)
Department: Engineering | Location: Remote (Working from home)
Contact: x6180

Issue Description:
I got an email that looked normal and clicked the link in it. A weird rainbow-coloured web page opened saying I have been phished, and now there is a program on my computer I definitely did not install. I am worried someone has access to my account. What do I do?

Troubleshooting performed:
- Clicked a link in an email
- A strange full-page message opened in the browser
- There is an unfamiliar app installed now

Business Impact:
A phishing link installed a rogue app and may have exposed the user's credentials. Account and endpoint both need to be secured.


<img width="728" height="510" alt="image" src="https://github.com/user-attachments/assets/8c7c15e1-1697-4c45-941b-4940bea46996" />


## Steps Taken 

1. I am technically the first line of defense when it comes to tickets like this because I should follow the company's policies, but I should know how to handle the situation before I escalate. The reason why I will need to escalate this later on is that I don't have certain privileges that a SOC analyst might have, such as access to different programs, different software, and access controls that they're able to investigate the link that the user clicked on that created this situation.

I'm going to first send them a verification code in order for them to be able to reset their password and then reset MFA because there's a 50/50 chance that the phishing site that the user clicked on might have captured some of the tokens or the MFA token in this case.


<img width="1146" height="506" alt="image" src="https://github.com/user-attachments/assets/9ee921f2-f0d5-4e72-bbe1-7c9b61db7ee7" />


<img width="402" height="264" alt="image" src="https://github.com/user-attachments/assets/a967e7f2-3e2d-41ec-8d00-6f3e2c086cb6" />

2. I'm then going to send her the temporary password, and she should be able to create a new password.

<img width="616" height="406" alt="image" src="https://github.com/user-attachments/assets/8c1b1dbe-9ce5-4877-a978-229169fc7aa3" />


<img width="420" height="334" alt="image" src="https://github.com/user-attachments/assets/85f94e76-5346-4d87-9057-1aea4436b007" />


<img width="440" height="422" alt="image" src="https://github.com/user-attachments/assets/5b440ba8-9701-4054-88eb-18e36829db0f" />


3. Once I clicked on Reset Password, I then clicked on Reset MFA, and now the next time she logs in, it will prompt her to provide two or more distinct forms of verification to access her account or her computer, reducing the risk of unauthorized access. MFA ensures that even if one credential is compromised, attackers cannot easily gain entry without additional required factors.


<img width="440" height="422" alt="image" src="https://github.com/user-attachments/assets/12bf6d11-ca41-4cb2-a154-3ed8b84d60b6" />



4. I want to remote into her computer, look in Control Panel and look for the unfamiliar app that the link installed, and uninstall it.  

<img width="960" height="802" alt="image" src="https://github.com/user-attachments/assets/de1499ea-e9aa-4c8b-b33c-55d3df8d8c35" />

<img width="857" height="524" alt="image" src="https://github.com/user-attachments/assets/89c7815f-ebf4-44aa-8505-12268086bf9e" />


5.  I then went to Settings, clicked on Security, and clicked on Full Scan. 

<img width="754" height="534" alt="image" src="https://github.com/user-attachments/assets/3bdfd05a-334a-4976-8715-339fa98e9e22" />



6. After the scan was completed, it detected one threat and removed it. The device is now clean. What I will do now is escalate it to the SOC analyst team. This escalates the ticket to the security team. This will only be done for genuine security issues. 

<img width="704" height="488" alt="image" src="https://github.com/user-attachments/assets/bc83604d-4186-4a86-a88a-52980e13220f" />

<img width="402" height="202" alt="image" src="https://github.com/user-attachments/assets/63801904-50d0-4190-8416-3dc9542f7050" />



## Ticket Notes

- User clicked on a link in a suspicious e-mail; a phishing page opened, and an unknown app appeared on their computer with a possible credential exposure.
- verified users identity by sending them a verification code and then resetting their password and send a temporary password.
- reset MFA so they can set up verification again at their next login, in case the threat actor captured their token.
- Remoted into their computer, found the unfamiliar app in Control Panel, and uninstalled it.
- Ran a full scan in Security Settings; it found one threat and removed it device is now clean.
- Escalated the ticket to the SoC analyst team to investigate the link and check for account compromise.





















































