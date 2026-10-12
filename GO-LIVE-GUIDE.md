TOOLORA GO-LIVE GUIDE (you already have GitHub Pages working)

STEP 1. Buy your domain (about $10 to $15 a year). Namecheap or Cloudflare are good. Do NOT connect it yet.
STEP 2. Tell Claude the domain. Claude updates the sitemap, robots.txt and page addresses and gives you a new zip.
STEP 3. Upload that zip's files to your GitHub repository and click Commit changes.
STEP 4. GitHub: your repository > Settings > Pages > Custom domain. Type your domain, click Save.
        (Do this BEFORE changing DNS. It protects your domain.)
STEP 5. At your domain registrar > DNS settings, add:
        4 "A" records for @ pointing to: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
        1 "CNAME" record for www pointing to: YOUR-GITHUB-USERNAME.github.io
STEP 6. Wait 10 minutes to a few hours. Then in Settings > Pages tick "Enforce HTTPS".
STEP 7. Google Search Console (search.google.com/search-console): add your domain, then submit https://YOURDOMAIN/sitemap.xml
STEP 8. Google Analytics: create a property, copy the Measurement ID (starts with G-). Give it to Claude to switch analytics on.
STEP 9. Apply for Google AdSense when the site has been live for a few weeks and Search Console shows pages indexed.
