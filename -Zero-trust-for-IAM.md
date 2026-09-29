# Zero Trust for Identity - Never Trust, Always Verify

From Module 1 - Zero Trust Model has 3 principles. I apply them to IAM:

1. Verify Explicitly: Don't just trust password. Check MFA, location, device.
   Example: User logs in from Copenhagen, 5 min later from USA - block it.

2. Use Least Privilege Access: Give minimum access needed, not Admin for everyone.
   Example: Intern needs SharePoint? Give access to 1 folder, not whole company drive.

3. Assume Breach: Act as if attacker is already inside. So we check identity every time.
   Example: Even if user logged in yesterday, ask again today.

GRC asks "Do we follow Zero Trust?" IAM implements it with MFA and least privilege.
