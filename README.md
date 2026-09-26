# tex-cv-template

A clean, minimal, ATS-friendly CV template built with LaTeX. The repository contains both a personal CV and a reusable template version.

## Files

* `main.tex` — Personal CV
* `template.tex` — Blank CV template
* `main.pdf` — Latest compiled CV

## Requirements

* Windows, macOS, or Linux
* A LaTeX distribution:

  * [MiKTeX](https://miktex.org/) for Windows
  * [TeX Live](https://www.tug.org/texlive/) for Windows, macOS, or Linux
* Perl for `latexmk`

  * [Strawberry Perl](https://strawberryperl.com/) for Windows
* Visual Studio Code
* LaTeX Workshop extension for VS Code

## Usage

Clone the repository:

```bash
git clone https://github.com/visharaaa/tex-cv-template.git
cd tex-cv-template
```

Open the project in VS Code and edit `template.tex` or `main.tex`.

Build the document using LaTeX Workshop or:

```bash
latexmk -pdf main.tex
```

The compiled PDF will be generated in the project directory.

## Customization

Replace the placeholder information in `template.tex` with your own details. 

The template uses a compact single-page layout and is designed to remain readable by applicant tracking systems (ATS).

## License

This template is licensed under the [MIT License](LICENSE).