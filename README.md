Issue Faced:
401 Unauthorized while sending Bearer token 

Root Cause:
API endpoint was outdated (.glitch.me) and redirected to a new domain (.click). Postman drops Authorization headers during redirects.

Fix:
Used the final endpoint https://simple-books-api.click/orders directly.
