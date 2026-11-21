# APC Payroll — installers

Installers only (no source code, no data). The APC Payroll app on each PC checks this place at start and every 4 hours
and installs a newer version by itself when it is closed — only if the release is signed with APC's private key.

- Current version: **2.26.2** — in 2 pieces (`Vetan-Payroll-Setup-2.26.2.exe.p1` … `.p2`); the app joins and checks them.
  SHA-256 of the whole installer: `64c06841f573e34f6bb8e5cd65548f20fe64f142b80cc6c612ca054262e67727`
- Bridge version for older PCs: **2.16.1** — `Vetan-Payroll-Setup-2.16.1.exe`

To install on a new PC (or repair one): download **`APC-PAYROLL-Online-Setup.exe`** (small) and run it; the app then
updates itself to the current version at its first start.
