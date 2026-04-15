# joaopelinca.github.io

This is my personal portfolio website built with Jekyll and the Chirpy theme, hosted on GitHub Pages.

**Live site:** [joaopelinca.github.io](https://joaopelinca.github.io)

---

## Purpose

This site is my living portfolio where I am going to document the computational skills, projects, and experiences I build throughout my academic journey in Kinesiology at the University of Calgary. It started as the final project for **KNES 381 (Computer Applications in Kinesiology)** and will continue to grow as I take on new courses, research, and opportunities.

---

## Tools & Technologies

| Category | Tools |
|---|---|
| Site framework | Jekyll + Chirpy theme |
| Hosting | GitHub Pages |
| Markup | Markdown, HTML, Liquid |
| Version control | Git, GitHub |
| Python stack | NumPy, Pandas, Matplotlib |
| Notebooks | Kaggle Notebooks |
| Signal processing | MATLAB |

---

## Site Navigation

### Pages

| Page | Description |
|---|---|
| **Home** | Landing page with a brief introduction |
| **About** | Academic background, skills, and interests |
| **Projects & Skills** | Showcase of computational projects (see below) |

### Projects

| Post | Description |
|---|---|
| [Python & Data Analysis — VO2max](/_posts/2026-04-14-python-vo2-analysis.md) | Python script analyzing breath-by-breath gas exchange data from Kaggle to identify physiological thresholds (GET, RCP). Built with NumPy, Pandas, and Matplotlib. Embedded Kaggle notebook. |
| [MATLAB & Sensorimotor Neuroscience](/_posts/2026-04-14-matlab-sensorimotor-neuroscience.md) | MATLAB analysis of EMG signals from KNES 464. Covers the tendon vibration reflex and vestibular reflex, with figures generated from real physiological data. |
| [Tools & Workflow](/_posts/2026-04-14-tools-and-workflow.md) | Overview of the development toolkit built throughout KNES 381 — Git, Jekyll, Python, terminal, and more. |

---

## Running Locally

Requires Ruby and Bundler.

```bash
# Install dependencies
bundle install

# Start local server
bundle exec jekyll serve

# Open in browser
open http://localhost:4000
```

---

## Project Structure

```
_posts/          # Project write-ups and blog entries
_tabs/           # Main navigation pages (About, Projects)
assets/
  img/           # Profile photo and project figures
_config.yml      # Site settings (title, URL, avatar, social links)
index.md         # Home page content
```
