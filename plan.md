# Personal Website Plan — Jake Vikoren

## Status
[x] Questions answered
[x] Tech stack decided
[x] Design direction set
[x] Site structure defined
[ ] Content gathered
[ ] Build & deploy

---

## Decisions

| Item              | Decision                                      |
|-------------------|-----------------------------------------------|
| GitHub username   | jvikoren                                      |
| Deploy URL        | jvikoren.github.io                            |
| Primary purpose   | Professional landing page for recruiters/hiring managers |
| Tech stack        | Jekyll + plain HTML/CSS/JS (no unnecessary complexity) |
| Visual style      | Minimalist dark mode, clean animations        |
| Sections          | About, Resume/CV, Projects, Publications, Contact |
| Dark/light mode   | Dark mode only (keep it simple)               |
| Contact form      | No — just a contact section (email/links)     |
| Analytics         | None                                          |
| Custom domain     | None — default GitHub Pages URL               |

---

## Design Direction

**Inspiration:** [jazzed-kale.cloudvent.net](https://jazzed-kale.cloudvent.net/) — clean, minimal, monochromatic, content-first, ample whitespace, clear hierarchy.

**Style:**
- Dark background, light text — neutral palette (blacks, grays, off-whites with one subtle accent color)
- Minimalist layout with generous whitespace
- Clean sans-serif typography with clear heading hierarchy
- Simple, subtle animations (fade-in on scroll, hover effects) — nothing flashy
- Single-page or multi-page with smooth navigation

---

## Site Structure

### Sections (in order)
1. **Hero** — Name, tagline ("Machine Learning Engineer [AI x Science]"), brief intro, CTA links (GitHub, LinkedIn, Resume)
2. **About** — Short bio: background, focus, what drives you
3. **Projects** — Cards or list; each with title, description, link/embed
4. **Publications** — List of papers/work with links
5. **Resume/CV** — Embedded PDF or downloadable link, possibly a text summary
6. **Contact** — Email link + social links (no form)

---

## Content Needed

### Still required from you:
- [x] **Bio** — 2–4 sentences about yourself, background, and focus area
  - Jake Vikoren is a physics-trained machine learning engineer specializing in AI for scientific discovery. His work spans atomic-scale modeling, geometric deep learning, and computer vision, including self-supervised learning for biomedical imaging. He has developed machine learning interatomic potentials and generative models for materials discovery while building scalable ML systems for large-scale scientific data. Throughout his career, he has consistently translated research advances into practical engineering solutions and deployed machine learning systems in interdisciplinary scientific environments.
- [x] **Projects:**
  - Project 1: Charge Density Prediction
    - [OpenGPNN](https://github.com/GenerativeMaterials/OpenGPNN/tree/main). A Charge Density prediction model, see github for the project description. 
  - Project 2: Skin Cancer Classification — description, and is it a standalone HTML file to embed or link to?
    - Here is the link to the project. Take a look and generate a description: [Skin Cancer Classification](https://www.kaggle.com/code/jvikoren/fastai-mobilenet-90-acc)
  - Project 3: What is the link and title for the second project?
    - Particle Life. I added the HTML file for it. 
  - Any others?

- [x] **Publications** — List of papers/articles with titles, venues, and links (if any)
  - [Machine Learning, Density Functional Theory, and Experiments to Understand the Photocatalytic Reduction of CO2 on CuPt/TiO2](https://pubs.acs.org/doi/abs/10.1021/acs.jpcc.4c02275)
  - [Generation of Thermodynamically Favorable Crystal Structures of Pb_{10-x}Cu_x(PO4)6O using Atom Combinatorics Approach](https://chemrxiv.org/doi/full/10.26434/chemrxiv-2023-6bvbq)
- [x] **Resume/CV** — PDF file or link
  - I added the PDF. 
  - I also added a letter of reccomendation 
- [x] **Social links** — GitHub profile URL, LinkedIn URL, any others?
  - https://www.linkedin.com/in/jake-vikoren/

---

## Tech Notes

- **Jekyll** with GitHub Pages built-in support (no extra CI needed)
- Minimal dependencies — custom CSS (no Bootstrap/Tailwind unless needed)
- One `_config.yml`, simple `_layouts/`, flat structure
- Possibly single-page with anchor links rather than multiple pages. Use multiple pages if it improves overall organization and interpretability. 
