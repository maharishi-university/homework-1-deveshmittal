[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18840477)
# MIU-Seminar-2025-03-Homework1
# Requirements
1. Set up an AWS Free Tier Account:
* If you haven’t done so, create an AWS Free Tier account at AWS Sign-Up.
* Use an email not associated with another AWS account.

2. Add MFA for the root account:
* Go to: AWS Console → IAM → Security Credentials.
* Enable MFA: Choose "Virtual MFA" and use Google Authenticator/Authy.
* Take a screenshot of the MFA setup confirmation.
![Part2.png](Part2.png)

3. Create another account and work in this account from now on:
* Go to: IAM → Users → Add User.
* Username: your-name-id.
* Attach Policy: AdministratorAccess.
* Set Console Access: Enable sign-in for this user.
* Log out from the root account and only use this IAM user from now on.
* Take a screenshot of the IAM user list.
![Part3.png](Part3.png)

4. Use your root account to create Billing Alert:
* Go to: Billing Dashboard → Preferences.
* Enable billing alerts and set up an email notification.
* Take a screenshot of the billing alert settings.
![Part4.png](Part4.png)
5. Use your root account to create Budget Alert:
* Go to: AWS Budgets → Create Budget.
* Type: Cost Budget.
* Threshold: $1 (or Free Tier limit).
* Notification: Send email alerts when spending approaches the limit.
* Take a screenshot of the budget alert setup.
![Part5.png](Part5.png)

## Submit the above screenshots.
