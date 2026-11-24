# NETWORKWALKS-B084-ASA-WK3-PM1-PM2-Password-Recovery-With-JTR_And_NW_tools

# Password Auditing with John the Ripper and Johnny

## Overview
This repository documents the use of John the Ripper (JTR) and Johnny (GUI) to assess password strength in a controlled and authorized environment.  The project demonstrates how weak passwords can be identified through password auditing techniques and highlights the importance of implementing strong password security practices.

## Objectives

- Understand password auditing methodologies.
- Learn how John the Ripper performs password recovery against password hashes.
- Utilize Johnny as a graphical interface for John the Ripper.
- Evaluate the effectiveness of password complexity requirements.
- Understand defensive measures against password-cracking attacks.

## Cybersecurity Domain

This project falls within the following cybersecurity disciplines:

- Ethical Hacking
- Penetration Testing
- Password Auditing
- Offensive Security (OffSec)
- Security Assessment

## Tools Used

### John the Ripper (JTR)

John the Ripper is an open-source password auditing and recovery tool used to identify weak credentials through various cracking techniques.

### Johnny

Johnny is a graphical user interface (GUI) for John the Ripper that simplifies password auditing and result analysis.


### NetworkWalks Tools

This are web-based tools developed by NetworWalks, 1st one computes a hash value of a locked file and the second one the Password Cracker, is used to find the real password from that hash.

## Methodology

### Phase 1: Preparation

- Install John the Ripper and Johnny.
- Obtain password hashes from authorized test systems.
- Verify that all testing activities are approved.

### Phase 2: Password Audit

- Load password hashes into John the Ripper.
- Configure appropriate cracking modes.
- Execute password auditing procedures.
- Monitor progress and collect results.

### Phase 3: Analysis

- Identify successfully recovered passwords.
- Evaluate password complexity and patterns.
- Determine security weaknesses.
- Recommend remediation measures.

## Key Findings

The project demonstrates that:

- Weak passwords are vulnerable to password recovery attacks.
- Dictionary-based passwords are easier to crack.
- Password complexity significantly improves resistance.
- Secure password storage practices are essential.
- Multi-Factor Authentication (MFA) provides additional protection.

## Security Recommendations

- Enforce strong password policies.
- Implement MFA wherever possible.
- Use unique passwords for each service.
- Store passwords using strong hashing algorithms.
- Conduct periodic password audits.

## Lessons Learned

The primary lesson learned is that password strength has a direct impact on organizational security. Password auditing tools can help security professionals identify weak credentials before they are exploited by attackers.

## Ethical Considerations

All testing should be conducted only on systems for which explicit authorization has been obtained. Unauthorized password-cracking activities may violate organizational policies and applicable laws.

## Skills Demonstrated

- Password Auditing
- Security Analysis
- Penetration Testing Fundamentals
- Linux Tool Usage
- Security Reporting
- Risk Assessment

## Author

Asa Phafoli

## License

This repository is intended for educational and authorized security testing purposes only.
