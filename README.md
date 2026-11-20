 Password Cracking with John the Ripper (JTR) & Networkwalks Tools

Completed the Week 3 Cybersecurity & Ethical Hacking lab modules (**W3-PM1** & **W3-PM2**) with **Networkwalks**[cite: 18, 25].

## Overview
- **Tools Used:** John the Ripper (JTR Jumbo), Johnny GUI, Networkwalks Hash Calculator, and Networkwalks Password Cracker[cite: 4, 18, 25]
- **Objective:** Extract `$pdf$` hashes from password-protected PDF files, recover weak passwords via dictionary/cracking attacks, and capture the completion flags[cite: 2, 18, 27, 28, 29].

## Lab Results & Captured Flags

| Target / Module | Cracked Password | Captured Flag |
| :--- | :--- | :--- |
| **Target 1 (Johnny)** | `good-luck`[cite: 30] | `nw{cybersecurity_flag_captured_2608}`[cite: 27] |
| **Target 2 (Johnny)** | `password1`[cite: 31] | `nw{networkwalks_persistence_jtr_270521}`[cite: 28] |
| **Target 3 (Johnny)** | `1qaz2wsx`[cite: 32] | `nw{networkwalks_flag_260821_1}`[cite: 29] |

## Workflow Summary
1. **Hash Extraction:** Extracted the `$pdf$` hash string from each locked PDF file[cite: 8, 19, 20].
2. **Cracking:** Loaded the extracted hashes into **Johnny** (linked to `john.exe`) and tested candidate passwords to recover access[cite: 6, 11, 12, 13].
3. **Verification:** Unlocked the protected PDFs using the recovered passwords and confirmed the captured flags[cite: 14, 27, 28, 29].

## Key Takeaway
Common or predictable passwords (such as `password1`, `good-luck`, and keyboard sequences like `1qaz2wsx`) are recovered quickly when exposed to dictionary and guessing attacks—highlighting why strong, complex passwords and proper access controls matter[cite: 18, 30, 31, 32].
