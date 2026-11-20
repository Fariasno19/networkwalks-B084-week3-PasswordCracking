# networkwalks-B084-week3-PasswordCracking

## Overview
---
This project focuses on understanding password security and exploring how password-auditing tools can be used to evaluate the strength of passwords protecting PDF files.
The hands-on exercise involved retrieving password-verification information from an encrypted PDF document and using a password list to evaluate potential password combinations.

PDF passwords are not stored as plain, readable text. Instead, PDF security relies on password-derived verification data and encryption to restrict unauthorized access. Depending on the PDF format and encryption method, specialized tools can extract the necessary security information for offline password auditing.

---
## Objectives

- Understand the key differences between encryption and hashing.
- Explore how password-auditing and recovery tools operate.
- Learn how dictionary-based attacks evaluate commonly used password combinations.
- Recognize the security risks associated with weak, simple, and predictable passwords.
- Understand the importance of creating strong passwords to protect sensitive documents.

  ---
  ### Tools covered in the session

- **John the Ripper (JtR Jumbo):** A command-line password-auditing tool that supports different password hash and encrypted-file formats.
- **Johnny GUI:** A graphical interface for John the Ripper.
- **Networkwalks Hash Calculator and Password Cracker:** Browser-based tools used for the practical exercise.

  ---
 ## What I did

During the practical exercise, I completed the following tasks:

1. Used a password-protected PDF document supplied for the training session.
2. Retrieved the PDF's password-verification information using the provided extraction tool.
3. Imported the extracted security data into a password-auditing tool.
4. Used a prepared password list to test different possible password combinations.
5. Successfully identified the password for the training document and confirmed it by opening the PDF.

---
## Key Takeaways

This practical exercise provided a better understanding of how PDF password-protection mechanisms work and demonstrated the importance of maintaining strong password security.

Some important security practices include:

- Creating long and unique passwords.
- Avoiding commonly used words and predictable password combinations.
- Not reusing the same password across multiple accounts.
- Enabling multi-factor authentication (MFA) whenever available.

 Following these practices helps strengthen account protection and reduce the risk of unauthorized access to sensitive information.

  ---

  ## Ethical Considerations

This activity was conducted strictly for educational purposes using a PDF document provided for the training exercise.

Password-recovery and auditing tools should only be used on documents, accounts, or systems that you own or have received explicit authorization to assess. Responsible and ethical use of security tools is essential when performing cybersecurity-related activities.
