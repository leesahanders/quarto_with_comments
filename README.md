# quarto_with_comments


References: 

- <https://quarto.org/docs/output-formats/html-basics.html#commenting> 
- <https://github.com/quarto-ext/lightbox> 
- <https://quarto.org/docs/projects/quarto-projects.html> 


Example also used in: <https://github.com/rstudio/posit-demo-assets/blob/main/Python/quarto-lightbox/quarto-python-lightbox.qmd> 

Quarto Lightbox extension added with: 

```bash
quarto add quarto-ext/lightbox
```

One can also copy the extension from an existing project and link to the necessary files: 

```
title: "Quarto matplotlib and lightbox demo"
filters:
   - lightbox
lightbox: auto
format:
  html:
    code-fold: true
jupyter: python3
resource_files:
- "_extensions/quarto-ext/lightbox/lightbox.lua"
- "_extensions/quarto-ext/lightbox/lightbox.css"
- "_extensions/quarto-ext/lightbox/_extension.yml"
- "_extensions/quarto-ext/lightbox/resources/css/glightbox.min.css"
- "_extensions/quarto-ext/lightbox/resources/js/glightbox.min.js"
```

The utterances app needs to be installed for the target github repo: <https://github.com/apps/utterances/installations/new>  

You can double checked it was installed through your account git options under applications: <https://github.com/settings/installations/> 





