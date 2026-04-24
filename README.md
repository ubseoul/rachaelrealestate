# RachaelRealty.site

**Adeseke Rachael Ijidakinro — Metro Atlanta REALTOR® | Hexzades Realty**

A fully custom, AI-optimized real estate lead generation website built for Gwinnett County and Metro Atlanta.

---

## 🚀 Deployment — GitHub Pages (Step by Step)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** button → **New repository**
2. Name it: `rachaelrealty`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. Click **uploading an existing file** on the new repo page
2. Drag and drop ALL the files from this folder (keep the folder structure intact):
   ```
   index.html
   home-value.html
   404.html
   _config.yml
   blog/index.html
   blog/lawrenceville.html
   ```
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main` / Folder: `/ (root)`
4. Click **Save**
5. Wait ~2 minutes. Your site will be live at:
   `https://yourusername.github.io/rachaelrealty`

### Step 5 — Connect your custom domain (rachaelrealty.site)
1. In GitHub Pages settings, enter `rachaelrealty.site` in the **Custom domain** field
2. In Porkbun, go to your domain DNS settings and add:
   ```
   Type: A    Host: @    Answer: 185.199.108.153
   Type: A    Host: @    Answer: 185.199.109.153
   Type: A    Host: @    Answer: 185.199.110.153
   Type: A    Host: @    Answer: 185.199.111.153
   Type: CNAME  Host: www  Answer: yourusername.github.io
   ```
3. Wait 10–30 minutes for DNS to propagate
4. Check **Enforce HTTPS** in GitHub Pages settings

---

## 📧 Formspree Setup — Get Leads in Rachael's Inbox

Formspree lets the contact forms email Rachael directly. Free plan handles 50 submissions/month.

### Step 1 — Create Formspree account
Go to [formspree.io](https://formspree.io) → Sign up free

### Step 2 — Create a new form
1. Click **New Form**
2. Name it: `RachaelRealty Leads`
3. Set the email to **Rachael's email address**
4. Copy the **Form ID** (looks like: `xpzvwkgr`)

### Step 3 — Replace the placeholder in all files
Search for `REPLACE_WITH_YOUR_FORMSPREE_ID` in these files and replace with your Form ID:
- `index.html` (line ~420)
- `home-value.html` (line ~380)
- `blog/lawrenceville.html` (line ~210)

Example: change `REPLACE_WITH_YOUR_FORMSPREE_ID` → `xpzvwkgr`

### Step 4 — Test it
Fill out the contact form on the live site. You should get an email within seconds.

---

## 📁 File Structure

```
rachaelrealty/
├── index.html              ← Homepage (main site)
├── home-value.html         ← Seller lead funnel (4-step)
├── 404.html                ← Custom error page
├── _config.yml             ← GitHub Pages config
├── README.md               ← This file
└── blog/
    ├── index.html          ← Blog listing page (SEO hub)
    ├── buyers-guide.html   ← Complete buyer guide (SEO)
    ├── sellers-guide.html  ← Complete seller guide (SEO)
    ├── lawrenceville.html  ← Lawrenceville neighborhood guide
    ├── duluth.html         ← Duluth neighborhood guide
    ├── suwanee.html        ← Suwanee neighborhood guide
    └── alpharetta.html     ← Alpharetta neighborhood guide
```

---

## 🔮 Recommended Next Pages to Add

These pages will multiply SEO traffic over time. Ask Claude to build them:

| Page | Why it matters |
|------|---------------|
| `blog/duluth.html` | High search volume for "homes in Duluth GA" |
| `blog/suwanee.html` | Very affluent, high-value buyer/seller leads |
| `blog/buford.html` | Fast-growing area, lots of search traffic |
| `blog/alpharetta.html` | Highest home prices = biggest commissions |
| `buyers-guide.html` | Targets first-time buyers searching Google |
| `sellers-guide.html` | Targets homeowners researching selling |

---

## 🤖 AI Search Optimization

The site is pre-optimized for AI search engines (ChatGPT, Perplexity, Google AI Overviews):

- ✅ Schema.org JSON-LD on every page (RealEstateAgent, Article, Service types)
- ✅ Rachael's name, brokerage, rating, and location in structured data
- ✅ Local area content for all 18 cities she serves
- ✅ Real verified reviews embedded with review schema
- ✅ E-E-A-T signals (expertise, experience, authority, trust)

---

## 📞 Quick Reference

- **Agent:** Adeseke Rachael Ijidakinro
- **Brokerage:** Hexzades Realty
- **Location:** Lawrenceville, GA (Gwinnett County)
- **Rating:** 5.0 ★ (RateMyAgent, Homes.com, HomeLight)
- **Domain:** rachaelrealty.site (register at porkbun.com, ~$1–3/yr for .site)

---

*Built with love as a gift. 🏡*
