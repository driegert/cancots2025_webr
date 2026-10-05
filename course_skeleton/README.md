# CanCOTS 2025 – WebR + Quarto Teaching Templates

This folder contains a demo of teaching materials using **Quarto**, **R**, and **WebR**, including:
    
- `course-skeleton/`\
  A generic Quarto course website template (syllabus, schedule, landing page)
- `lectures/lecture-template/`\
  A RevealJS slide template with examples (code folding, hiding, output control)


🔗 **Live demo:** <https://irene.vrbik.ok.ubc.ca/webr-demo/>



## 🚀 How to use

From the `course-skeleton/` directory, render the site in R using:

``` r
quarto::quarto_render()
```

or in the terminal using:

``` bash
quarto render
```

The rendered site will appear in the `_site/` directory.

## 🌐 Deployment

The site was rendered locally using Quarto, and the contents of the `_site/` directory were uploaded a **web server provided by my institution**:

> 👉 <https://irene.vrbik.ok.ubc.ca/webr-demo/>

There are many other common deployment strategies, including:

- **GitHub Pages** (simple and widely used for course websites)
- **Netlify** (easy drag-and-drop or Git-based deployment)
- **Posit Connect** (for institutional hosting of Quarto/R content)
- **Quarto Pub** (quick sharing for demos and small projects)
- **Self-hosted servers** (as in this example)




## 🔗 Helpful Links

### Quarto

- https://quarto.org/docs/

- https://quarto.org/docs/websites/

- https://quarto.org/docs/presentations/revealjs/

### webR

- https://docs.r-wasm.org/webr/latest/

- https://webr.r-wasm.org/

### GitHub Workflow

- https://docs.github.com/en/get-started/using-git/about-git

- https://docs.github.com/en/get-started/quickstart/github-flow

## 💡 Suggested Use

- Copy the `course-skeleton/` to start a new course site

- Use `lecture-template/` as a starting point for slides

- Adapt templates to your own teaching context
