# Canada PR Calculator

A single-page calculator for Canada's **Express Entry Comprehensive Ranking System (CRS)** and the **Ontario Immigrant Nominee Program (OINP) Ontario Workforce Priority** stream. The interface is in Simplified Chinese.

**Live page:** https://agnesv1.github.io/canada-pr-calculator/

## Features

- **CRS** under the current rules and the rules effective **November 3, 2026** (the new Labour Market Integration factor: high-wage Canadian work experience and job-offer points, no LMIA required). IRCC's list of 186 high-wage occupations is built in.
- **OINP Ontario Workforce Priority** EOI score on the 132-point grid published in July 2026 (earnings factor updated October 5, 2026), with a check of the basic stream criteria.
- **Timeline**: work permit countdown, the dates Canadian experience reaches 1, 2 and 3 years, birthdays that lower age points, language test expiry, and the OINP recent-graduate window.
- **Improvement suggestions** ranked by points gained and tagged by how achievable each one is; the likely-and-worthwhile ones are starred.
- **Latest Express Entry cutoffs**, read live from IRCC's public data feed, with a built-in snapshot as an offline fallback.
- **IELTS General Training ↔ CLB table**; CELPIP-G, PTE Core and TEF Canada scores are converted too.
- **Private by design**: everything you enter stays in your browser's local storage. Use *export / import* to move a backup between browsers or devices.

## Usage

Open the live page, or download `index.html` and open it in any modern browser. There is no build step and there are no dependencies.

## Updating the rules

All point tables, the high-wage occupation list and the draw snapshot sit at the top of the `<script>` block in `index.html`. The rules were last checked against the official sources on **2026-10-23**.

## Sources

- IRCC: [CRS criteria](https://www.canada.ca/en/immigration-refugees-citizenship/services/immigrate-canada/express-entry/check-score/crs-criteria.html), [changes effective November 3, 2026](https://www.canada.ca/en/immigration-refugees-citizenship/services/immigrate-canada/express-entry/changes.html), [high-wage occupations](https://www.canada.ca/en/immigration-refugees-citizenship/services/immigrate-canada/express-entry/check-score/high-wage.html), [rounds of invitations](https://www.canada.ca/en/immigration-refugees-citizenship/services/immigrate-canada/express-entry/rounds-invitations.html), [language test equivalency](https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/work/after-graduation/eligibility/language-results.html)
- Ontario: [Ontario Workforce Priority stream](https://www.ontario.ca/page/ontario-workforce-priority-stream), [2026 OINP updates](https://www.ontario.ca/page/2026-ontario-immigrant-nominee-program-updates)

## Disclaimer

For estimates and planning only. This is not legal advice; IRCC, the OINP and your official profile always prevail.
