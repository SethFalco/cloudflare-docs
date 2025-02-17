---
_build:
  publishResources: false
  render: never
  list: never
---

You can now configure an [Access policy](/cloudflare-one/policies/access/) to control who can connect to your application.

1. Enter any name for your rule.

2. Specify a policy [action](/cloudflare-one/policies/access/#actions).

3. Assign [Access groups](/cloudflare-one/identity/users/groups/) to reuse existing rules, or create new rules. You can add as many include, exception, or require statements as needed.

4. (Optional) Customize the login experience for users who match this policy:

   - [Purpose justification](/cloudflare-one/policies/access/require-purpose-justification/)
   - [Temporary authentication](/cloudflare-one/policies/access/temporary-auth/)

5. Select **Next**.
