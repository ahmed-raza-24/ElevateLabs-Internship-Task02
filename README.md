Phishing Email Header Analysis
==============================

This project provides a detailed analysis of a suspicious phishing email by examining its headers using free online header analyzers.

📌 Objective
------------
To identify signs of phishing by analyzing email header fields such as sender address, authentication results, and delivery path.

🧪 Sample Email Summary
------------------------
- Subject: Microsoft account unusual signin activity
- From: no-reply@access-accsecurity.com
- Reply-To: sotrecognizd@gmail.com
- Return-Path: bounce@thcultarfdes.co.uk
- Sender IP: 89.144.44.2

🛡 Authentication Checks
-------------------------
- SPF: None (sender domain does not designate permitted hosts)
- DKIM: None (email not signed)
- DMARC: Permerror (policy evaluation failed)

🔍 Key Observations
--------------------
- Sender domain is not owned by Microsoft.
- Reply-To address is a personal Gmail account.
- Authentication methods (SPF, DKIM, DMARC) all failed.
- Message uses urgency and scare tactics typical of phishing.
- IP address is from an untrusted source.

✅ Conclusion
-------------
The email exhibits several common traits of phishing:
- Forged sender identity
- Redirected reply-to
- Failed authentication
- Unusual subject content

📢 Do not trust or interact with emails containing these signs.

📁 Files Included
-----------------
- Task02.txt – Summary of the phishing analysis report
- Task02.txt – This file

⚠️ Disclaimer
--------------
This analysis is for educational and awareness purposes only. No actual phishing emails were sent, and no systems were compromised.
