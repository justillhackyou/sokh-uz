# sokh.uz

Independent, multilingual landing page for sokh.uz. Uzbek is the default language; Russian and English are available.

## GitHub Pages

1. Create a public repository and upload `index.html`, `CNAME`, and `README.md` to the default branch.
2. Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)` → Save.
3. In PS Cloud DNS, set the apex `@` A records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
4. Remove conflicting apex A/AAAA/CNAME records. Optionally set `www` CNAME to `<github-username>.github.io`.
5. In GitHub Pages, verify custom domain `sokh.uz` and enable Enforce HTTPS when available.

GitHub Pages custom domains: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
