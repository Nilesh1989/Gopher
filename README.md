## A Machine Learning based malicious domain detection
### Overview
A domain can be used for malicious purposes like 
- Malware, Virus or Trojan delivery
- Phishing
- Spam mails
- Malicious Ad Campaigns (Malvertising)
- Command and Control (C2C)
- DGA (Domain Generation Algorithms)
- Data Exfiltration etc.

So our idea was to develop an open source code to detect malicious domains using machine learning. We are using Scikit-learn, a free machine learning library for the python programming language. 
### Problems
- There are many repositories are available to detect malicious url, phishing domains, DGA in github. But the problem we have seen is, for different attacks we have different solutions.
- Even though attacks have same behaviours in most of the attacks, we have different solutions.
- The repositories are not updated up to the mark.

So we have decided to consolidate these behaviours into single problem and develop a prediction model for the detection of malicious domains. Thus we don't have to rely on different solutions and maintaining different models.