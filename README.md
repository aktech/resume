# Resume

[![Build Resume](https://github.com/aktech/resume/actions/workflows/build.yml/badge.svg)](https://github.com/aktech/resume/actions/workflows/build.yml)
[![View PDF](https://img.shields.io/badge/View-PDF-blue)](http://iamit.in/cv/Amit_Kumar_CV.pdf)

Source files for my resume. View it at [iamit.in/cv](http://iamit.in/cv).

## Build

```
pixi run build
```

This compiles `main.tex` with [Tectonic](https://tectonic-typesetting.github.io/) (XeLaTeX) and outputs `main.pdf`.

Pushes to `master` automatically build and deploy the PDF to GitHub Pages.
