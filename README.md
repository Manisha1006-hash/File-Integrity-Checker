# Project Information

- Project Title: File Integrity Checker  
- Company: CODTECH IT SOLUTIONS  
- Intern Name: Manisha Chaudhary  
- Intern ID: CT06DN358  
- Domain: Cyber Security and Ethical Hacking  
- Internship Duration: 6 Weeks  
- Mentor: Neela Santosh  

# Project Description

The File Integrity Checker is a useful and handy utility in cybersecurity that keeps files' integrity under check by computing and comparing hash values. File integrity forms the foundation of secure systems' maintenance since any unauthorized or accidental changes to files can bring vulnerabilities, malware, or loss of data. The tool is developed using Python and the Flask web framework so that it is user-friendly and accessible via a clear web interface.

The application utilizes the SHA-256 cryptographic hash function from Python's `hashlib` library to compute a file's hash. Upon uploading a file, the application computes its SHA-256 hash and checks it with hashes saved earlier in a local JSON database (`hash_db.json`). Depending on this check, the tool decides if the file is new, unchanged, or has been modified. Such a mechanism guarantees that any change even in a single byte of the file will be captured, thus offering strong file monitoring functionality.

For secure access to the system, the program comes with a user authentication system and Multi-Factor Authentication (MFA). Users are required to register using their email and password, which is hashed securely with SHA-256 before it is stored. At login, upon verification of password, a One-Time Password (OTP) is sent to the email ID at login using Flask-Mail. This OTP needs to be confirmed before the user is granted access to the dashboard, making a huge difference in the security stance of the app. Email operations are carried out securely utilizing an application-specific password for Gmail, conforming to new security standards.

The project also boasts a graphical and interactive Graphical User Interface (GUI) created with HTML, CSS, Bootstrap, and Jinja templating. The interface has customized background pictures, formatted forms, easy-to-use navigation, and visually different outcome pages that report whether or not files have been altered or are safe. This allows for an enjoyable and effortless user experience while still being functional.

The upload mechanism is supported by Python's `os` and `werkzeug` modules to manage file storage securely. Uploaded files are saved in a special folder (`monitored_files/`) and their hash digests are stored in a JSON file for long-term integrity monitoring. The database supports ongoing monitoring and rapid comparisons on subsequent uploads.

This project not only improves technical competence in web development, cryptography, and security best practices, but also mimics a true-to-life file monitoring system employed in working environments to identify ransomware attacks, insider attacks, and accidental file modifications. It is an application of cybersecurity concepts in the real world and helps solidify the significance of integrity in the preservation of digital trust.

In summary, the File Integrity Checker is a secure and effective solution for any organization or individual seeking to protect their data against unauthorized change. Through its combination of hands-on functionality, security, and interactive usability, it is both an educational experience and a useful security tool.

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
