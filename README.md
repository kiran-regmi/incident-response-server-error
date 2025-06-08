# Dealing with compromised server 
At Commonwealth Bank, it is the responsibility of the cyber security team to deal with daily cyber related incidents. Today, the team leader has nofied that there has been a soft complain that server might have been compromised. **What would you do?**

**In this project**, we will try to answer the following:
* Task one - What kind of attack has happened and why do we think so?
* Task two - As a cyber security analyst, what are the next steps to take? 
* Task three - How would we contain, resolve and recover from this incident? 
* Task four - What activities should we performed post-incident?

# Table of Content 
* Investigating The Incident
* Listing of Resources to Explore
* Investingation Summary Report

## Investigating the Incident 
How is the problem started?
* 10:30 a.m. – The IT Service Desk receives a report from one of our colleagues at the bank that they have received an email from HR telling all employees to update their timesheets in the company’s support portal so the timesheets can be approved on time by their line managers against the next pay day. The colleague clicked the link in the email that opened what looked like the portal. However, following the employee's input of the user credentials, an unfamiliar error page appeared like the one below.
![Screen Shot 2025-06-06 at 5 39 05 PM](https://github.com/user-attachments/assets/d9435f78-86cb-4bd7-8dcc-4ff24c09a5d2)

* 2:00 p.m. – Eight more reports of emails similar to the one reported earlier are received by the IT Service Desk. Upon further investigation, it was found that 62 colleagues across the Risk Department received the same email over the course of two days.  The emails directed the users to a fake website to steal their usernames and passwords and download a harmful program.
* 3:50 p.m. – The IT Service Desk receives calls and emails from more colleagues that the file-shares are not opening and they receive an error when trying to open a Word document they have always been able to open.


### List of resources to explore:
- ***[Top 10 Common types of Cybersecurity Attacks](https://www.datto.com/blog/common-types-of-cyber-security-attacks/)***
- ***[11 Types of Phishing + Real-Life Examples](https://www.pandasecurity.com/en/mediacenter/types-of-phishing/)*** 
- ***[8 Critical steps to take after a ransomware attack: Ransomware response guide for businesses - Emsisoft | Security Blog](https://www.emsisoft.com/en/blog/36921/8-critical-steps-to-take-after-a-ransomware-attack-ransomware-response-guide-for-businesses/)***
- ***[Battling Ransomware: How to Respond to a Ransomware Incident](https://www.forbes.com/councils/forbestechcouncil/2018/12/27/battling-ransomware-how-to-respond-to-a-ransomware-incident/)***
- ***[Frequently Asked Questions - Ransomware | Information Security Office](https://security.berkeley.edu/faq/ransomware/)***
- ***[What to do before and after a cybersecurity breach?](https://www.american.edu/kogod/research/cybergov/upload/what-to-do.pdf)***

### Investigation Summary Report:
**Task one - What kind of attack has happened, and why do you think so?** 
* In a **phishing attack**, the perpetrator pretends to be a reputable entity or person via email to obtain sensitive information like login credentials. In this case, the attacker disguised as the company's HR by asking employees to update their **timesheets**. 
* **Malware** is intrusive software designed to harm or exploit computers. In this case, the user executed a phishing attack payload that may have installed malware onto their system. As users cannot open a Word document that they have always been able to open, this could be ransomware or a virus.
  
**Task two - As a cyber security analyst, what are the next steps to take? List all that apply.** 
* Begin documenting the investigation. 
* Prioritise handling the incident based on factors such as functional impact, information impact and recoverability effort. 
* Advise users to change and strengthen all logins, passwords and security questions. 

**Task three - How would you contain, resolve and recover from this incident? List all answers that apply.** 
* Identify and mitigate all exploited vulnerabilities. 
* Attempt to remove malware from all hosts affected. 
* Return affected systems to an operationally ready state. 
* Confirm that the affected systems are functioning normally. 
* Stay alert and continue to monitor for any similar future activity. 

**Task four - What activities should be performed post-incident?** 
* Follow-up report detailing everything that occurred. 
* Hold a lesson-learnt meeting. 
* Educate: Create a cyber awareness program for employees. Such programs help employees identify future phishing emails.














