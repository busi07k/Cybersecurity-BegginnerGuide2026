# 🔴 Red Team: The Ethical Attackers

Welcome to the offensive side of cybersecurity. The Red Team's goal is to simulate real-world cyberattacks to expose vulnerabilities before real attackers do.

---

Career Path: Roles & Levels

Because this is a more advanced field, the career path looks different than the Blue Team. You are entering at a Mid-level expectation.

### 🟡 Mid-Level (The Starting Point for Offensive Sec)
*This is where you aim to land after building experience elsewhere.*

* **Vulnerability Analyst:** The gateway role. You use automated tools (like Nessus or Qualys) to scan networks, find outdated software, and write reports on how to patch them. It is less "hacking" and more "auditing."
* **Penetration Tester (Pentester):** The classic "ethical hacker." You are hired for a short period (1-2 weeks) to attack a specific web application or network segment and report the vulnerabilities you found. 
* **Application Security (AppSec) Engineer:** Focused entirely on code. You work closely with developers to ensure the software they write is secure from the start (finding SQL injections, XSS, etc., before the app is launched).

### 🔴 Senior & Advanced Levels
*The true "Red Team" roles require deep technical expertise and creativity.*

* **Red Team Operator:** Unlike a Pentester who attacks a specific app, a Red Teamer simulates an Advanced Persistent Threat (APT). They try to breach the entire organization over weeks or months, using phishing, physical breaches, and custom malware, while actively avoiding detection by the Blue Team.
* **Exploit Developer:** You don't just use hacking tools; you create them. You find "Zero-Day" vulnerabilities in software and write the code to exploit them. 
* **Malware Developer:** You write custom viruses, trojans, and ransomware simulations specifically designed to bypass the latest EDRs and Antiviruses used by the Blue Team. *(This is highly advanced and requires deep C/C++, OS internals knowledge and evasion techniques).*

---

### The Certifications: Reality Check

In the offensive side, multiple-choice exams are useless. Certifications here are grueling 24-hour to 5-day practical hacking exams. We divide them into two categories:

#### 🟢 The Stepping Stones (Junior Level)
*Do not expect to get a job instantly with these. They are designed to build your confidence and prove you know the methodology before attempting the big ones. ( choose one )*

* **[eJPT (eLearnSecurity Junior Penetration Tester)](https://securityblue.team/):** A very popular beginner certification. It proves you know how to run a basic pentest, use the tools, and write a report.
*How to study:* This exam is tied to **INE Security's Penetration Testing Student (PTS)** course.
  
* **[PJPT (Practical Junior Penetration Tester)](https://certifications.tcm-sec.com/pjpt/):** By TCM Security. Highly recommended over the eJPT because it focuses heavily on attacking internal networks and Active Directory (which is what companies actually use).
*How to study:* This exam is tied to TCM Security's **Practical Ethical Hacking (PEH)** course.

#### 🔴 The Job Getters (Mid Level)
*These are the certifications that actually make recruiters and technical leads take you seriously. If you have one of these, you will get interviews.*

* **1. [OSCP (OffSec Certified Professional)](https://www.offsec.com/certifications/oscp/):** **The Holy Grail of Red Team.** It is the most recognized offensive certification in the world. It is an exhausting 24-hour exam where you must hack multiple machines and Active Directory environments. It is the ultimate HR filter.
*How to study:* OffSec provides their own official course **(PEN-200)**. Students also heavily practice with HackTheBox and OffSec's Proving Grounds before the exam.
  
* **2. [CPTS (HTB Certified Penetration Testing Specialist)](https://academy.hackthebox.com/preview/certifications/htb-certified-penetration-testing-specialist):** HackTheBox's own certification. Many senior professionals consider this exam *significantly harder and more realistic* than the OSCP. While HR might still look for OSCP, technical leads respect the CPTS immensely.
*How to study:* You MUST complete the **HTB Academy Penetration Tester Path** (linked in Step 1).
  
* **[PNPT (Practical Network Penetration Tester)](https://certifications.tcm-sec.com/pnpt/):** A 5-day exam where you must perform OSINT, bypass external defenses, breach an Active Directory domain, and present a professional debrief to a "client". Very realistic and highly respected.
*How to study:* TCM Security provides a specific bundle of training courses explicitly for this exam.
---

**Summary:** Do the THM paths to learn the basics. Take the eJPT or PJPT to test your nerves. Then, lock yourself in a room for 6 months, study the HTB paths, and survive the OSCP or CPTS to get the job.

> Extra tip: I recommend you that you become active in community, post write-ups of the labs you break, what you learn everyday, help, and let them help you. GoodLuck Mr.Robot!!
