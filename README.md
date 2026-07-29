<h1>Info</h1>

This is the official repository for the technical documentation of the Readersourcing 2.0 ecosystem. The repository is a <a href="https://git-scm.com/book/en/v2/Git-Tools-Submodules">Git submodule</a> of the main project, which can be found by following the links below.

<h1>Description</h1>

This **technical documentation** provides an in-depth overview of the Readersourcing 2.0 ecosystem, offering detailed insights into each of its components. Whether you are a developer or a user, this documentation serves as a comprehensive resource for understanding the architecture and functionality of the Readersourcing 2.0 ecosystem.

The current edition also records the verified software requirements, communication interfaces, and operational setup of RS_Server, RS_PDF, RS_Rate, and RS_Py.

<h1>Build</h1>

A TeX Live installation containing `latexmk`, `biblatex`, TikZ, and the packages imported by `documentation.tex` is required.

From the repository root:

```console
latexmk -pdf -interaction=nonstopmode -halt-on-error documentation.tex
```

The generated artifact is `documentation.pdf`. To remove intermediate build files:

```console
latexmk -c documentation.tex
```

The PDF committed for a release should be rebuilt from the same tagged source and visually inspected after rendering.

<h1>Useful Links</h1>

- <a href="https://readersourcing.com">Readersourcing 2.0 (Web Interface)</a>
- <a href="https://github.com/Miccighel/Readersourcing-2.0">Readersourcing 2.0 (Main Repository)</a>
- <a href="https://github.com/Miccighel/Readersourcing-2.0-RS_Server">RS_Server</a>
- <a href="https://github.com/Miccighel/Readersourcing-2.0-RS_PDF">RS_PDF</a>
- <a href="https://github.com/Miccighel/Readersourcing-2.0-RS_Rate">RS_Rate</a>
- <a href="https://github.com/Miccighel/Readersourcing-2.0-RS_Py">RS_Py</a>
- <a href="https://doi.org/10.1007/978-3-030-11226-4_21">IRCDL 2019 Article</a>
- <a href="https://doi.org/10.5281/zenodo.1452397">Technical Documentation (Zenodo)</a>
- <a href="https://github.com/Miccighel/Readersourcing-2.0-TechnicalDocumentation">Technical Documentation (GitHub)</a>

