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

# 🕵️‍♀️ Investigation Summary Report
## 🧩 Task One – Type of Attack & Rationale
### 🔍 Attack Type: Phishing + Malware Infection (Possible Ransomware)
* **Phising:**
The attacker impersonated the company’s HR department, tricking employees into updating their timesheets via a fraudulent email. This social engineering tactic is designed to harvest sensitive credentials.

* **Malware Execution:**
Once the phishing email was acted upon, a malicious payload was likely executed. Symptoms include:
    - Users unable to open Word documents they previously could.
    - Indicates potential ransomware or virus infection.
![Screen Shot 2025-06-13 at 2 09 55 PM](https://github.com/user-attachments/assets/bf32f52a-afbe-495b-9f47-51524ac79111)


## 🛡 Task Two – Immediate Next Steps (Cybersecurity Analyst Actions)
### 📝 Begin documenting the investigation in a detailed and auditable format.

**⚖️ Prioritize the incident based on:**

* Functional Impact
* Information Impact
* Recovery Effort

**🔐 Advise users to:**

* Change all login credentials
* Update and strengthen passwords
* Review and reset security questions

## 🔧 Task Three – Containment, Resolution & Recovery
### ✅ Key Actions to Take:
* 🔎 Identify and mitigate all exploited vulnerabilities
* 🧼 Remove malware from all affected endpoints and systems
* 🔁 Restore systems to a secure, operationally ready state
* 📈 Verify system integrity: Ensure normal functionality has returned
* 🛡 Monitor for reoccurrence or similar attack patterns

  
## 🧠 Task Four – Post-Incident Activities
### 📄 Create a detailed follow-up report documenting:

* Attack vector
* Affected systems
* Resolution steps taken
* Recovery timeline

### 🧩 Conduct a "Lessons Learned" meeting:

* Involve all relevant stakeholders
* Discuss response effectiveness and gaps
* Plan improvement actions

### 🎓 Launch a Cyber Awareness Program:

* Educate employees on phishing red flags
* Promote safe email and document handling practices
* Reduce future risk through behavioral change

📌 Note: This report should be updated as new findings emerge and remediations are completed. 









