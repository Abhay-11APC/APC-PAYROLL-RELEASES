# APC Payroll — installers

Installers only (no source code, no data). The APC Payroll app on each PC checks this place at start and every 4 hours
and installs a newer version by itself when it is closed — only if the release is signed with APC's private key.

- Current version: **2.23.0** — in 2 pieces (`Vetan-Payroll-Setup-2.23.0.exe.p1` … `.p2`); the app joins and checks them.
  SHA-256 of the whole installer: `e5b1955270fc15e3aed1586eb9e623138629f4e1c2cd17b81decf0c93fb82668`
- Bridge version for older PCs: **2.16.1** — `Vetan-Payroll-Setup-2.16.1.exe`

To install on a new PC (or repair one): download **`APC-PAYROLL-Online-Setup.exe`** (small) and run it; the app then
updates itself to the current version at its first start.
