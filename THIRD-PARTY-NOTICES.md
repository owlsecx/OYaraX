# Third-Party Notices — OYaraX

This tool is distributed as a single pre-built executable. It bundles the
third-party components listed below. Each component remains the property of
its respective copyright holders and is used under its own license, whose
full text is reproduced in this file.

**Owlsec LLC's own source code is proprietary and is not covered by any of
the licenses below.** Those licenses apply only to the third-party components
named here.

- Tool binary: `OYaraX`
- SHA-256: `dfd5f5eb240abe8ae990f3c7c15305d0db8108743d72f562f132e683ba7adcee`
- Bundled interpreter: CPython 3.11 (PSF License)
- Generated: 2026-11-24
- Machine-readable inventory: see `SBOM.cdx.json` in this repository

## Components

This tool bundles **no third-party Python packages**. It uses only the Python
standard library and the CPython interpreter.

| Component | Version | License |
|---|---|---|
| CPython | 3.11 | PSF-2.0 |
| Python standard library | 3.11 | PSF-2.0 |

The CPython interpreter and standard library are distributed under the Python
Software Foundation License. Full text: <https://docs.python.org/3/license.html>

Shared system libraries from Debian (for example `libssl`, `libz`, `libbz2`)
are bundled unmodified by PyInstaller. Each is governed by its own license as
shipped by the Debian project; see `/usr/share/doc/<package>/copyright` in
Debian, or the Debian source packages for the exact versions listed in
`SBOM.cdx.json`.
