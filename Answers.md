# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
 Python Pillow
2. Which CVE is linked to this vulnerability?
CVE-2023-50447
3. What remediation steps do you suggest?
Run your code in a “jail” or similar sandbox environment that enforces strict boundaries between the process and the operating system. This may effectively restrict which code can be executed by your product.
### Vulnerability 2:
1. Which vulnerability are you addressing?
PyYAML 5.1
2. Which CVE is linked to this vulnerability?
CVE-2019-20477
3. What remediation steps do you suggest?
Make fields transient to protect them from deserialization. 
