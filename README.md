# Taibao Elementary · Bilingual Page

A bilingual web page for **嘉義縣太保市太保國民小學 (Taibao Elementary School)**, a century-old public elementary school (est. 1900) in Taibao City — the seat of Chiayi County and home to the Southern Branch of the National Palace Museum and the high-speed rail.

Built and donated by [My Culture Connect 人師教育協會](https://www.mycultureconnect.org/), a Taiwanese non-profit. Hosted on GitHub Pages at:

**Live**: <https://lukelin7429.github.io/tbps-bilingual/>

## Pages

| URL | Page | Content |
|---|---|---|
| `/` | Home | School identity, the Wang De-lu → "Taibao" naming story, town-and-school timeline, the vision 健康・適性・智慧 (Healthy / Adaptive / Wise), principal teaser, student-life cards (Chinese-music ensemble, baseball, science exploration, reading & bilingual), contact |
| `/principal/` | Principal's Office | Principal Chen Chih-kuang (appointed 2022), a bilingual letter on leading a hundred-year school into a bilingual century, three commitments mapped to 健康・適性・智慧 |
| `/bilingual-campus/` | Bilingual Campus | How Taibao is building bilingual capacity — 2030 Bilingual Nation policy, teachers trained abroad, English classroom, county resources — plus embedded Classroom English & Bilingual Announcements playlists (My Culture Connect resources) |
| `/around-taibao/` | Around Taibao | A bilingual walk through six real Taibao landmarks: the name "Taibao" / Wang De-lu · Fuji Temple (Seven Star Goddess) · the Wang Family Shrine · Southern Branch of the National Palace Museum · THSR Chiayi Station · the Chiayi County seat — each with English and Chinese phrases |

## Design

- **Primary**: ink-blue `#1F3A5F` (a century-old school's scholarly gravitas)
- **Accent**: bronze `#B07D3C` (the copper of the Southern Palace Museum and the Wang De-lu heritage)
- **Type**: Playfair Display (English display serif) + Lato (English body) + PingFang TC (Chinese)
- **Background**: pure white throughout
- **Pattern**: inline single-page per section — no click-outs, no popups, no iframes-in-iframes
- Distinct from the coastal-teal palette of the sister school [KangLang Elementary](https://lukelin7429.github.io/klnes-bilingual/)

## Bilingual resource credits

The two YouTube playlists embedded on `/bilingual-campus/` are produced by **My Culture Connect** and shared across multiple partner schools, so views accumulate on one channel and every school gets updates automatically.

## Assets still needed from the school

See `photos/README.md`. The heroes currently render as gradients (no broken images); drop real photos in `photos/` and follow the comments in `assets/css/main.css` and the page files to swap them in. Also pending confirmation from the school: the principal's name romanisation, biography, and portrait.

## To bind a custom domain (when the school is ready)

GitHub Pages serves this at `lukelin7429.github.io/tbps-bilingual/`. To put it on a domain the school controls:

1. Use a **subdomain** (e.g. `www.` or `bilingual.<domain>`), **not** an apex/naked domain — subdomains provision their HTTPS certificate cleanly on GitHub Pages; apex domains are slower and have stalled before.
2. In the school's DNS console, add a `CNAME` record pointing the chosen hostname to `lukelin7429.github.io`.
3. Create a `CNAME` file in this repo's root containing only that hostname.
4. Wait for propagation (1–24 h), then enable **Enforce HTTPS** in **Settings → Pages** *after* the certificate has been issued.

Note: `cyc.edu.tw` subdomains are managed centrally through TANet / the Chiayi County network centre — the school cannot self-serve those and would need to request the CNAME through that channel.

## License

Content (text and the bilingual walk) is original to Taibao Elementary and My Culture Connect, shared for non-commercial educational reuse. Code (HTML/CSS) is MIT-licensed.

## Maintainer

- **Repo**: [lukelin7429/tbps-bilingual](https://github.com/lukelin7429/tbps-bilingual)
- **Designed and donated by**: [Luke Lin 林吉祥](https://www.mycultureconnect.org/), My Culture Connect 人師教育協會
- **School**: [tbps.cyc.edu.tw](https://www.tbps.cyc.edu.tw/) · 05-2949031
