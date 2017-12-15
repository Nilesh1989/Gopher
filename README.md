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
### Quick Start
### Feature Least
1. URL length
2. Host length
3. Number of dots
4. Host ranking in city
5. Host ranking in country
6. URL average token length
7. Host average token length
8. Path average token length
9. URL token count (Considering words as a token)
10. Host token count
11. Path token count
12. URL largest token length
13. Host largest token length
14. Path largest token length
15. IP address presence
16. ASN number
17. Safe browsing
18. Domain age
19. Number of subdomains
20. Is IDN (International Domain Name)
### To-Do
- Will add more machine learning models
- Will add Is domain from dynamic DNS as a feature
- Will add shortened URL as a feature
- Will add number of special characters (- and _) as a feature
- Will add website contents as a feature
### Results
### Refrences