# Password Security Project README

This README summarizes the activities conducted to explore password security, including generating passwords, evaluating their strength, identifying best practices, and understanding password attacks.

---

## 📌 Overview

The goal of this project was to enhance understanding of password security by:

- Creating passwords with varying complexity.
- Evaluating password strength using [PasswordMeter.io](https://www.passwordmeter.com/).
- Identifying best practices for creating strong passwords and researching common password attacks.
- Documenting findings and lessons learned.

---

## 🔐 Task 1: Generating Passwords with Varying Complexity

I generated four passwords with increasing complexity, incorporating uppercase letters, lowercase letters, numbers, symbols, and varying lengths:

- **Simple (8 characters):** `Kj9#mP2$`
- **Moderate (12 characters):** `vT7@nL#xP4qR`
- **Complex (16 characters):** `9kM$zT2&pL8#vN5j`
- **Highly Complex (20 characters):** `Qw3!rT9#kM2$vB8^nL5@`

These passwords demonstrate the importance of **length** and **character diversity** in enhancing security. Longer passwords with a mix of character types are more resistant to attacks.

---

## 🧪 Task 2: Evaluating Password Strength with PasswordMeter.io

I used PasswordMeter.io to evaluate the strength of three passwords: `"anand2222"`, `"Kj9#mP2$"`, and a complex 16-character password. The tool's criteria include:

- Minimum of 8 characters
- At least 3 out of 4 character types: uppercase, lowercase, numbers, symbols

### 🔻 Password 1: `"anand2222"`

- **Score:** 30%
- **Complexity:** Weak
- **Details:**
  - Characters: 7 (Bonus: +28)
  - Lowercase Letters: 5 (Bonus: +4)
  - Numbers: 2 (Bonus: +8)
  - Middle Numbers/Symbols: 1 (Bonus: +2)
  - Repeat Characters: 4 (Deduction: -2)
  - ❌ Missing uppercase letters and symbols

![Screenshot 2025-06-03 205722](https://github.com/user-attachments/assets/d3b506f7-388e-4a9d-9942-f0e3aab26c7f)

**Analysis:** This password is weak due to its short length, lack of uppercase letters and symbols, and use of a dictionary-style pattern.

---

### ✅ Password 2: `"Kj9#mP2$"`

- **Score:** 92%
- **Complexity:** Very Strong
- **Details:**
  - Characters: 8 (Bonus: +32)
  - Uppercase Letters: 2 (Bonus: +12)
  - Lowercase Letters: 2 (Bonus: +12)
  - Numbers: 2 (Bonus: +8)
  - Symbols: 2 (Bonus: +12)
  - Middle Numbers/Symbols: 3 (Bonus: +6)
  - Requirements Met: 5 (Bonus: +10)

![Screenshot 2025-06-03 205553](https://github.com/user-attachments/assets/765dfb1c-7f3f-4293-aa8e-acc440762187)

**Analysis:** Meets minimum criteria and uses all character types. Could still improve by avoiding potential dictionary-style patterns.

---

### ✅ Password 3: `9kM$zT2&pL8#vN5j`

- **Score:** 100%
- **Complexity:** Very Strong
- **Details:**
  - Characters: 16 (Bonus: +64)
  - Uppercase Letters: 4 (Bonus: +24)
  - Lowercase Letters: 5 (Bonus: +22)
  - Numbers: 4 (Bonus: +16)
  - Symbols: 3 (Bonus: +18)
  - Middle Numbers/Symbols: 6 (Bonus: +12)
  - Requirements Met: 5 (Bonus: +10)

![Screenshot 2025-06-03 205747](https://github.com/user-attachments/assets/29bac745-77b6-432d-9e46-d40cb8ebad56)

**Analysis:** Perfect score due to excellent length, character diversity, and randomness. Highly secure.

---

### 🔐 Best Practices

- Use at least **12–16 characters**
- Include **uppercase, lowercase, numbers, and symbols**
- **Avoid dictionary words** and predictable patterns
- Use **passphrases** (e.g., `Blue$Sky_2024!`)
- Use a **password manager** to store unique passwords
- Enable **multi-factor authentication (MFA)** wherever possible

### 🛡️ Common Attacks

- **Brute Force:** Tries all possible combinations  
  **Defense:** Use long, complex passwords and lockouts after failed attempts.

- **Dictionary Attack:** Tries common words or phrases  
  **Defense:** Avoid real words; use randomness and symbols.

**Impact of Complexity:**  
Increasing character types and length **exponentially increases** the time required to crack a password.

---

## 📚 Lessons Learned

- **Length is Critical:** Passwords with 12+ characters are significantly more secure.
- **Diversity Matters:** Using all character types boosts strength and avoids deductions.
- **Avoid Predictable Patterns:** Even complex-looking words can be vulnerable if they're in dictionaries.
- **Evaluate Regularly:** Tools like PasswordMeter.io provide actionable insights.
- **Supplement with MFA:** Passwords alone aren’t enough—MFA blocks most automated attacks.

---

## ✅ Conclusion

By generating passwords, testing them with PasswordMeter.io, and researching best practices, I’ve learned how to improve password security effectively. The findings underscore the importance of:

- Password **length**
- Character **diversity**
- **Randomness**
- Use of **MFA** and **password managers**

Together, these practices significantly enhance security in real-world applications.

---
