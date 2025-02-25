

| Ticket ID | Alert Message | Severity | Details | Ticket status |
| :---- | :---- | :---- | :---- | :---- |
| A-2703 | SERVER-MAIL Phishing attempt possible download of malware | Medium | The user may have opened a malicious email or possibly opened attachments/clicked links. | **Investigating** |


| **Alert Ticket Evaluation** |
| :---- |
### __**Who Caused The Incident?**__  
The incident was caused by an unrecognized sender using the name Clyde West and the email ID *Def Communications;* however the real email address is marked as 76tguyhh6tgftrt7tg.su causing doubt to the true identity of the sender. 

--------------------------
### __**What Happened?**__
The user opened an email sent by *Def Communications* which contained unknown links and attachments which the user has then accessed/opened by inputting a password to access the file which has then installed a malicious program onto the computer. 

--------------------------
### __**When Did The Incident Take Place?**__
Wednesday, July 20, 2022 at 09:30:14 AM.

--------------------------
### __**Where Did The Incident Occur?**__
On one of the systems used by the HR department. 

--------------------------
### __**Why Did It Happen?**__ 
The user did not properly check the email for signs of malicious activity or verify the legitimacy of the email address. The subject line and body both contain serious grammatical errors along with the email address using a suspicious name and not matching with the sender's ID. 

--------------------------
### __**Conclusion**__ 
After verifying that the hash has been associated with malicious files in the past and due to the alert severity level reporting at medium, I have chosen to escalate this ticket to a level-two SOC analyst to conduct further investigation into this matter.

--------------------------

### **Additional information**

**Known malicious file hash**: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

**Email**:  
From: Def Communications \<76tguyhh6tgftrt7tg.su\>  \<114.114.114.114\>  
Sent: Wednesday, July 20, 2022 09:30:14 AM  
To: \<hr@inergy.com\> \<176.157.125.93\>  
Subject: Re: Infrastructure Egnieer role

Dear HR at Ingergy,

I am writing for to express my interest in the engineer role posted from the website.

There is attached my resume and cover letter. For privacy, the file is password protected. Use the password paradise10789 to open. 

Thank you,

Clyde West  
Attachment: filename="bfsvc.exe"

