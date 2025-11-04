# lab4-1 README

## Server headers
Most sites showed 'Server' headers like 'Apache/2.4.7 (Ubuntu)' or 'gunicorn/19.9.0'. These can reveal what software the site uses, which helps attackers but also helps defenders patch systems faster.

## Differences between sites
- **Headers:** Some had detailed server info; others hid it. A few changed responses for scanner-style User-Agents.
- **Titles & meta:** Some pages had clear titles and descriptions, others were blank or generic.
- **Forms:** Some sites had login or search forms, with visible and hidden inputs.
- **Keywords:** 'Admin' or 'login' appeared rarely, showing that static scans can miss dynamic text.

## Defensive tip
Hide or remove server version info from headers and keep meta data minimal to reduce clues for attackers.

## Ethics
Only scan or probe systems you own or are allowed to test. Be gentle with request rates and report any issues responsibly.

