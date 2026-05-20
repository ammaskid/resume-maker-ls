# SEO Action Plan — resume.loomixstudios.in

## Read this first (honest expectations)

**You cannot rank #1 for "resume maker" in 5 days.** Anyone who says otherwise
is wrong. That keyword is dominated by Canva, Zety, Resume.io and Indeed —
companies with 10+ years of domain authority and large budgets.

A brand-new page takes Google **weeks to months** just to be crawled, indexed,
and ranked properly. That is how Google works — no file or trick changes it.

**What IS achievable:**
- Get indexed by Google within a few days to ~2 weeks.
- Rank quickly for low-competition, long-tail terms:
  - "loomix resume maker"
  - "loomix studios resume"
  - "free resume maker no sign up no watermark"
  - "private resume builder browser"
- Slowly climb for harder terms over months as you build links and traffic.

Your domain loomixstudios.in already ranking for "loomixstudios" is a real
advantage — the subdomain inherits some of that trust.

---

## What has been done for you (technical SEO — already in the files)

1. Full meta tags — title, description, keywords, canonical URL, robots.
2. Open Graph + Twitter Cards — proper link previews on WhatsApp, LinkedIn,
   Facebook, Twitter.
3. JSON-LD structured data — WebApplication schema + FAQPage schema.
   The FAQ schema can earn "rich snippet" FAQ boxes in Google results.
4. A real, crawlable H1 containing the keyword "resume maker".
5. A crawlable FAQ section on the page (matches the FAQ schema).
6. robots.txt — tells crawlers they can index everything.
7. sitemap.xml — lists your page for Google.
8. netlify.toml — security headers + forced HTTPS (a ranking factor).
9. site.webmanifest — makes it installable, helps mobile signals.

---

## Files to deploy (GitHub -> Netlify)

Put ALL of these in the root of your GitHub repo:

    index.html          <- the website (updated with SEO)
    robots.txt          <- crawler instructions
    sitemap.xml         <- page list for Google
    netlify.toml        <- Netlify headers + HTTPS redirect
    site.webmanifest    <- PWA manifest
    og-image.png        <- YOU must create this (see below)

### og-image.png — you need to make this
A 1200x630px image shown when your site is shared. Easiest method: open your
site, screenshot the hero section, crop to 1200x630, save as og-image.png in
the repo root. Without it, social shares show no preview image.

---

## DO THIS NOW (the part that actually matters — about 30 minutes)

Technical SEO is necessary but NOT enough on its own. These manual steps are
what actually get you indexed and ranked:

### 1. Google Search Console (most important — do today)
- Go to https://search.google.com/search-console
- Add property: resume.loomixstudios.in
- Verify ownership (DNS TXT record, or HTML tag — Netlify makes this easy).
- Submit your sitemap: enter sitemap.xml
- Use "URL Inspection" -> paste your URL -> click "Request Indexing".
  This pushes Google to crawl you in days instead of weeks.

### 2. Bing Webmaster Tools (5 minutes, free extra traffic)
- https://www.bing.com/webmasters — add and verify, submit sitemap.

### 3. Get your first backlinks (this is what raises ranking)
Google ranks pages partly by who links to them. Get real links:
- Add a link from loomixstudios.in TO resume.loomixstudios.in.
  You own both — this is the single highest-value link you can get.
- Post your tool on: Reddit (r/resumes, r/jobs — read each subreddit's rules
  first), Product Hunt, Hacker News "Show HN", Indie Hackers, relevant
  Facebook/LinkedIn groups.
- List it in free online-tool directories.

### 4. Social signals
- Share on LinkedIn, X, Instagram from the Loomix Studios accounts.
- Each share with a link is a small positive signal plus real traffic.

---

## Realistic timeline

| When       | What to expect                                              |
|------------|-------------------------------------------------------------|
| Day 1-3    | Submit to Search Console + request indexing.                |
| Day 3-14   | Google indexes the page. Check with site:resume.loomixstudios.in |
| Week 2-4   | You start ranking for brand terms ("loomix resume maker").  |
| Month 2-3  | Long-tail keywords start ranking if you keep adding links.  |
| Month 4+   | Competitive terms MAY improve — needs ongoing content+links.|

---

## To rank higher over time (ongoing — not optional)

- Add content. A blog with articles ("How to write a resume summary",
  "Best resume format for freshers") brings search traffic and gives Google
  reasons to rank you. Add them as separate HTML files in the repo.
- Get more backlinks steadily. More quality links = higher ranking.
- Keep the site fast. It already is (single file, no heavy frameworks).
- Watch Search Console for which queries bring visitors, then improve the
  page for those queries.

---

## Bottom line

The technical SEO foundation is now done and is genuinely strong. But SEO is a
months-long effort of indexing, backlinks and content — not a 5-day switch.
Do the Search Console + backlink steps this week and you will be indexed and
ranking for your brand terms fast. The big competitive terms come later, with
consistent effort.
