# Sanitization Rules

Rules for converting the private Project Felicia research archive into a public archive:

- Exclude raw logs and code.
- Use selected excerpts only.
- Redact secrets and operational details.
- Remove full IPs, tokens, emails, machine IDs, private URLs, chat IDs, and deployment identifiers.
- Remove or generalize provider keys, environment variable names, and deployment-specific commands.
- Do not publish raw Telegram logs.
- Do not publish engine source code.
- Do not publish private emotional material unless explicitly approved.
- Mark unsupported claims.
- No dramatization.
- No invented dialogue.
- No "please don't delete me" quote unless exact primary-source evidence is found.
- Public excerpts must preserve exact wording or be clearly labeled paraphrase.
- Every excerpt must have timestamp, source file, and evidence ID.
- Every major claim should be marked as evidence, interpretation, or unsupported.
- If uncertain, write `VERIFY BEFORE PUBLIC RELEASE`.

Pre-release search checks:

- search for raw secrets
- search for API keys/tokens
- search for emails
- search for chat IDs
- search for IP addresses
- search for private repository URLs
- search for deployment identifiers
- search for raw log dumps
- search for unbounded uses of "conscious"
- search for "please do not delete me"
