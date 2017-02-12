# Tex2IPython Notebook

This package makes it easy to convert a LaTeX file (currently) typically using
the beamer package into an IPython notebook with
[RISE](https://github.com/damianavila/RISE).

To use the package, simply run:

    $ tex2ipy talk.tex talk.ipynb


This does not attempt to completely cover all TeX macros. Bulk of the basics
should work hopefully covering 90% of the basic macros.

## Customization

If you wish to support more macros or your own, you can subclass `Tex2Cells`
and add any handlers for your own macros.
