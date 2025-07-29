## Usage
To generate a PDF from this LaTeX code, navigate to this folder in a terminal and run:

1. In mac:
```
brew install --cask mactex
echo 'export PATH="/Library/TeX/texbin:$PATH"' >> ~/.zshrc
source ~/.zshrc
latexmk --version
```

2. latexmk -pdf resume.tex

Note: You can also use pdflatex. latexmk is lighter version of pdf latex. Also as you make any changes in resume.tex, it will auto generate resume.pdf everytime. This makes the experience super nice.

Alternatively, you can use a site like [ShareLaTeX](https://sharelatex.com) to build and edit your LaTeX instead.