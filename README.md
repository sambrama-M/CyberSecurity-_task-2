# CyberSecurity_task-2

## Task 2: Phishing Email Investigation

---

### Objective

The goal of this task was to analyze a suspicious email and identify signs of phishing.

### Tools Used

* Sample email source: [Usecure Blog](https://blog.usecure.io/the-most-common-examples-of-a-phishing-email)
* Header analysis tool: MXToolbox SuperTool

### What the Email Looked Like

The email claimed to be from HM Revenue & Customs (HMRC), stating that the recipient was eligible for a tax refund of £209.27. It had a professional tone and no spelling or grammar mistakes, which made it look convincing at first glance. But upon closer inspection, several red flags were found.

### Phishing Indicators Identified

1. **Fake Identity**
   The sender pretended to be HMRC but used a personal Hotmail address, which is not official or trustworthy.

2. **Urgency**
   The email urged the recipient to claim the refund quickly, a common tactic to create pressure and reduce critical thinking.

3. **Suspicious Link**
   A link in the email redirected to a fake Microsoft login page, designed to steal user credentials.

4. **Generic Greeting**
   The message began with a simple "Hello" instead of addressing the recipient by name, which is a common sign of mass phishing emails.

5. **Unrealistic Offer**
   The email promised a refund without any verification, which seems too good to be true.

6. **Polished Appearance**
   Despite being fake, the email had no spelling or grammar errors, making it appear more legitimate.

7. **Credential Theft Attempt**
   The fake login page collected user details and sent them directly to cybercriminals.

### Header Analysis

Using MXToolbox, the email header appeared normal and did not show obvious signs of tampering. This highlights that phishing emails can still appear technically clean while being dangerous.

---
