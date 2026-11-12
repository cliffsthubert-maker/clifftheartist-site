# clifftheartist.com

Static website for Cliff the Artist · Content Studio. Plain HTML + CSS, no build step.

## Pages
- index.html: Content Studio offer (home)
- work.html: portfolio
- about.html, books.html, contact.html, 404.html

## Images still needed (put them in /images, then swap the matching [placeholder] box for an <img>)
- tunez-flyer.jpg, island-ville-food.jpg, island-tv-studio.jpg (home hero)
- kekas-new-year-flyer.jpg, kekas-santorini-reel.jpg (recent work)
- cliff-portrait.jpg (about)
- yasuke-cover.jpg, frequency-cover.jpg (books)

## Publish (GitHub Pages)
1. Create an empty GitHub repo named `clifftheartist-site`.
2. Push this folder to it.
3. Repo Settings → Pages → Source: Deploy from branch → `main` / root.
4. Custom domain: clifftheartist.com (the CNAME file already sets this). Enable "Enforce HTTPS" once it's available.
5. At your domain registrar, add DNS records:
   - A records for @ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME for www → <your-github-username>.github.io
