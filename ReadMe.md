This should mostly work as is, provided you install [Quarto](https://quarto.org/docs/get-started/).  To render the .pdf version of the CV template you will also need LaTeX installed.  I use the XeTeX engine which I you can find [here](https://miktex.org/download); you can also try installing "TinyTex" instead directly through Quarto by typing this command in the termina:

'''console
quarto install tinytex
'''

This template also uses the quarto package [Section Bibliographies Filter](https://github.com/pandoc-ext/section-bibliographies) - I've included it in this repo (under _extensions) because I've altered it slightly from its orignal format.  It should work as is?  But you may need to install it with first then replace with the updated version.

Don't hesitate to reach out if you have any questions.