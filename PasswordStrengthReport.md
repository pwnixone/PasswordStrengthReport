# Password Strength Evaluation Report

## Objective
The objective of this report is to analyze the strength of passwords generated with different character complexities. Each password was tested using an online password strength checker to understand which factors contribute most to secure password creation.

## Password Samples

| Password              | Length | Uppercase | Lowercase | Numbers | Symbols | Strength Rating | Estimated Crack Time |
|-----------------------|--------|-----------|-----------|---------|---------|-----------------|----------------------|
| FFG0xQIyl0Z H         | 12     | Yes       | Yes       | Yes     | No      | Strong          | 3 years              |
| w;G_?71lm(cA          | 12     | Yes       | Yes       | Yes     | Yes     | Strong          | 3 years              |
| MLHHHIYQMOUX          | 12     | Yes       | No        | No      | No      | Strong          | 11 months            |
| D4sOaNHi9b2b          | 12     | Yes       | Yes       | Yes     | No      | Strong          | 3 years              |
| qwer@1234             | 9      | No        | Yes       | Yes     | Yes     | Weak            | 17 minutes           |

## Screenshots of Strength Tests
- Password `w;G_?71lm(cA` (complex, mixed types): ![Screenshot-2025-10-03-212552.jpg](screenshots/Screenshot-2025-10-03-212552.jpg)
- Password `qwer@1234` (short, common pattern): ![Screenshot-2025-10-03-211626.jpg](screenshots/Screenshot-2025-10-03-211626.jpg)
- Password `MLHHHIYQMOUX` (uppercase only): ![Screenshot-2025-10-03-211341.jpg](screenshots/Screenshot-2025-10-03-211341.jpg)
- Password `FFG0xQIyl0Z H` (mixed case, digits): ![Screenshot-2025-10-03-211403.jpg](screenshots/Screenshot-2025-10-03-211403.jpg)
- Password `D4sOaNHi9b2b` (mixed case, digits): ![Screenshot-2025-10-03-211538.jpg](screenshots/Screenshot-2025-10-03-211538.jpg)

## Analysis and Best Practices

- Passwords including uppercase, lowercase, numbers, and symbols with at least 12 characters rate highest in strength and crack time.
- Using only uppercase or lowercase letters with no digits or symbols reduces strength despite length.
- Short passwords or common sequences drastically reduce crack time and should be avoided.
- Symbols significantly increase complexity and thus password security.
- Password managers help generate and store complex passwords which are difficult to guess or brute-force.

## Common Password Attacks

- **Brute Force Attacks:** Try every possible combination of characters until the password is found; more complexity and length exponentially increase time to crack.
- **Dictionary Attacks:** Use common words, phrases, or leaked password lists to guess passwords; complex passwords with no dictionary words resist these attacks better.

## Conclusion

Strong password creation relies on length and diversity of character sets. Combining uppercase, lowercase, numbers, and symbols along with sufficient length creates more secure passwords. Password managers are recommended to handle complex passwords without compromising memorability.

---

*This report was generated as part of a cybersecurity task to evaluate password strengths using online tools and to learn best password creation practices.*
