# Workflow export

Put the n8n export here as `ai-applicant-screening.json`.

How to export from n8n: open the workflow, click **⋯**, choose **Download**, and save the file in this folder.

Before you commit, check the file for:
- Google Sheet IDs or document URLs. Replace them with `YOUR_SHEET_ID`.
- Any real applicant names or emails in the Sample Applicant node. Use fake data.

n8n exports do not include credential secrets, only credential names. Still, search the file for `key`, `token` and `@` before you commit.
