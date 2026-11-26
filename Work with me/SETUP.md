# Freelance page: setup guide

## What's in this folder
- `freelance/index.html`: the full freelance page with services, pricing, process, inquiry form and FAQ. It's a single file with no images needed.
- `add-to-existing-portfolio/freelance-section.html`: a nav link and a small "Freelance" section to paste into your current portfolio, linking to the new page.

## 1. Upload the page (about 5 minutes)
1. github.com → your `portfolio` repo → **Add file → Upload files**.
2. Drag in the whole `freelance` folder → **Commit changes**.
3. After 1–2 minutes, the page is live at **https://jessieqin0911.github.io/portfolio/freelance/**

## 2. Add it to your existing portfolio
Open `add-to-existing-portfolio/freelance-section.html` and follow the two steps at the top: add the nav link, then paste the section above your Contact section. Edit your portfolio's `index.html` on GitHub (pencil icon) and commit.

## 3. Connect the inquiry form to Google Forms (about 15 minutes)
The form on the page is custom, but each submission is saved to your Google Form, so inquiries land in a Google Sheet.

**a) Create the form** at forms.google.com. Make **every question "Short answer"** (and "Details" a Paragraph), with no required questions. The page already handles validation and the multiple-choice options. Use these 13 questions, in any order:

Name · Business · Email · Phone · Link · Type · Services · Package · Details · Deadline · Budget · Assets · Source

**b) Get the pre-filled link:** ⋮ menu → **Get pre-filled link**. In each question, type its **keyword in lowercase**:
`name`, `business`, `email`, `phone`, `link`, `type`, `services`, `package`, `details`, `deadline`, `budget`, `assets`, `source`
Click **Get link** → **Copy link**.

**c) Paste it** into `freelance/index.html`. Search for `GOOGLE_FORM_PREFILLED_LINK = ""` and paste the link between the quotes. Your email is already set as the backup (hidden from the page).

**d) Turn on notifications:** Responses tab → **Link to Sheets**, then ⋮ → **Get email notifications for new responses**.

**e) Test it:** submit a test inquiry on the live page and check the Sheet.

Until step c is done, "Send inquiry" opens a pre-written email to you instead, so it still works.

## 4. Review before sharing
- [ ] Check your Tipalti agreement or ask HR about outside work
- [ ] Prices, the 2-business-day reply time, and the "about a week" turnaround
- [ ] FAQ answers I drafted for you: 50% deposit on one-off projects, month-to-month packages, and a written agreement. Change these to your real terms.
- [ ] The founding-client 20% offer and the "happy to meet for coffee" line
- [ ] "Metro Vancouver" location
- [ ] Update "currently looking for my next digital marketing role" on your main portfolio
