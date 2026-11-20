# WK2-networkwalks-password-security-auditing-lab
Hands-on cybersecurity lab exploring PDF password recovery, hash extraction, dictionary attacks, and password auditing using John the Ripper, Johnny, and Networkwalks tools.

## Methodology

This exercise involved two different password-recovery approaches: John the Ripper with Johnny, and the Networkwalks password-cracking tools.

Both approaches were used to perform the hash-related operations and recover the password of the authorized protected PDF file.

### 1. Installation and Configuration
Downloaded and configured John the Ripper and Johnny on Windows. Configured Johnny to locate the John the Ripper executable.

### 2. Hash Calculation and Extraction
Used the Networkwalks Hash Calculator and the PDF hash extraction process to obtain and examine the hash associated with the protected PDF.

### 3. Dictionary-Based Password Recovery
Used the Networkwalks Password Cracker to perform a dictionary attack against the extracted hash.

### 4. John the Ripper Password Recovery
Loaded the extracted PDF hash into Johnny and initiated password recovery using John the Ripper.

### 5. Comparative Testing
Performed the password-recovery exercise using both approaches. Both tools were used to carry out the corresponding hash-related and password-recovery operations, demonstrating two different interfaces and implementations of password auditing.

### 6. Verification
Used the recovered password to open the protected PDF and confirm successful recovery.

## Key Learning Outcomes

- Gained practical experience with John the Ripper and Johnny.
- Explored hash calculation and PDF password-hash extraction.
- Practiced dictionary-based password attacks.
- Compared two different password-recovery tools and workflows.
- Understood how candidate passwords are tested against extracted password hashes.
- Learned why weak and predictable passwords are vulnerable to offline password attacks.
- Improved understanding of password security and the importance of strong passwords.

## Conclusion

This practical exercise provided hands-on exposure to password auditing and offline password recovery.

Using John the Ripper and Networkwalks password-cracking tools demonstrated how different tools can perform similar password-recovery operations.

The exercise reinforced the importance of strong passwords, appropriate encryption mechanisms, and secure handling of sensitive files.

## Ethical Considerations

All testing was conducted for educational purposes using an authorized lab file. Password-cracking tools should only be used against files and systems for which explicit permission has been obtained.

