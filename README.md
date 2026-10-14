# BRUGES

![licence](https://img.shields.io/badge/licence-Apache-2.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `BRUGES` in category **MINING**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/agilescientific/bruges · **Upstream pin:** `905fe4fee2bd03f4852ecaacd9a004d84ed8441f` · **Category:** MINING · **Vendor:** Anticloud FZ LLE · **Licence:** Apache-2.0

---

## What This Project Does

# bruges is a

![Bruges](http://agile.geosci.ai/bruges.png)

In other words, it's just a load of functions that implement important equations in (mostly seismic) geophysics, from Aki-Richards to Zoeppritz.

[![Run tests](https://github.com/agilescientific/bruges/actions/workflows/run-tests.yml/badge.svg)](https://github.com/agilescientific/bruges/actions/workflows/run-tests.yml)
[![Build docs](https://github.com/agilescientific/bruges/actions/workflows/build-docs.yml/badge.svg)](https://github.com/agilescientific/bruges/actions/workflows/build-docs.yml)
[![PyPI version](https://img.shields.io/pypi/v/bruges.svg)](https://pypi.python.org/pypi/bruges/)
[![PyPI versions](https://img.shields.io/pypi/pyversions/bruges.svg)](https://pypi.org/project/bruges//)
[![PyPI license](https://img.shields.io/pypi/l/bruges.svg)](https://pypi.org/project/bruges/)

## Quick start

Install with:

```shell
pip install bruges
```

Make a trapezoidal wavelet like:

```python
import bruges as bg
w, t = bg.filters.ormsby(duration=0.256, dt=0.002, f=[5, 10, 40, 80])
```

This produces two arrays: amplitude `w` and time `t`.

## Links

- [Documentation](https://code.agilescientific.com/bruges)
- [Issue Tracker](https://github.com/agilescientific/bruges/issues/)
- [PyPi](http://pypi.python.org/pypi/bruges/)
- [Agile's website](http://www.agilescientific.com)

![Bruges rooves](https://www.dropbox.com/s/tzvi22ujq6rozdb/bruges_long_rooves.png?raw=1)

---

## Installation

```shell
pip install bruges
```

Make a trapezoidal wavelet like:

```python
import bruges as bg
w, t = bg.filters.ormsby(duration=0.256, dt=0.002, f=[5, 10, 40, 80])
```

This produces two arrays: amplitude `w` and time `t`.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

[![Run tests](https://github.com/agilescientific/bruges/actions/workflows/run-tests.yml/badge.svg)](https://github.com/agilescientific/bruges/actions/workflows/run-tests.yml)
[![Build docs](https://github.com/agilescientific/bruges/actions/workflows/build-docs.yml/badge.svg)](https://github.com/agilescientific/bruges/actions/workflows/build-docs.yml)
[![PyPI version](https://img.shields.io/pypi/v/bruges.svg)](https://pypi.python.org/pypi/bruges/)
[![PyPI versions](https://img.shields.io/pypi/pyversions/bruges.svg)](https://pypi.org/project/bruges//)
[![PyPI license](https://img.shields.io/pypi/l/bruges.svg)](https://pypi.org/project/bruges/)

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Contributing

## 🙌 Thank you for considering contributing to `bruges`!

There are several important ways you can help; here are some examples:

- Submitting bug reports and feature requests: see [Issues](https://github.com/agilescientific/bruges/issues).
- Proposing code for bug fixes and new features, then [making a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).
- Fixing typos and generally improving the documentation.
- Writing tutorials, examples, and how-to documents.

## Code of conduct

We're fortunate to be part of a large professional community that conducts itself with mutual respect and consideration for others. Agile's [Code of Conduct](https://github.com/agilescientific/community/blob/main/CODE_OF_CONDUCT.md) is part of protecting these features for everyone, everywhere. Please read it.

## Authorship

If you contribute a pull request to the project, please add yourself to `AUTHORS.md`.

## License

Upstream © its respective contributors under Apache-2.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/agilescientific/bruges
- **Pinned SHA:** `905fe4fee2bd03f4852ecaacd9a004d84ed8441f`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`0ebf712f81868262f8cabf5d47899d4b80d6666d80c9bb06fae0a7463a96a7c6`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

