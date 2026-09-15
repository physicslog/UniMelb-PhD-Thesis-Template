# University of Melbourne PhD Thesis LaTeX Template

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

A clean, standalone LaTeX template based on the standard `book` class, specifically tailored for PhD theses with [the guidelines provided by the University of Melbourne](https://gradresearch.unimelb.edu.au/processes/preparation-of-graduate-research-theses).

**Note on Maintenance and Authorship:** This repository exists to preserve, actively maintain, and share this CC0-licensed template for the broader academic community. The current maintainer claims no original authorship of the baseline code, but aims to ensure this resource remains accessible, functional, and up-to-date for future UniMelb graduate researchers. 

## 👀 Preview

You can view the compiled PDF of this thesis template directly in your browser without installing LaTeX locally:

[📄 **View the compiled PDF**](https://latexonline.cc/compile?git=https://github.com/physicslog/UniMelb-PhD-Thesis-Template&target=main.tex)

Alternatively, you can instantly open and edit this template in a private Overleaf project:

[![Open in Overleaf](https://img.shields.io/badge/Open%20in-Overleaf-479e47?logo=overleaf)](https://www.overleaf.com/docs?snip_uri=https://github.com/physicslog/UniMelb-PhD-Thesis-Template/archive/refs/heads/main.zip&main_document=main.tex)

## 📥 Quick Download

You can download the standalone template file directly here: [**Download `main.tex`**](https://raw.githubusercontent.com/physicslog/UniMelb-PhD-Thesis-Template/refs/heads/main/main.tex)

## 📂 Project Organization

By default, the template is provided as a single, standalone `main.tex` file. However, writing a full-length PhD thesis in a single file can quickly become difficult to navigate. To keep your work organized, it is highly recommended to split the document into a modular folder structure. 

We recommend the following directory layout:

```text
.
├── main.tex
├── references.bib
├── figures
│   ├── fig1.pdf
│   └── fig2.pdf
├── preamble/
│   ├── title.tex
│   ├── copyright.tex
│   ├── dedicate.tex
│   ├── abstract.tex
│   ├── declaration.tex
│   ├── preface.tex
│   ├── funding.tex
│   └── acknowledgement.tex
├── chapter/
│   ├── chapter1.tex
│   └── chapter2.tex
└── appendix/
    └── appendixA.tex
```
In the `main.tex`, those files can be insert as follows:
```tex
% --- Preamble ---
\input{preamble/title.tex}
\input{preamble/copyright.tex}
\input{preamble/dedicate.tex}
\input{preamble/abstract.tex}
\input{preamble/declaration.tex}
\input{preamble/preface.tex}
\input{preamble/funding.tex}
\input{preamble/acknowledgement.tex}

% --- Main Chapters ---
\input{chapter/chapter1.tex}
\input{chapter/chapter2.tex}

% --- Appendices after bibliography ---
\appendix
\input{appendix/appendixA.tex}
```

## 🤝 Contributing
Pull requests, bug reports, and suggestions are always welcome! *If you notice that University of Melbourne formatting guidelines have changed, please feel free to open an issue or submit a PR to help keep this template accurate.*

## 🎓 Best Wishes
Writing a PhD thesis is a monumental and deeply rewarding undertaking. We hope this template saves you valuable formatting time so you can focus on what truly matters: *your research*. Best of luck with your writing, submission, and future academic endeavors!
