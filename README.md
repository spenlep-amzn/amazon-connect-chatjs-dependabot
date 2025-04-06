# Automed PR for Security Vulnerability Patches (Dependadbot)

<img width="968" alt="Screenshot 2025-04-06 at 3 46 54 PM" src="https://github.com/user-attachments/assets/72ea67ba-6001-46f8-92da-d62017d99f3d" />

# One-time Setup

1. Create file: `.github/dependabot.yml`

2. Update github settings to match this:
<img width="1145" alt="Screenshot 2025-04-06 at 2 50 22 PM" src="https://github.com/user-attachments/assets/302817fb-e2f7-480c-a0c9-16f4f27c961d" />

3. (optional) Disable dependabot for Example code directories

- Delete all `package-lock.json` and `yarn.lock`
- Delete  `.github/dependabot.yml`
- Add note to README:

```md
# Security Notice
This is example code not intended for production use.
Dependencies may contain known vulnerabilities.
Please update all dependencies before using in any production environment.
```
