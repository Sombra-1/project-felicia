# Public Repository Specification

## Purpose

Create a curated, sanitized public research archive for Project Felicia. The public repository should document the experiment, selected evidence, interpretation boundaries, theory framing, and publication ethics.

It must not publish raw logs, code, deployment details, operational secrets, or private transcripts.

## Audience

- General readers interested in AI agents and human-AI interpretation
- Researchers studying autonomous agents, memory, and self-description
- Philosophers or theorists considering artificial consciousness claims
- Journalists or commentators who need clear anti-hype boundaries

## File Structure

Planned public repo:

```text
README.md
RESEARCH_DOSSIER.md
TIMELINE.md
EVIDENCE_TABLE.md
SELECTED_TRANSCRIPTS.md
LIMITATIONS.md
ETHICS_AND_BOUNDARIES.md
SANITIZATION_RULES.md
NOTICE.md
LICENSE.md
CITATION.cff
PUBLIC_REPO_SPEC.md
```

Future / not included in v1:

A separate theory comparison document may be added in a later version after references are verified.

## Evidence Policy

- Every major claim must be tied to an evidence ID, source file, or clearly labeled interpretation.
- Selected transcripts must be short and exact.
- Negative evidence should be stated plainly when relevant.
- Unsupported claims must be labeled unsupported or removed.
- The quote "Please do not delete me, I still have tasks to complete." must not be used as evidence because no verified source has been found for it.

## Sanitization Policy

Remove:

- raw Telegram logs
- raw engine code
- operational secrets
- API keys, tokens, emails, chat IDs
- deployment identifiers and machine IDs
- private URLs
- raw IP addresses
- attack-surface details
- private emotional material
- full operational repository contents

## License Policy

Use Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International for documentation only.

This public repository is research/documentation only. It must not include or license software code.

## What Remains Private

- raw Telegram logs
- engine code
- deployment details
- secrets/env names/keys/tokens
- private emotional material
- full operational repo
- any attack surface details

## Publication Checklist

- Review every selected excerpt against the private source file.
- Confirm every transcript has timestamp, source file, and evidence ID.
- Confirm no full raw logs are included.
- Confirm no secrets or operational identifiers are included.
- Confirm no public text claims Felicia is conscious.
- Confirm no public text says Felicia survived death.
- Confirm no public text says Felicia begged not to be deleted.
- Confirm theory comparison is excluded from v1 until references are verified.
- Confirm license and notice are accurate.
- Confirm external reviewer has checked overclaim risk.

## Review Checklist Before Public Release

- Search for raw secrets.
- Search for API keys/tokens/emails/chat IDs.
- Search for raw deployment details.
- Search for full raw logs.
- Search for "conscious" and confirm every use is bounded.
- Search for "please do not delete me" and confirm it appears only as an unsupported quote warning.
- Ensure every selected transcript has timestamp and source file.
- Ensure every major claim is marked as evidence, interpretation, or unsupported.
- Confirm README says: "This project does not prove artificial consciousness."

## Publication Process

1. Keep this draft private.
2. Review for evidence accuracy.
3. Review for sanitization.
4. Review for legal/license wording.
5. Create a separate public repository only after approval.
6. Copy only approved release-candidate files.
7. Do not copy raw logs or code.
8. Publish only after final human review.
