# Phishing Email Analysis Report

## Task 2: Analyze a Phishing Email Sample

### Objective

To identify phishing characteristics present in a suspicious email and understand how attackers use social engineering techniques to deceive users.

---

## Email Details

**From:** [security-alert@amazon-verification.net](mailto:security-alert@amazon-verification.net)

**Subject:** Amazon Account Security Alert

**Email Body Summary:**
The email claims that suspicious login attempts were detected on the recipient's Amazon account. It instructs the user to verify their identity through a provided link within 12 hours to avoid account suspension.

---

## Phishing Indicators Identified

### 1. Suspicious Sender Address

The email originates from:

[security-alert@amazon-verification.net](mailto:security-alert@amazon-verification.net)

The domain "amazon-verification.net" is not owned by Amazon and is attempting to appear legitimate by including the word "Amazon".

**Risk:** Email spoofing and impersonation.

---

### 2. Urgent and Threatening Language

The email contains phrases such as:

* "Verify your account within 12 hours"
* "Permanent account suspension"

These statements create panic and pressure the recipient into acting quickly without verification.

**Risk:** Social engineering attack.

---

### 3. Suspicious URL

The email contains the following link:

https://amazon-account-secure-check.net/login

Analysis:

* Not an official Amazon domain.
* Uses Amazon's brand name to gain trust.
* Designed to redirect users to a fake login page.

**Risk:** Credential theft.

---

### 4. Generic Greeting

The email begins with:

"Dear Customer"

Legitimate organizations typically address users by their registered name.

**Risk:** Indicates a mass phishing campaign.

---

### 5. Brand Impersonation

The sender claims to represent Amazon Security Team while using an unrelated domain.

**Risk:** Identity spoofing and fraud.

---

### 6. Fear-Based Manipulation

The email warns users about unauthorized access and account suspension.

Attackers commonly use fear to influence victims into making rushed decisions.

**Risk:** Psychological manipulation.

---

## Analysis Summary

| Indicator           | Status |
| ------------------- | ------ |
| Fake Sender Domain  | Found  |
| Suspicious Link     | Found  |
| Urgent Language     | Found  |
| Generic Greeting    | Found  |
| Brand Impersonation | Found  |
| Social Engineering  | Found  |

---

## Conclusion

After analyzing the email, several phishing indicators were identified, including a spoofed sender address, fraudulent URL, urgent language, generic greeting, and social engineering tactics. The email is designed to trick users into revealing sensitive account credentials through a fake verification page.

Therefore, this email should be classified as a phishing attempt and should not be trusted.

---

## Outcome

Successfully analyzed a phishing email sample and identified common phishing techniques such as email spoofing, malicious links, urgency tactics, brand impersonation, and social engineering.
