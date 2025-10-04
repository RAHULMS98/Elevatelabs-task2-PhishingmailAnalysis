# 🎣 Phishing Mail Analysis

## 🎯 Objective
To analyze a sample phishing email and identify both **social engineering tactics** and **technical red flags** through header and URL inspection.

---

## 🧰 Methodology and Tools Used

### 📨 **Email Client**
Used to view the sample phishing email and extract its raw headers for in-depth technical inspection.

### 🧩 **MXToolbox Header Analyzer**
An online tool used to parse complex email headers, verify sender authenticity, and trace the message origin.  
Checked authentication mechanisms such as **SPF**, **DKIM**, and **DMARC** to detect spoofing.

### 🔗 **URL Scanner**
Used to scan and verify embedded links in the email body, confirming whether their destinations matched the displayed URLs and checking for malicious content.

---

## 🔍 **Analysis of Findings**

### ⚠️ **Email Spoofing**
The sender impersonated a legitimate organization but used a public domain (e.g., `@gmail.com`) instead of an official corporate email address.

### 🧠 **Social Engineering**
The message used **urgency and fear tactics**, such as threatening account suspension, to manipulate the recipient into taking immediate action.

### 🌐 **Mismatched URLs**
The hyperlink text appeared legitimate but redirected to a **non-corporate** or **malicious** domain upon inspection.

### 🧾 **Technical Discrepancies**
Header analysis showed **failed SPF, DKIM, and DMARC checks**, along with unusual mail routing — strong signs of email spoofing.

---

## 🧩 **Conclusion**
This exercise demonstrated how phishing emails exploit human behavior and technical loopholes.  
By analyzing email headers, URLs, and sender details, one can identify red flags and prevent falling victim to phishing attacks.

---

## 📂 **Tools Referenced**
- [MXToolbox Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)  
- [VirusTotal URL Scanner](https://www.virustotal.com/)  
- Any standard email client (e.g., Outlook, Thunderbird, or Gmail)

---

**Author:** Rahul Malatesh Sannapujar  
