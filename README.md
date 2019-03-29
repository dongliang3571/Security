# Security

### CSRF (Cross Site Request Forgery)

CSRF is an attack that forces an end user to execute unwanted actions on a web application in which he/she is currently authenticated. With a little help of social engineering (like sending a link via email or chat), an attacker may force the users of a web application to execute actions of the attacker's choosing. A successful CSRF exploit can compromise end user data and operation, when it targets a normal user. If the targeted end user is the administrator account, a CSRF attack can compromise the entire web application.

CSRF relies on the following:

Web browser behavior regarding the handling of session-related information such as cookies and http authentication information
Knowledge by the attacker of valid web application URLs
Application session management relying only on information which is known by the browser
Existence of HTML tags whose presence cause immediate access to an http[s] resource; for example the image tag img

https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.md

https://stackoverflow.com/questions/16049721/how-is-using-synchronizer-token-pattern-to-prevent-csrf-safe

https://security.stackexchange.com/questions/157061/how-does-csrf-correlate-with-same-origin-policy
