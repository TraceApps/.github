# Security

This covers every TraceApps repository that has no security policy of its own: NutriTrace, LiftTrace, CookTrace, NoteTrace, Fathom, and the rest.

## Reporting a vulnerability

Please report it privately, not in a public issue:

1. Open the repository the problem is in.
2. Go to the **Security** tab and choose **Report a vulnerability**.
3. Describe what an attacker can do, what they need (an account, a role, a setting), the version or commit, and the steps to reproduce.

Only the maintainer can see the report. The answer comes there, and the conversation, the fix and the advisory stay private until a release has the fix.

## What happens next

- The report is confirmed against the current development branch and the latest release.
- The fix goes to the development branch first, then into the next release.
- A GitHub security advisory is published with that release, crediting you unless you'd rather not be named.

## Supported versions

Fixes go into the next release of each app. Running the latest release is the way to get them; older versions aren't patched separately.
