# Security Policy

## Supported versions

This is a learning repository made of static `.html` files. There is no server,
database, or package to patch, so we simply maintain the latest state of the
`main` branch. If you find a problem, it will be fixed there first.

| Version | Supported |
| :--- | :--- |
| `main` (latest) | ✅ |
| Older commits / forks | ❌ (please update to the latest version) |

## Reporting a vulnerability

**Please do not open a public issue for a security problem.**

Email the maintainer privately at **staticcodersilicon@gmail.com** with:

* Which file and line (or section) is affected
* What the problem is and how someone could abuse it
* A minimal example, if possible
* Which browser/version you reproduced it in
* Any suggested fix you have in mind

You'll get an acknowledgement within **7 days**. We'll investigate, agree on a
fix and disclosure timeline with you, and credit you in the fix if you'd like.
We aim to ship a fix within **30 days** for confirmed issues. If we can't
reproduce it, we'll tell you why and keep the conversation open.

Please give us a reasonable chance to fix the issue before disclosing it publicly.

## What counts as in scope

Even a beginner tutorial should teach safe habits, so please report things like:

* Demo code that runs untrusted input with `innerHTML`, `eval()`, or `document.write()`
* Examples that load scripts, fonts, or images from untrusted third parties
* Instructions that encourage unsafe practices (storing passwords in plain text,
  pasting secrets into a page, disabling browser protections)
* Links pointing to malicious or lookalike sites
* Anything that could harm a reader who copies the example into their own project

## Out of scope

* The fact that HTML/CSS/JavaScript source is public — that's the whole point of
  this project
* Theoretical issues with no realistic impact on readers
* Issues in third-party sites or browsers that just happen to be linked from a lesson
* Reports generated entirely by automated scanners with no explanation

## A note for learners

Never put real passwords, API keys, tokens, or personal data into a lesson file
or any code you find online. Use fake values like `example@example.com` and
`YOUR_API_KEY_HERE`. If you ever paste a real secret into a GitHub issue or pull
request, **revoke/rotate it immediately** — deleting the message is not enough.
