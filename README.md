# Pi-hole + La Libre Belgique (lalibre.be) — Fix for subscription/authentication

If the newspaper La Libre Belgique displays limited content (visitor without subscription) when Pi-hole is active, the problem is usually due to the blocking of Piano domains (paywall/authentication).

Whitelisting Piano domains fixes subscription recognition.

---

## Quick answer:
Whitelist all Piano subdomains:
- piano.io
- lalibre.be (if you still have issue)

## Detailed answer:
- Go to 'Domain management'
- Add a new Regex filter
- Regular expression 'piano.io'
- Click on 'Add to allowed domains'

- Do the same with 'lalibre.be' if you still have issue.


