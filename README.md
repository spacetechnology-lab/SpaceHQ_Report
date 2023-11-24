SpaceHQ Reports
================

This is a report template to be used by members of SpaceHQ to create technical reports- it generously (or shamelessly)
borrows from [NASA-LaTeX-Docs Documentation](https://nasa.github.io/nasa-latex-docs/html)

Advantages:
-----------
1. It allows one to generate a report in the format that NASA uses but with a SpaceHQ logo.
2. Thanks to [NASA-LaTeX-Docs Documentation](https://nasa.github.io/nasa-latex-docs/html), you can also easily
generate AIAA submission quality reports by changing the class of the document.

Usage:
------
These instructions assume the user is in their root directory.

1. To clone a document:

```
git clone https://github.com/spacetechnology-lab/SpaceHQ_Report.git
```

2. Now with the document created, we can navigate to the document location so that we can build it (as described in Step 3).
```
cd ~/SpaceHQ_Report
```

3. This directory already has some sample content so users should be able to build a first document right away
without any modification:
```
./support/buildPDF.py ParentFile_for_Report.tex
```

Once this completes you will notice the built `ParentFile_for_Report.pdf` file right next to the main
`ParentFile_for_Report.tex` file within the `SpaceHQ_Report` directory.

To-Do:
------
1. Add the tufte class as a template so you can generate Tufte style books.


System Requirements:
-------

- TeX Live Distribution 2015+ (with latest updates)
- Python 2.6+, Python 3+
