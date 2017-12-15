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


You can use the [editor on GitHub](https://github.com/Nilesh1989/Detection-Of-Malicious-Domain/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Nilesh1989/Detection-Of-Malicious-Domain/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
