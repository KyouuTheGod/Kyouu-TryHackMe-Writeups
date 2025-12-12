IDOR (Insecure Direct Object Reference)

Overview
IDOR is a common access control vulnerability where an application
allows users to access objects they do not own by manipulating identifiers.

Enumeration
- Identify parameters such as `user_id`, `account_id`, `order_id`
- Test incremental or predictable values
- Observe differences in responses

Exploitation
- Modified 'user_id' parameter in the request/ or on the URL bar
- Successfully accessed another user's data

Impact
- Sensitive information disclosure
- Possible account takeover
- Violation of user privacy

Remediation
- Enforce server-side authorization checks
- Do not trust user-supplied identifiers
- Use indirect object references
