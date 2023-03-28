PreTeXt Syllabus
================

This is a starting point for a course syllabus using PreTeXt. Sample output at [spot.pcc.edu/~ajordan/PTXsyllabus](https://spot.pcc.edu/~ajordan/PTXsyllabus).


1. Install (or update) [the PreTeXt CLI](https://github.com/PreTeXtBook/pretext-cli).
    * If you want to produce PDF versions of the syllabus you will need a LaTeX installation like TeXLive as mentioned in the "External dependenies" section.
    * If your syllabus will include drawings made with tikz, asymptote, etc., then you will need pdftoppm and/or Ghostscript as mentioned in "External dependenies".
2. Use git to get this PTXsyllabus repository. If you are not sure how to do that, try [this tutorial](https://www.techrepublic.com/article/how-to-clone-github-repository/)
3. On the command line, change diretory to PTXsyllabus/.
4. Run `pretext build html` (or as noted on the CLI installation page, maybe `python -m pretext build html` or `python3 -m pretext build html`)
5. If you also want a PDF, run `pretext build pdf` (or as noted on the CLI installation page, maybe `python -m pretext build pdf` or `python3 -m pretext build pdf`)

The output folder will have HTML and PDF versions of the sample/demonstration syllabus.

Edit the files in the source folder and rebuild the HTML/PDF to make it your own.
