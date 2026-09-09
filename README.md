# Shubh Digital Marketing — Website + CMS

This folder has everything for your live website AND a free admin panel
where you can edit text, pricing, testimonials, stats and social links
from your browser — no coding needed.

## What's in this folder
- `index.html` — the website itself
- `content.json` — all the editable text/numbers on the site (the admin panel edits this file)
- `admin/` — the admin panel (Decap CMS)

## One-time setup (about 10 minutes)

### 1. Put this folder on GitHub
1. Go to https://github.com and create a free account if you don't have one.
2. Create a new repository (e.g. `shubh-website`).
3. Upload all the files in this folder to that repository, keeping the
   `admin` folder structure exactly as it is.

### 2. Connect the repo to Netlify
1. In Netlify, choose **Add new site → Import an existing project**.
2. Connect your GitHub account and pick the repository you just created.
3. Leave the build settings empty (no build command needed) and deploy.

### 3. Turn on Identity + Git Gateway (this powers the login for the admin panel)
1. In your Netlify site dashboard, go to **Site configuration → Identity** and click **Enable Identity**.
2. Under **Registration**, set it to **Invite only** (so strangers can't sign up).
3. Go to **Identity → Services → Git Gateway** and click **Enable Git Gateway**.
4. Go to **Identity → Invite users**, and invite your own email address.
5. Check your email and accept the invite — this sets your password.

### 4. Open the admin panel
Go to `https://your-site-name.netlify.app/admin/` and log in with the
email/password from step 3. You'll see a friendly form for every editable
section of the site — hero text, pricing, testimonials, stats, and social
links. Hit **Publish** after editing, and the live site updates automatically
within a minute or two.

## Day-to-day editing
Once set up, you never need to touch code again:
1. Visit `/admin/` on your site.
2. Log in.
3. Edit any field.
4. Click **Publish**.

Bring the changes back to this chat any time you want a bigger redesign —
I can always give you a fresh, ready-to-upload version.
