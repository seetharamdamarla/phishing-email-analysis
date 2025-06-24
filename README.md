# 📧 Phishing Email Analysis

This repository contains the analysis of a sample phishing email as part of a Cyber Security Internship (Task 2).

---

## 📌 Objective

To identify and document phishing characteristics in a suspicious `.eml` email file using email header analysis, URL inspection, and social engineering detection techniques.

---

## 🛠 Tools Used

- **Thunderbird Mail** – To open and inspect the `.eml` file
- **EML Analyzer** – To analyze email headers and links
- **MXToolbox** – For checking IP reputation and header analysis

---

## 📁 Repository Structure

phishing-email-analysis/
│
├── phishing_email.eml # Sample phishing email file
├── README.md # Project documentation (this file)
│
├── analysis/
│ └── eml_analyzer_report.txt # Header and spam verdict analysis
│
└── screenshots/
├── mxtoolbox_result_1.png
├── mxtoolbox_result_2.png
└── mxtoolbox_result_3.png


---

## 🔍 Key Findings

- **Sender Domain Spoofing**: `support@paypa1.com` (not `paypal.com`)
- **Suspicious Link**: `https://paypal-security-update.com/verify`
- **Threatening Language**: “Failure to verify will result in suspension”
- **Blacklisted IP**: 192.0.2.1 – lacks rDNS and flagged in RBLs
- **Generic Greeting**: “Dear Valued Customer” (no personalization)

---

## 📸 Screenshots

Screenshots of MXToolbox results and tools used can be found in the [`screenshots/`](screenshots/) folder.

---

## ✅ Conclusion

This phishing email exhibits multiple red flags including spoofed domains, fake URLs, and social engineering language. The analysis helps build awareness and understanding of email-based threats.

---

## 🔗 Submission

Submitted as part of Task 2 of the Cyber Security Internship Program.
