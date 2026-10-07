# MEHUL — one-pager

## Put this on GitHub Pages
1. New repo → upload `index.html`, `style.css`, and the `assets/` folder to the root.
2. Settings → Pages → Source: Deploy from branch → `main` → `/ (root)` → Save.
3. Your site goes live at `https://<username>.github.io/<repo>/` within a minute or two.

## Add your mix demo
Upload your 5-minute mix file to the repo root and name it exactly `demo-mix.mp3`.
The player in the Mix section already points to that filename — no code changes needed.
(If your file is a different format like `.wav` or `.m4a`, either rename it to `.mp3`, or open `index.html` and change `demo-mix.mp3` to your actual filename in the `<source src="...">` line.)

## Add your contact info
In `index.html`, under the Contact section:
- Replace `xxxx@abc.com` (appears twice — the `mailto:` link and the visible text) with your real email once you've bought the domain.
- Replace `+91-xxxxxxxxxx` with your real number.

## Custom domain (once you buy one)
Add a `CNAME` file to the repo root containing just your domain name, then set it in Settings → Pages → Custom domain. Point your registrar's DNS to GitHub's A records (185.199.108.153, .109.153, .110.153, .111.153) or a CNAME to `<username>.github.io`.
