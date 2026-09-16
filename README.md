# turnpressure-site

The privacy policy, support and landing pages for **Turn Pressure** (iOS).

Apple requires the first two to be reachable at public URLs — a privacy policy under
Guideline 5.1.1(i) even when the app collects nothing, and a support URL on the
listing. A reviewer opens both.

- Privacy policy — `privacy.html`
- Support — `support.html`
- Landing page — `index.html`

Plain static HTML, served by GitHub Pages from `main` / root. No build step.

## This folder is the source — the GitHub repo is a publishing target

The pages live in the `turn_pressure` repository, at `turnpressure-site/`, and moved
there on 2026-08-26 because no project file lives outside the project folder. Edit them
here. `ligrimp-lang/turnpressure-site` is where they get published to, and a clone of it
is not a place to make changes — that is the drift this arrangement removes.

    .claude/skills/ship/scripts/publish-site.sh turn-pressure --dry-run   # what would change
    .claude/skills/ship/scripts/publish-site.sh turn-pressure             # commit and push

It refuses to publish uncommitted changes, so what is on the web always names a commit in
the project repository. The privacy policy text has no second copy anywhere — `privacy.html`
is it.

---

© 2026 Rustam Ismailov. All rights reserved. The text and design here are published
so Apple and users can read them, not as an open-source release.
