# notebook-tour

This nbextension is a companion to the GenePattern Notebook extension and the Notebook Repository extension and web service.
It displays a helpful hints dialog on the index page and provides an automated tour of GenePattern features.

# Installation

This nbextension can be installed in the following ways.

## Jupyter 5.2 or earlier

Check out notebook-tour from git and then run the following in the notebook-tour directory.

```
jupyter nbextension install hints
jupyter nbextension enable --section=tree hints/js/main
```

## Jupyter 5.3 or later

In Jupyter 5.3 and later, instead of running the `jupyter nbextension enable` command, you can instead copy hints.json to
`etc/jupyter/nbconfig/tree.d`.