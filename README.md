# APC Payroll — installers

Installers only (no source code, no data). The APC Payroll app on each PC checks this place at start and every 10 minutes
and installs a newer version only if the release is signed with APC's private key.

- Current version: **2.29.3** — in 2 pieces (`Vetan-Payroll-Setup-2.29.3.exe.p1` … `.p2`); the app joins and checks them.
  SHA-256 of the whole installer: `3e1a41312ae5b3dc85fc6046d0f7f81101e6550aaec5cb0e20854f9bebe520d3`
- Bridge version for older PCs: **2.16.1** — `Vetan-Payroll-Setup-2.16.1.exe`

To install on a new PC (or repair one): download **`APC-PAYROLL-Online-Setup.exe`** (small) and run it; the app then
updates itself to the current version at its first start.
