# Felix Aguila — Personal Portfolio

Personal portfolio website for **Felix Manuel Aguila Alonso**, Product Analytics Specialist & ML Engineer.

## Live Site
https://felitoaguila.github.io/

## About
This site showcases my experience, projects, and skills in:
- **Product Analytics**: ETL pipelines, KPI dashboards (Dash/Plotly), payment data analysis (Stripe, MercadoPago)
- **Data Engineering**: SQL, MongoDB, BigQuery, Airflow, dbt, Docker
- **Machine Learning**: scikit-learn, PyTorch, TensorFlow, computer vision, NLP
- **Data Visualization**: Dash, Plotly, Tableau, Matplotlib, Seaborn

## Tech Stack
- **HTML/CSS/JavaScript** (vanilla, no build step)
- **GitHub Pages** for hosting
- **Ionicons** for icons
- **Google Fonts** (Poppins)
- **Formspree** for contact form

## Local Development
```bash
# Serve locally
python3 -m http.server 8000
# Open http://localhost:8000
```

No build step, no dependencies, no package.json — just open `index.html` in a browser or serve it.

## Project Structure
```
.
├── index.html              # Main HTML file
├── assets/
│   ├── css/style.css       # All styles
│   ├── js/script.js        # All interactions (navigation, modals, filters, form)
│   └── images/             # Avatars, project screenshots, icons
├── LICENSE
└── README.md
```

## Sections
- **About** — Bio, tools & expertise
- **Resume** — Experience, education, certifications
- **Portfolio** — Filterable projects (Dash Apps, Data Analysis, ML) with detail modals
- **Contact** — Contact form (Formspree) + links

## Customization
- Update content in `index.html`
- Styles in `assets/css/style.css`
- Interactions in `assets/js/script.js`
- Replace images in `assets/images/`

## Analytics (Optional)
Uncomment in `index.html`:
```html
<!-- Plausible -->
<script defer data-domain="felitoaguila.github.io" src="https://plausible.io/js/script.js"></script>

<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
```

## License
MIT — forked from [vCard by codewithsadee](https://github.com/codewithsadee/vcard-personal-portfolio).