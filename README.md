# LESS.

**Less scrolling. More living.**

[Open LESS.](https://linusmm-ship-it.github.io/less/)

Private screen-time challenges for friends. Open the app, choose your name, then create or join a club with its invitation code. No email, password or GitHub account is required to use the app.

On iPhone, open the link in Safari, then Share → Add to Home Screen. On Android, use the browser install option; the native Android companion APK is available in Profile.

This repository publishes the built PWA (`site.zip`). Personal profiles, measurements and screenshots are stored separately in the protected Supabase backend and are never committed here. Native Android capture needs explicit Usage Access permission. Automatic iOS capture is not enabled.

The Pages workflow verifies `SHA256SUMS` before publishing the archive. For maintenance, rebuild from the full development package with `LESS_PUBLIC_BASE=/less/ npm run build`, run `python3 scripts/package-github.py /path/to/output`, and update `site.zip` and `SHA256SUMS` together. Recovery and Web Push remain unavailable; real phone measurement/install testing is still required.
