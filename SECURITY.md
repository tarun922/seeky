# Security Policy

## Supported Versions

Seeky is maintained by a single developer, not a team, so there isn't
capacity to backport security fixes across multiple release lines. Only the
**latest released version** gets security fixes. If you're on an older
version and a vulnerability affects you, the fix is to update — older
versions won't receive patches.

| Version        | Supported          |
| -------------- | ------------------- |
| Latest release | :white_check_mark: |
| Anything older | :x:                 |

Check the Releases page for the current version number before reporting —
if you're not on the latest, please update first and confirm the issue
still reproduces.

## Reporting a Vulnerability

**Please don't open a public issue for a security vulnerability.** This
repo is public, and a public issue describing an exploitable bug puts every
current user at risk before a fix is out.

Instead, please use GitHub's private vulnerability reporting:

1. Go to this repo's **Security** tab
2. Click **"Report a vulnerability"**
3. Describe the issue — what it affects, how to reproduce it, and its
   potential impact

This opens a private draft advisory that only you and the maintainer can
see, so details stay contained until there's a fix.

### What to include

- Affected version(s)
- Platform/OS (Windows, Linux, macOS — and installer type if relevant:
  `.exe`, `.AppImage`, `.deb`, etc.)
- Steps to reproduce, or a proof of concept if you have one
- What an attacker could actually do with it (impact), as best you
  understand it

### What to expect

This is a solo-maintained project, so there's no formal SLA, but as a
practical target:

- **Acknowledgement:** within a few days of the report
- **Status updates:** as there's progress to share — if a fix is going to
  take a while, you'll be told that rather than left waiting silently
- **If accepted:** a fix is prepared, a new release is published, and (with
  your permission) you're credited in the advisory/release notes. Public
  disclosure happens only after a fixed version is available.
- **If declined:** an explanation of why it's not considered a
  vulnerability, or why it's out of scope (e.g. it requires something
  already outside Seeky's trust boundary, like a compromised OS)

### Please don't

- Test against other people's installations or data without permission
- Publicly disclose a vulnerability before a fix has shipped
- Use automated scanners against any infrastructure beyond your own local
  install without asking first

Thanks for taking the time to report responsibly — it genuinely helps.
