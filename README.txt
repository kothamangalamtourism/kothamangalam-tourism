Kothamangalam Tourism Development Portal - static GitHub Pages deployment package

1. Upload index.html and CNAME to the root of a PUBLIC GitHub repository.
2. GitHub repository Settings > Pages > deploy from branch > main / root.
3. Add custom domain: www.kothamangalamdevelopmentcouncil.in.
4. At the domain DNS provider, create CNAME: host www, target YOUR-GITHUB-USERNAME.github.io (replace with your actual GitHub username domain).
5. Wait for DNS propagation, then enable Enforce HTTPS under Settings > Pages.
6. Replace the placeholder social URLs in index.html with the real official Facebook, Instagram and YouTube URLs.

Note: GitHub Pages hosting can be free for public repositories. The domain registration/renewal is separate and may cost money. This package does not publish the site or change DNS; account access is required for those steps. The admin editor in this static prototype stores changes only in the current browser; it is not a secure shared CMS.
