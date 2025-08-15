Quick start (Vercel)
======================

1) Create a free account at https://vercel.com and click **New Project**.
2) When asked to "Import Git Repository", choose **Skip** and then **Create** a project from **Other** (static).
3) Upload this `index.html` file when prompted or connect a GitHub repo that contains it.
4) After deploy, go to **Project → Settings → Domains → Add** and add your domain(s).
   • For an apex domain (example.com): add an **A** record at your DNS to the IP Vercel shows (typically 76.76.21.21).
   • For `www` or other subdomains: add a **CNAME** to the value Vercel shows (often `cname.vercel-dns.com`).
5) Wait a few minutes for DNS to propagate. Your site will be live on all the domains you added.

Alternative (GitHub Pages)
=========================
1) Create a GitHub repo and upload `index.html`.
2) In repo **Settings → Pages**, enable Pages from the `main` branch and `/ (root)`.
3) Optional custom domain:
   • Add your domain under **Settings → Pages → Custom domain**.
   • At your DNS: set four **A** records to 185.199.108.153 / .109 / .110 / .111 and a **CNAME** for `www` to `<username>.github.io`.
