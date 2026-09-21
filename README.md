# PRIME ScreenCam — Releases

Compiled binaries and installers for [PRIME ScreenCam](https://github.com/Zhikeyev/prime-screencam)
(closed-source; that repo is private).

This repo exists only so `screencam`'s own background auto-updater
(`internal/update`) has a public, unauthenticated place to check for and
download new versions — GitHub Releases inherit their source repo's
visibility, and the source repo is private, so releases live here instead.

Every release asset is listed in that release's `SHA256SUMS.txt` — the
updater refuses to install anything that doesn't match.

Don't file issues or PRs here; there's no code in this repo to review.
