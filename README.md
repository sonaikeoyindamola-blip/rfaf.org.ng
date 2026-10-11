# rfaf.org.ng

Static website for the Rebecca Faramade Abiola Foundation. One page (`index.html`) with hash routes:
`#about`, `#programmes`, `#impact`, `#get-involved`, `#donate`, `#contact`. No build step, no backend.

## Deploy (GitHub Pages)
1. Push these files to the default branch of a repository.
2. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`.
3. Custom domain: `rfaf.org.ng` (the `CNAME` file already sets it). Tick **Enforce HTTPS** once the certificate is issued.

## DNS records for rfaf.org.ng
| Type  | Name | Value |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| AAAA  | @    | 2606:50c0:8000::153 |
| AAAA  | @    | 2606:50c0:8001::153 |
| AAAA  | @    | 2606:50c0:8002::153 |
| AAAA  | @    | 2606:50c0:8003::153 |
| CNAME | www  | `<github-owner>.github.io` |

Keep any MX/TXT records for email unchanged.

## Forms
Contact and volunteer forms build a WhatsApp message to +44 7799 301877; nothing is stored.
To collect submissions by email, point the forms at a form service (e.g. Formspree) once a domain mailbox exists.

## Content still to confirm before launch
- Registration number (8998704 shown; SC 311406507 also supplied)
- Official launch at University of Ibadan, 20 Aug 2026
- Logo, brand colours, photos (pattern panels stand in for photos)
- SWIFT code and currency for the domiciliary account
