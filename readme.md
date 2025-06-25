cybersecurity-internship
task 2 of the cybersecurity internship

Phishing Email and Header Analysis
Task Overview
This project is part of a cybersecurity internship exercise to analyze a phishing email and examine its headers to identify signs of phishing and email spoofing.

Phishing Email Details
Subject:
>>shashank.ss935!! - "You have won a Makita Tool Set 🎁. ID#9738"

From:
LIDL™ <info@dmxnkuzj.sdgdsrgt.innovativetech2.net.pl>

To:
shashank.ss935@gmail.com

![phishingemail](https://github.com/user-attachments/assets/c653c676-700d-4207-a406-d22a3b3a743d)

Phishing Indicators
Suspicious Sender Address:
The email is pretending to be from LIDL but the sender domain is innovativetech2.net.pl, which is not a legitimate LIDL domain.

Urgent Language:
The message says “Hurry up. The number of prizes is limited! Confirm now!” to pressure the user to act quickly.

Too Good to Be True Offer:
Claims that the user has won a Makita Tool Kit without participating in any contest.

Mismatched Branding:
Poor formatting and color schemes that do not match the professional look of LIDL’s actual emails.

Suspicious Links:
The “Confirm Now” button is likely to lead to a phishing website. (Actual link not visible but commonly a phishing trap.)
link: https://storage.googleapis.com/elbualezdiali/trackingh%20(1).html#4LMjAP12997tAsx111ppaxehzfih69MYFQMJHORLGMEMB807525CUSF1382n22


![phishingemail1](https://github.com/user-attachments/assets/183ddcb1-69cf-4516-a477-a96d4f233941)

Email Header Analysis
Return-Path:
69-807525@sdgsdrgt.innovativetech2.net.pl

Received-SPF:
pass (but the IP belongs to a suspicious domain)

DKIM:
pass but it is signed by an unknown domain, not LIDL’s official domain.

ARC-Authentication-Results:
Authentication passed, but the source domain is not trustworthy.

Relay Path:
The email traveled from: vgjxgprw.com

repudiandaeguzvf.mikado.dpdns.org (IP: 5.196.26.30)

![phishing header](https://github.com/user-attachments/assets/6bc55e21-013b-43ab-82ea-691eba347cfe)

Delivered to Gmail server

Blacklist Check:
The sending server was flagged in blacklist checks.
![phishing blacklist](https://github.com/user-attachments/assets/de61b8e3-b93a-4124-bb64-9cb443291c29)

Key Findings
The email passed SPF and DKIM, but these can be configured on unauthorized domains.

The sending IP is linked to suspicious activity.

The offer and sender information indicate a phishing attempt.

The email uses social engineering tactics to make the recipient act quickly.


Conclusion
This phishing email uses social engineering, fake rewards, and domain spoofing to trick the recipient into clicking a malicious link. Despite passing some authentication checks, header analysis reveals the true source and confirms phishing intent.

