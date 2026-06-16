# Your Hacking Daily News — 2026-06-16

_A clean, daily hacking magazine with the best stories, advisories, and research — in plain language._

![Hacker illustration](https://upload.wikimedia.org/wikipedia/commons/thumb/0/06/Password_hacking_illustration.jpg/1280px-Password_hacking_illustration.jpg)

---

## At a Glance

- Top Stories (fast read, clear takeaways)
- Vulns & Patches (what to fix first)
- Research & Exploits (deep dives and PoCs)

---

## Editor's Note

Fresh security updates and threat intel highlights, distilled for a quick read — no digging required.

![Security cover](https://upload.wikimedia.org/wikipedia/commons/thumb/0/06/Password_hacking_illustration.jpg/1280px-Password_hacking_illustration.jpg)

## Analyst’s Pick

### Chromium: CVE-2026-11681 Use after free in Ozone
_Source: Microsoft Security Update Guide (RSS) · 2026-06-16_

**Why it’s worth your time:** This CVE was assigned by Chrome. Microsoft Edge (Chromium-based) ingests Chromium, which addresses this vulnerability.

_Read more:_ https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-11682

## Fast Facts

- Total items scanned: 62
- Top Stories: 1 · Vulns: 4 · Research: 1
- This Week’s Trend keywords: chromium, chrome, information, microsoft, more

## This Week’s Trend

Across sources, the most repeated topics are **chromium, chrome, information, microsoft, more**.

## Top Stories

### Who Runs the Ransomware Group ‘The Gentlemen?’
_Source: Krebs on Security · 2026-06-10_

**Mini‑article:** A cybercrime group known as The Gentlemen has emerged as the second most active ransomware gang by victim count, rapidly attracting a talented pool of hackers through an aggressive recruitment strategy that promises affiliates 90 percent of any ransom paid by victims. This post examines clues pointing to a real life identity for the administrator of The...

_Read more:_ https://krebsonsecurity.com/2026/06/who-runs-the-ransomware-group-the-gentlemen/

## Vulns & Patches

### CVE-2026-34182 CMS AuthEnvelopedData Processing May Accept Forged Messages
_Source: Microsoft Security Update Guide (RSS) · 2026-06-16_

**Mini‑article:** Information published.

_Read more:_ https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-34182

### CVE-2026-54411 Linux-PAM through 1.7.2 contains an observable timing discrepancy (CWE-208) in the pam_userdb module's plaintext-password comparison path in modules/pam_userdb/pam_userdb.c that allows a local or network-adjacent attacker able to repeatedly drive authentication through a calling service to recover the plaintext password of a target account by measuring response-timing differences. The comparison uses strncmp() (or strncasecmp() when PAM_ICASE_ARG is set) preceded by a length-equality check, so the time to reject a candidate depends on the index of the first differing byte and on whether the candidate's length matches the stored password, leaking the password length and individual prefix bytes. The vulnerable path is reached when the administrator configures pam_userdb with crypt=none, with an unrecognized crypt method, or without a crypt= argument, causing the module to store and compare credentials in plaintext.
_Source: Microsoft Security Update Guide (RSS) · 2026-06-16_

**Mini‑article:** Information published.

_Read more:_ https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-54411

### Chromium: CVE-2026-11681 Use after free in Ozone
_Source: Microsoft Security Update Guide (RSS) · 2026-06-16_

**Mini‑article:** This CVE was assigned by Chrome. Microsoft Edge (Chromium-based) ingests Chromium, which addresses this vulnerability.

_Read more:_ https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-11682

### Chromium: CVE-2026-11679 Use after free in Codecs
_Source: Microsoft Security Update Guide (RSS) · 2026-06-16_

**Mini‑article:** This CVE was assigned by Chrome. Microsoft Edge (Chromium-based) ingests Chromium, which addresses this vulnerability.

_Read more:_ https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-11680

## Research & Exploits

### How has use of framing protection security headers changed in the past 3 years&#x3f;, (Wed, Jun 10th)
_Source: SANS ISC Diary (Title Only) · 2026-06-10_

**Mini‑article:** Back in 2023, I wrote a diary[1] discussing how commonly X-Frame-Options and CSP headers containing the frame-ancestors directive were used on 1 million most popular domains on the internet (based on the Tranco list[2]), and how they were set. Given that three years have passed since then, I thought it might be interesting to repeat the analysis and see...

_Read more:_ https://isc.sans.edu/diary/rss/33068

---

_More tomorrow. Stay patched and stay sharp._

_Image credits:_ Password hacking illustration by Santeri Viinamäki (CC BY-SA 4.0); Password hacking illustration by Santeri Viinamäki (CC BY-SA 4.0)

