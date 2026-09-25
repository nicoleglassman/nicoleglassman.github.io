# Nicole Glassman — portfolio site

Three self-contained pages, no build step, no server code. Upload the folder as-is.

```
index.html              landing page (your name, two cards, contact)
buildcheck/index.html   Buildcheck — interactive campaign-build QA demo
pov/index.html          What I'd change about most brands' social
```

Clean URLs once hosted:

- `https://YOURSITE/`            landing
- `https://YOURSITE/buildcheck/` demo
- `https://YOURSITE/pov/`        point of view

The pages link to each other with relative links, and every "message me on LinkedIn" links to linkedin.com/in/nicoleglassman.

---

## Host it (pick one)

### Option A — GitHub Pages (free, permanent, ~10 minutes)

1. Create a GitHub account if you don't have one. Choose the username carefully — it becomes the URL (e.g. `nicoleglassman`).
2. Click **New repository**. Name it exactly `YOURUSERNAME.github.io` (e.g. `nicoleglassman.github.io`). Public. Create.
3. On the empty repo page click **uploading an existing file**. Drag in `index.html`, the `buildcheck` folder and the `pov` folder (folders drag-and-drop fine in Chrome). Click **Commit changes**.
4. Wait a minute or two, then open `https://YOURUSERNAME.github.io/buildcheck/`. If it 404s, go to **Settings → Pages**, set Source to *Deploy from a branch*, branch `main`, folder `/ (root)`, Save, and wait again.
5. To update a page later: open the file in the repo, click the pencil, paste the new HTML, commit. Or re-upload.

Custom domain (optional, ~$12/yr): buy the domain, then in **Settings → Pages → Custom domain** enter it and follow GitHub's DNS instructions (a CNAME for `www` pointing at `YOURUSERNAME.github.io`). Your URLs become `https://nicoleglassman.com/buildcheck/`.

### Option B — Netlify (free, fastest)

1. Sign up at netlify.com. **Add new site → Deploy manually**.
2. Drag the whole folder (or the zip) onto the drop zone. It's live in seconds at a random `something.netlify.app` address.
3. **Site configuration → Change site name** → `nicoleglassman`. Your URLs become `https://nicoleglassman.netlify.app/buildcheck/` and `/pov/`.
4. Custom domain: **Domain management → Add a domain**.

Either way, open both pages on your phone once before sharing — that's where LinkedIn traffic comes from.

---

## Before the links go anywhere

1. **May/June vs same month.** Résumés v17 and v18 say "May creator content … June brand creative." The POV page says the flights ran in the same month. Make them agree — whichever is true — in both places.
2. **Dates.** Every résumé version still says "December 2025 – Present." Change to "December 2025 – September 2026."
3. **The public name.** Add "(public demo: Buildcheck)" to the QA-system bullet so the link and the bullet connect.

---

## Adding the links to each résumé version

Replace `YOURSITE` with your real host (`nicoleglassman.github.io`, `nicoleglassman.netlify.app`, or your domain). Write URLs out in plain text as well as hyperlinking them — some applicant-tracking systems strip hyperlinks from PDFs.

### Header line (all versions)

Under the existing contact line, add:

`Portfolio: YOURSITE/buildcheck · YOURSITE/pov`

For the agency paid-social version you can keep just the demo: `Portfolio: YOURSITE/buildcheck`

### The QA-system bullet (all versions)

Current (v18): *Built an AI QA system on Anthropic's Claude that checks Ads Manager exports against media plans, cutting a four-day, four-person review of 2,000 ads to a 20-minute run. Rolled it out agency-wide and trained the media VP and analysts.*

Edit to: *Built an AI QA system on Anthropic's Claude (public demo: Buildcheck — YOURSITE/buildcheck) that checks Ads Manager exports against media plans, cutting a four-day, four-person review of 2,000 ads to a 20-minute run. Rolled it out agency-wide and trained the media VP and analysts.*

Hyperlink "Buildcheck" to the demo. This is the one bullet a recruiter will want to verify, so the proof sits next to the claim.

### Version by version

**v12 In-House Brand (needs a v19 rebuild from v18 anyway)**
- Header: both links.
- Summary: retitle to *Social media marketer and strategist…* and end with *…and builds the tools to execute them: shipped Buildcheck, an AI-assisted campaign QA system used agency-wide.*
- Keep the Fear Factor three-way creative test and the creator-vs-brand test as a pair — they're the testing story the POV page tells.
- Keep v18's NBA cross-platform activation / influencer coordination bullet and the Leadership skills line — closest things on the page to in-house social work.
- Optional line at the end of the summary or in Skills: *Point of view on brand social: YOURSITE/pov*.

**v17 AI Marketing**
- Header: both links.
- Summary already leads with the QA system — add the name: *…shipped Buildcheck, a campaign QA system on Anthropic's Claude that cut…*
- Skills → AI and Automation: add *Python build and test scripts (AI-paired)* if you're comfortable defending it in an interview; it's stated on the demo page.

**v18 Agency Paid Social**
- Header: demo link (POV optional).
- Bullet edit as above.
- Nothing else — the POV page positions you for in-house, which isn't this version's job.

---

## LinkedIn Featured section

Add two links (Profile → Add profile section → Recommended → Add featured → Add a link):

1. **What I'd change about most brands' social** — `YOURSITE/pov/`
   Description: *Six changes I'd make in an in-house social seat, each with the test that convinced me.*
2. **Buildcheck — AI-assisted QA for paid-social campaign builds (interactive demo)** — `YOURSITE/buildcheck/`
   Description: *A planning workbook and an AI QA engine that check a campaign build against the plan before it spends. Plant errors, run the QA, fix, re-run.*

POV first, demo second: strategist first, then proof you can ship. Also edit the Experience entry for VaynerMedia to add the Buildcheck line and link it as media on that entry.
