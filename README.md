# AWS Root Account MFA Hardening

![AWS](https://img.shields.io/badge/Cloud-AWS-orange)
![Security](https://img.shields.io/badge/Focus-Cloud%20Security-blue)
![MFA](https://img.shields.io/badge/Authentication-MFA-green)

## 📌 Project Overview
This project demonstrates the implementation of Multi-Factor Authentication (MFA) for an AWS root user.

MFA adds an extra layer of security by requiring an authenticator code in addition to the account password.

## 🎯 Objectives
- Improve AWS root account security.
- Enable MFA using an authenticator application.
- Verify the MFA sign-in process.
- Review MFA status in the AWS console.

## 🛠️ Tools & Technologies
| Tool | Purpose |
|---|---|
| Amazon Web Services (AWS) | Cloud platform |
| AWS Management Console | Account security configuration |
| Authenticator App | Time-based one-time password (TOTP) |

## 🔐 Authentication Flow

```text
User
  |
  v
AWS Sign-in Page
  |
  v
Password Verification
  |
  v
MFA Code Verification
  |
  v
AWS Console Access
```

## ⚙️ Implementation Steps
1. Opened the AWS Management Console.
2. Reviewed the root user MFA recommendation.
3. Registered an authenticator device.
4. Completed the MFA verification challenge.
5. Verified access to the AWS Console.
6. Checked the MFA status in the IAM dashboard.

## 🛡️ Security Best Practices
- Enable MFA for the AWS root user.
- Do not share passwords or MFA codes.
- Never publish MFA QR codes or secret keys.
- Keep account security screenshots free of sensitive information.
- Use the root account only when necessary.

## 📸 Project Evidence
Screenshots are available in the repository.

- IAM Dashboard
- 1. [IAM Dashboard](01-IAM-Dashboard.png)
- Root MFA Recommendation
- 2. [Root MFA Recommendation](02-Root-MFA-Recommendation.png)
- MFA Device Registration
- 3. [MFA Device Name](03-MFA-Device-Name.png)
- MFA Verification
- 4. [Root MFA Challenge](06-Root-MFA-Challenge.png)
- Console Access Verification
- 5. [Console Home Verified](07-Console-Home-Verified.png)
- IAM MFA Status
- 6. [IAM MFA Enabled](08-IAM-MFA-Enabled.png)


## 📚 Learning Outcomes
Through this project, I learned:
- The importance of MFA in cloud security.
- How authenticator-based MFA works.
- How to review account security settings in AWS.
- Why sensitive authentication information must remain private.

## ⚠️ Disclaimer
This project was completed for educational purposes in an AWS environment. No unauthorized access or testing was performed.

