# CLAUDE.md

This public repository holds the builds of **Ancient Warriors: Order of the Seal** as
**GitHub Releases** and nothing else: the game's code is in the private repository
`Lusiy321/ancient_warrior`, the website in `Lusiy321/acient-warriors-web`. Release files
cannot be downloaded from a private repository by anybody but its owner — that is why
this one exists.

- **The tree is the README, this file and two git settings — nothing more.** Builds are
  100+ MB and never go into git (GitHub refuses a file over 100 MB, and a smaller one
  stays in the history for good); they are release assets, attached on github.com —
  GitHub Desktop cannot make a release. `.gitignore` keeps `*.zip`, `*.apk`, the split
  parts (`*.zip.*`) and `.DS_Store` out of a commit, which Desktop would otherwise offer.
  A 77 MB zip committed by hand was taken out of the history with a force push on
  13 October 2026, before the first release tag pointed into it — the only cheap moment.
- **Every release is `vX.Y.Z`** (the game's `application/config/version` with a `v`) and
  carries files under **fixed names**: `ancient-warriors-windows.zip` (the .exe, the .pck
  and the SQLite DLL of a release export) and `ancient-warriors.apk` (the signed universal
  APK from Play Console's App bundle explorer — never a debug build, see
  `docs/android_release_setup.md` in the game repository). The website's download page
  looks for exactly these names, and `latest/download/<name>` always gives the newest.
- **A cloud session cannot create or edit releases** (the session's GitHub proxy answers
  403 "not permitted for this session type"), so the owner publishes them — by hand or
  with `tools/release.py upload` in the game repository. Afterwards
  `python3 tools/release.py manifest` there, the site exporter and a commit of the site
  put the release into the page's HTML; the page also finds it by itself in the browser.
- Questions and bug reports from players come in as **Issues** here: the legal texts and
  the site point at this repository's Issues as the developer's contact for now.
- The README is bilingual (Russian first, then English), like the site. Keep its file
  names, links and install notes in step with the site's download page.
