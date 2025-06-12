# Project Information

- Project Title: File Integrity Checker  
- Company: CODTECH IT SOLUTIONS  
- Intern Name: Manisha Chaudhary  
- Intern ID: CT06DN358  
- Domain: Cyber Security and Ethical Hacking  
- Internship Duration: 6 Weeks  
- Mentor: Neela Santosh  

# Project Description

File Integrity Checker is a handy and useful tool in cybersecurity that maintains files' integrity under surveillance by calculating and comparing hash values. File integrity is the backbone of secure systems maintenance as unauthorized or accidental changes to files can introduce vulnerabilities, malware, or data loss. The tool is programmed in Python and Flask web framework such that it is easy to use and accessible through a simple web interface.

The application uses Python's hashlib SHA-256 cryptographic hash function to calculate a file's hash. When a file is uploaded, the application calculates its SHA-256 hash and compares it with hashes stored previously in a local JSON database (hash_db.json). Based on this comparison, the tool determines whether the file is new, unmodified, or modified. Such a mechanism ensures that whatever alteration even in one byte of the file will be recorded, thereby providing robust file monitoring capability.

For safe access to the system, the software also has a user authentication system and Multi-Factor Authentication (MFA). Users have to register with their email and password, which gets securely hashed using SHA-256 before being stored. On login, after password verification, One-Time Password (OTP) is sent to the email ID at login via Flask-Mail. The OTP must be verified before the user can be allowed to access the dashboard, having a drastic impact on the security position of the app. Email operations are performed securely using an application-specific password for Gmail, adhering to new security standards.

The project also has a graphical and interactive Graphical User Interface (GUI) developed using HTML, CSS, Bootstrap, and Jinja templating. It features personalized background images, styled forms, navigability, and visually distinct outcome pages that indicate whether files have been modified or not, and whether they are safe or not. This provides for a pleasant and seamless user experience while remaining functional.

The upload process is backed by Python's werkzeug and os modules for secure storage management of uploaded files. The uploaded files are stored in a designated folder (monitored_files/) and their hash digests are stored in a JSON file for long-term integrity checks. The database allows for continuous monitoring and quick comparison on future uploads.

This project not only enhances technical proficiency in web development, cryptography, and security best practices but also replicates a real-world file monitoring system used in working environments to detect ransomware attacks, insider attacks, and unintentional modifications to files. It is an implementation of cyber security concepts in the real world and serves to cement the importance of integrity in the upholding of digital trust.

In short, File Integrity Checker is a safe and efficient measure for any company or user who wants to secure their data from unauthorized modification. Its blend of hands-on functionality, security, and interactive convenience makes it not only an educational experience but also a valuable security utility. It also includes proper logging and error handling mechanisms to ensure reliability and traceability. The tool can be extended further to send alerts or logs to centralized monitoring systems for enterprise use.

# Technologies Used

- Python 3
- Flask
- Hashlib (SHA-256)
- Flask-Mail
- HTML5 / CSS3 / Bootstrap 5
- Jinja2 Templates
- JavaScript (Minimal)
- .env Configuration
- JSON (for storage in hashes)

# Set-up Instructions

1. Clone or download this repository.
2. Initiate a virtual environment and activate it.
3. Install dependencies via:
   'pip install -r requirements.txt'
4. Run through terminal via:
   'app.py'.

# oUTPUT
![Image](https://github.com/user-attachments/assets/1f833d27-d666-4143-9c25-dcb2cf4a6361)

![Image](https://github.com/user-attachments/assets/90342a40-6f0d-4290-bd8b-c17ce13ab87c)

![Image](https://github.com/user-attachments/assets/0c288b78-9e09-4196-abcc-5f8cd316fd7c)

![Image](https://github.com/user-attachments/assets/98613cf6-621d-4a35-ac61-bb58b5f8cba6)

![Image](https://github.com/user-attachments/assets/04291b45-cdf3-40c6-9a0f-e5eed8ee0ba6)

![Image](https://github.com/user-attachments/assets/cb59f778-3a93-44f3-bfc2-41f728214814)
