# Emsi-Skill-Matcher
Extract &amp; compare skills from your resume and a job posting

**Credit to Emsi Burning Glass**
https://skills.emsidata.com/
Get Access, see documentation, and use the pre-created tools there

I wanted to use the Emsi Skills API to compare my resume to a job posting by extracting skills to see what matches, what's missing from my resume, and what on my resume is "useless" for the job posting.

This isn't perfect, but it gives some quick insight which is helpful.

**Notes:**
* Resume must be in a Google Doc
* Job posting must be on a Greenhouse job board

**Instructions**
1. Copy the Google Sheet & Apps Script: https://docs.google.com/spreadsheets/d/1_qLKtICWaB_7XL645B8__EgHeh3SjrbbO9gIO0gwBZE/template/preview
   Or create your own using this repository
2. Get your API access: https://skills.emsidata.com/access
3. Open Apps Script and enter clientId & secret credentials into Token.gs file
4. Paste Google doc resume URL into B1
5. Paste Greenhouse job posting URL into B2
6. Select from menu Compare Skills - Compare Skills Now

**Results**
* Spreadsheet will display matched skills including name, category, confidence interval, and URL to more info via Emsi
* Ditto for skills missing from your resume
* Ditto for skills in your resume that aren't relevant to job posting
