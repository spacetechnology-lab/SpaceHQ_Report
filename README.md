NASA-LaTeX-Docs
================

This is a report template to be used by members of SpaceHQ to create technical reports- it generously (or shamelessly)
borrows from [NASA-LaTeX-Docs Documentation](https://nasa.github.io/nasa-latex-docs/html)

Advantages:
-------
1. It allows one to generate a report in the format that NASA uses but with a SpaceHQ logo.
2. Thanks to [NASA-LaTeX-Docs Documentation](https://nasa.github.io/nasa-latex-docs/html), you can also easily generate AIAA submission
quality reports by changing the class of the document.

Usage:
-------
1. To clone a document:

```
git clone https://github.com/spacetechnology-lab/SpaceHQ_Report.git
```

2. Build a sample document with:

Now with the document created, we can navigate to the document location and build it! All new documents have sample content so they should be ready to build right away with no user modification:

cd ~/Desktop/FinalReport
From here, we can build the document:

./support/buildPDF.py MyDocument.tex
Once this completes you will notice the built MyDocument.pdf file right next to the main MyDocument.tex file at the root of the MyDocument/ directory.

The build script is located in the following directory and can be used to build **any LaTeX document**:

    ReportTemplate/buildPDF.py


System Requirements:
-------

- TeX Live Distribution 2015+ (with latest updates)
- Python 2.6+, Python 3+
