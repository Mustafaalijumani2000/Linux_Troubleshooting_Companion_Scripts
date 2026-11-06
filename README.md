# Linux Troubleshooting the Automated Way — Companion Scripts

**Author: MAG JUMANI**

This repository accompanies the 300-page paperback *Linux Troubleshooting the Automated Way*.

## Companion package

The companion archive is **`Companion_Scripts.zip`**. It contains 40 incident-specific Bash scripts, the OS-specific runbook dispatcher (`scripts/os_specific_runbooks.sh`), a Python visual email report generator (`scripts/health_report.py`), and a sample HTML report.

**Download status:** The archive must be added to this public repository before the book's QR code and repository URL provide access to the scripts.

After the archive has been uploaded, download the ZIP, extract it, and read `scripts/README.md` before executing any script.

## Supported Linux versions

Ubuntu 20.04 / 22.04 / 24.04 LTS; Oracle Linux 7 / 8 / 9; Red Hat Enterprise Linux 7 / 8 / 9.

## Safety and usage

These are diagnostic helpers, **not automated remediation utilities**. Test in disposable virtual machines first. Operating-system updates, installed tools, access permissions, and service configurations differ. Verify each command on your actual release. Do not commit credentials or private reports containing host information.

Copyright © 2026 MAG JUMANI.
