# Farid A. Khavari — author website (production deploy package)

Same structure as cubanlinkcalc.com: static site, GitHub Pages hosting, GoDaddy = domain only.

## Files
- index.html — the full site (v2 mock, production copy)
- assets/ — portrait-miami.png (hero), khavari-for-governor.png (history poster), back-cover.jpg (about)
- favicon.svg, robots.txt
- sitemap.xml + CNAME — added once the domain is confirmed (need exact domain from Angel's GoDaddy)

## Amazon links
- Leaving Liberal Dystopia — direct: amazon.com/dp/B0H94TFG83 (verified, Angel-supplied)
- Towards a Zero-Cost Economy — direct: amazon.com/dp/1440121680 (ISBN/ASIN verified)
- Environomics — direct: amazon.com/dp/027594462X (ISBN-10 verified)
- The Final Crash — direct: amazon.com/dp/0984881603 (ISBN/ASIN verified)
- All other books — Amazon search links by exact title + author (Amazon blocks automated product-page reads; swap in direct dp links as they are supplied)

## Launch steps (like cubanlinkcalc)
1. Confirm domain.
2. Create public GitHub repo under @omgbye, push this folder, enable Pages.
3. Add CNAME (domain) + sitemap.xml with the real domain.
4. GoDaddy DNS (Angel clicks in his own session — GoDaddy bot-walls Muse's browser): delete parked A @, add A @ -> 185.199.108.153 / .109.153 / .110.153 / .111.153 (TTL 600), CNAME www -> omgbye.github.io.
5. Verify HTTPS, then submit to Google Search Console (URL-prefix, meta tag method).
