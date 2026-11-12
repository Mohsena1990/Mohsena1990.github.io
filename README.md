# Mohsen Asghari Ilani: Personal Website

Source for [mohsena1990.github.io](https://mohsena1990.github.io/), the personal website of **Mohsen Asghari Ilani**, PhD researcher at Swansea University (ESRC/UKRI) and Senior Data Scientist at Dotin.

Built with [Hugo](https://gohugo.io/) and the [CareerCanvas](https://github.com/felipecordero/careercanvas) theme by Felipe Cordero.

## Where things live

| What | File |
| --- | --- |
| Name, tagline, hero text, links, colours | `config.toml` |
| Navigation menu | `config/_default/menus.en.toml` |
| About, Skills, Experience, Tech Stack, Contact | `content/en/*.md` |
| Publications | `content/en/research/` |
| Blog posts | `content/en/blog/` |
| Profile photo, CV | `static/images/`, `static/files/` |

## Run locally

```bash
git clone --recurse-submodules https://github.com/Mohsena1990/Mohsena1990.github.io.git
cd Mohsena1990.github.io
hugo server
```

Then open http://localhost:1313.

## Deploy

Every push to `main` is built and published to GitHub Pages by `.github/workflows/hugo.yml`.

Optional repository secrets (Settings → Secrets and variables → Actions):

- `FORMSPREE_ENDPOINT`: enables the contact form ([formspree.io](https://formspree.io))
- `PEXELS_API_KEY`: enables random background photos ([pexels.com/api](https://www.pexels.com/api/))
