# Password Strength Testing with PasswordMeter.io

This README documents the process of testing password strength using [PasswordMeter.io](https://www.passwordmeter.com/). I evaluated two passwords of varying complexity: a simple password (`"password"`) and a slightly more complex one (`"exceptional"`). The results, including scores and complexity ratings, are detailed below, along with references to the evaluation screenshots.

---

## Password Testing Process

I used PasswordMeter.io to assess the strength of two passwords. The tool evaluates passwords based on criteria such as length, character types (uppercase, lowercase, numbers, symbols), and patterns (e.g., repeated characters). The minimum requirements for a strong password on this tool are:

- At least 8 characters in length.
- Contains at least 3 out of 4 character types: uppercase letters, lowercase letters, numbers, and symbols.

---

## Password 1: `"password"`

**Input:** `anand2002`

**Evaluation:**

- **Score:** 30%
- **Complexity:** Weak

**Details:**
- Number of Characters: 7 (Bonus: +28)
- Lowercase Letters: 5 (Bonus: +4)
- Numbers: 2 (Bonus: +8)
- Middle Numbers or Symbols: 1 (Bonus: +2)
- Repeat Characters (Case Insensitive): 4 (Deduction: -2)
- Missing uppercase letters and symbols, leading to a low score.
- Does not meet the "Requirements" bonus (needs 3/4 character types).
![Screenshot 2025-06-03 205722](https://github.com/user-attachments/assets/b3e6e90f-a424-4d9a-b6d2-dc66a6787b07)


**Analysis:**  
The password `"password"` is weak because it lacks uppercase letters and symbols, is only 7 characters long (below the minimum 8), and contains predictable patterns (a dictionary word). It only uses lowercase letters and numbers, failing the requirement of 3/4 character types.

---

## Password 2: `"exceptional"`

**Input:** `Kj9#mP2$`

**Evaluation:**

- **Score:** 92%
- **Complexity:** Very Strong

**Details:**
- Number of Characters: 8 (Bonus: +32)
- Uppercase Letters: 2 (Bonus: +12)
- Lowercase Letters: 2 (Bonus: +12)
- Numbers: 2 (Bonus: +8)
- Symbols: 2 (Bonus: +12)
- Middle Numbers or Symbols: 3 (Bonus: +6)
- Requirements: 5 (Bonus: +10, meets 3/4 character types)

![Screenshot 2025-06-03 205553](https://github.com/user-attachments/assets/c9eb9e4d-8ceb-465f-bb18-95b736619966)

**Analysis:**  
The password `"exceptional"` scores much higher because it meets the minimum length (8 characters) and includes uppercase letters, lowercase letters, numbers, and symbols. It satisfies the requirement of having at least 3 out of 4 character types, earning the "Requirements" bonus. However, it could be improved by increasing length and avoiding dictionary words to reach 100%.

---

## Password 3: (Complex Password)

**Input:** *9kM$zT2&pL8#vN5j*

**Evaluation:**

- **Score:** 100%
- **Complexity:** Very Strong

**Details:**
- Number of Characters: 16 (Bonus: +64)
- Uppercase Letters: 4 (Bonus: +24)
- Lowercase Letters: 5 (Bonus: +22)
- Numbers: 4 (Bonus: +16)
- Symbols: 3 (Bonus: +18)
- Middle Numbers or Symbols: 6 (Bonus: +12)
- Requirements: 5 (Bonus: +10, meets 3/4 character types)

![Screenshot 2025-06-03 205614](https://github.com/user-attachments/assets/31e84695-6846-42c3-a57f-a24d1b497ba6)

**Analysis:**  
This password achieves a perfect score because it is long (16 characters) and includes a balanced mix of uppercase letters, lowercase letters, numbers, and symbols. It meets all requirements and avoids deductions, making it highly resistant to attacks.

---

## Screenshots

The following screenshots were captured during the evaluation:

- `password-evaluation-30percent.png`: Shows the evaluation of the password `"password"` with a score of 30% and "Weak" complexity.
- `exceptional-evaluation-92percent.png`: Shows the evaluation of the password `"exceptional"` with a score of 92% and "Very Strong" complexity.
- `complex-evaluation-100percent.png`: Shows the evaluation of a complex password with a score of 100% and "Very Strong" complexity.

---

## Key Takeaways

- **Password length and diversity in character types are critical for a high score.**
- **Dictionary words** (e.g., `"password"`, `"exceptional"`) should be avoided to prevent vulnerability to dictionary attacks.
- **Including at least 3 out of 4 character types** (uppercase, lowercase, numbers, symbols) is necessary to meet PasswordMeter.io's requirements for a strong password.
- **Longer passwords with random characters** significantly improve strength, as seen in the 100% score for the complex password.
