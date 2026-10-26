# Accessibility

Seeky is a personal/independent project, built and maintained by a single
developer rather than a company or team. Accessibility work here is
genuinely best-effort — this document is meant to be honest about where
things stand today, not to make promises the project can't back up, so that
anyone who hits a barrier knows what to expect and how to report it.

This covers what the app currently supports, what hasn't been tested, and
how to tell us about a problem.

## Priorities

Seeky does not currently target or claim conformance with any WCAG level.
No formal accessibility evaluation has been done, so nothing here should be
read as a conformance claim — it's a description of what's been built and
tested informally during normal development, not an audit result.

Where attention has gone so far:

- **Keyboard support in the video player** — the player is usable without a
  mouse: play/pause, seek, volume, fullscreen, mute, and next/previous all
  have keyboard shortcuts, and the hero carousel on the home screen supports
  keyboard navigation too.
- **Subtitle/caption tracks for video content** — where a stream provides
  them, they can be selected and displayed.

Areas that have **not** been specifically prioritized or tested yet:
screen reader compatibility, color contrast across all of the app's
themes, and keyboard access to every screen (several newer screens and
modals have not been audited for this).

## Contributor expectations

This project does not currently have automated accessibility checks (no
axe-core/Lighthouse CI step, no linting for contrast or ARIA, etc.) in its
build pipeline. That's a gap, not a deliberate choice, and may change.

If you're contributing a user-facing change: please check that anything
interactive (buttons, menus, the new screen or modal you added) can be
reached and operated with Tab/Shift+Tab and Enter/Space before opening a
PR, and mention in the PR description if you tested with a screen reader
or at higher-than-default zoom. This isn't enforced by CI today — it's a
request, not a gate.

## Reporting accessibility issues

If something in Seeky is hard or impossible to use because of how it's
built, please open an issue. You do not need to disclose a disability or
explain why you're asking — just describe the barrier.

Helpful (all optional) context:

- What you were trying to do, and where (which screen/feature)
- What happened vs. what you expected
- OS and Seeky version
- Any assistive technology involved (screen reader + version, switch
  device, etc.) and browser/Electron version if relevant
- A screenshot or short recording, if it helps show the problem

### Severity

This project doesn't use formal severity labels yet. In practice, issues
that **block** a task entirely (e.g. a screen that can't be reached by
keyboard at all) get looked at before ones with a workaround (e.g. a label
that's missing for a screen reader but the control still works). If you
think something is blocking, say so plainly in the issue — that's enough,
you don't need to self-assign a label.

### How we respond

As a solo-maintained project, there's no guaranteed response time. What you
can expect:

- An acknowledgement on the issue once it's seen
- Honesty if something can't be fixed soon, including a workaround if one
  exists
- A comment on the issue when a fix ships, so you can verify it

## Ownership and maintenance

Seeky is maintained by one developer (the repo owner). There is no separate
accessibility team or role — accessibility issues go through the same
process as any other bug report, triaged by the maintainer.

## Supported environments

Seeky is an Electron desktop app, distributed for Windows, Linux
(AppImage/deb/pacman/rpm), and macOS.

- **Keyboard:** supported for the video player and home-screen carousel, as
  noted above; not yet audited across every screen.
- **Screen readers:** not currently tested with any screen reader (NVDA,
  JAWS, VoiceOver, Orca, etc.). It may partially work by virtue of using
  standard HTML elements in places, but this is unverified.
- **Pointer/touch:** mouse and trackpad are the primary tested input;
  touch input has not been specifically tested.
- **Display scaling/zoom:** not specifically tested at non-default OS scale
  settings or browser-level zoom.

If you've tried Seeky with a specific assistive technology or input method
not listed here, a report (good or bad) is genuinely useful.

## Known limitations

Based on informal testing rather than a full audit, known gaps include:

- No screen reader testing has been done, so screen reader support across
  the app is unverified and likely inconsistent.
- Several newer screens (e.g. anime browsing, My List, Settings panels)
  have not been checked for full keyboard reachability.
- Color contrast has not been checked across all of Seeky's themes (Powder
  Blue Breeze, Golden Hour, Arctic Pearl, Cosmic Void, Midnight Aurora, and
  others) — some theme/text combinations may not meet common contrast
  guidelines.
- No workaround is currently documented for the above; if you find one that
  works for you, please share it in an issue so it can be added here.

This list reflects what's been noticed or not yet tested, not a complete
inventory — if you hit something not listed here, please report it.

## Feedback and improvements

Suggestions for improving this document, or for how Seeky handles
accessibility generally, are welcome via a regular issue. If you're
reporting an active barrier rather than suggesting a process change, please
use the reporting steps above so it gets triaged correctly.
