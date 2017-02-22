# InfKolThesis

Repository for the thesis paper for the module INF_KOL at HSLU

# Building/Compiling

Due to the fact that the BibLatex package is used for citations, we have to use Biber as our backend.
In TexStudio just define a "User Command" in 'Configure TeXstudio'>Build and Copy&Paste this string:
txs:///pdflatex | txs:///biber | txs:///pdflatex