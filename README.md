

# Password Cracking and Hash Analysis Using Johnny (John the Ripper)

![Johnny](https://img.shields.io/badge/Tool-Johnny-blue?style=for-the-badge)
![John the Ripper](https://img.shields.io/badge/John_the_Ripper-Password_Auditing-red?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Password_Security-green?style=for-the-badge)
![Hash Cracking](https://img.shields.io/badge/Hash_Analysis-PDF-orange?style=for-the-badge)
![Networkwalks](https://img.shields.io/badge/Training-Networkwalks-blueviolet?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

A hands-on cybersecurity exercise exploring password cracking and hash analysis using Johnny, the graphical user interface for John the Ripper. The exercise focused on understanding password recovery, wordlist-based attacks and the importance of password security.

## Table of Contents

- [Project Overview](#project-overview)
- [Objective](#objective)
- [Tools and Environment](#tools-and-environment)
- [Practical Activities](#1-practical-activities)
- [Findings and Observations](#2-findings-and-observations)
- [Challenges and Solutions](#3-challenges-and-solutions)
- [Lessons Learned](#4-lessons-learned)
- [Skills Developed](#5-skills-developed)
- [Security Recommendations](#6-security-recommendations)
- [Conclusion](#7-conclusion)
- [Ethical Use and Disclaimer](#8-ethical-use-and-disclaimer)

## Project Overview

This exercise involved using Johnny to perform password recovery against a PDF password hash in an authorised cybersecurity training environment.

Johnny provides a graphical interface for John the Ripper, allowing users to manage password-cracking sessions and examine their results.

The practical exercise demonstrated how wordlist-based password attacks can identify weak passwords and why strong password practices are important.

## Objective

- Understand the fundamentals of password cracking.
- Explore Johnny and its password-cracking interface.
- Investigate password hashes associated with PDF documents.
- Understand the role of wordlists in password recovery.
- Analyse password-cracking results.
- Capture the flag associated with the practical lab exercise.

## Tools and Environment

| Tool / Component | Purpose |
|---|---|
| Johnny | Graphical interface for password auditing |
| John the Ripper | Password-cracking engine |
| Wordlist | Supplies candidate passwords for testing |
| PDF hash | Password-protected document hash used in the exercise |
| Windows | Environment shown in the Johnny screenshot |
| Networkwalks Academy | Practical cybersecurity training environment |

## 1. Practical Activities

### Activity 1: Working with Johnny

I used Johnny, the graphical interface for John the Ripper, to manage the password-cracking exercise.

The application provided access to:

- Password-cracking sessions.
- Password and hash information.
- Attack options.
- Statistics and progress.
- Cracked-password results.
- Console logs and export options.

### Activity 2: PDF Password Cracking

The exercise involved a PDF password hash.

The screenshot shows the password-cracking session completed successfully.

**Observed result:**

- Hash format: PDF
- Total hashes: 1
- Successfully cracked: 1
- Remaining: 0
- Completion: 100%

<text>Recovered password:</text>

```text
[REDACTED – LAB CREDENTIAL]
```

The recovered password is intentionally excluded from this public documentation.

### Activity 3: Capturing the Lab Flag

After successfully recovering the password, I reached the lab's completion screen.

The screen displayed a congratulations message confirming that another flag had been captured.

**Flag:**

```text
[REDACTED – LAB FLAG]
```

The flag has been redacted to avoid publishing the lab's answer in a public repository.

## 2. Findings and Observations

| Area | Observation |
|---|---|
| Application | Johnny |
| Underlying tool | John the Ripper |
| Target format | PDF |
| Total hashes | 1 |
| Cracked hashes | 1 |
| Remaining hashes | 0 |
| Success rate | 100% |
| Lab outcome | Flag successfully captured |

The exercise demonstrated that a PDF password hash could be successfully recovered during the lab session.

It also highlighted the importance of wordlist selection and password complexity when evaluating password strength.

## 3. Challenges and Solutions

### Challenge 1: Selecting an Appropriate Wordlist

Password recovery depends partly on the quality and relevance of the candidate passwords supplied during an attack.

**Solution:** I explored the importance of using an appropriate wordlist and understanding how candidate passwords influence the cracking process.

### Challenge 2: Understanding Hash-Cracking Results

Interpreting the cracking results requires understanding the difference between total hashes, successfully cracked hashes and remaining hashes.

**Solution:** I reviewed the Johnny results and confirmed that the session completed with one hash cracked out of one, representing a 100% success rate.

## 4. Lessons Learned

- Johnny provides a graphical interface for John the Ripper.
- Password hashes can be tested against candidate passwords using wordlists.
- Wordlist selection can influence password recovery.
- Weak passwords are more susceptible to dictionary-based attacks.
- Hash-cracking statistics help evaluate the outcome of an attack.
- Password security requires strong and unique passwords.
- Successful password recovery demonstrates the importance of protecting password-protected documents.

## 5. Skills Developed

![Password Auditing](https://img.shields.io/badge/Password-Auditing-blue?style=flat-square)
![Hash Analysis](https://img.shields.io/badge/Hash-Analysis-orange?style=flat-square)
![Wordlists](https://img.shields.io/badge/Wordlist-Usage-green?style=flat-square)
![Security Testing](https://img.shields.io/badge/Security-Testing-red?style=flat-square)

- Password Cracking Fundamentals
- Hash Analysis
- Wordlist-Based Attacks
- Johnny GUI
- John the Ripper
- PDF Password Recovery
- Password Security Assessment
- Cybersecurity Lab Documentation

## 6. Security Recommendations

Organisations and individuals should consider the following measures:

1. Use strong, unique passwords for sensitive documents.
2. Avoid predictable words, common phrases and easily guessed passwords.
3. Use a password manager to generate and store strong passwords.
4. Protect sensitive documents with appropriate encryption.
5. Avoid sharing document passwords through insecure communication channels.
6. Review password policies and educate users about common password weaknesses.

## 7. Conclusion

This practical exercise provided hands-on experience with password cracking and hash analysis using Johnny.

I successfully completed a PDF password-cracking session, with the application reporting that one out of one hash had been cracked. I also reached the lab completion screen and captured the required flag.

The exercise strengthened my understanding of password auditing, wordlist-based attacks, hash-cracking results and the importance of strong password practices.

## 8. Ethical Use and Disclaimer

This exercise was performed in an authorised cybersecurity training environment for educational purposes.

Password-cracking techniques should only be used on files, accounts and systems that you own or have explicit permission to assess.

**Understanding how passwords are cracked is an important step towards learning how to protect them.**

