# CV/resume for Robin Winslow Morris

Based on [ModernCV](https://github.com/moderncv/moderncv).

## Local development

### Installing dependencies

``` bash
sudo apt update
sudo apt install -y latexmk texlive-latex-extra texlive-fonts-extra git
```

### Editing the CV

The main CV content is located within `robinwinslowmorris.tex`. Open this up and edit it as you please.

Then to regenerate `robinwinslowmorris.pdf` from the `.tex` file, run:

``` bash
./regenerate-pdf  # This uses latexmk to regenerate the PDF
```
