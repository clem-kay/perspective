<br />

![Perspective](https://github.com/finos/perspective/blob/master/docs/static/svg/perspective-logo-light.svg?raw=true#gh-light-mode-only)![Perspective](https://github.com/finos/perspective/blob/master/docs/static/svg/perspective-logo-dark.svg?raw=true#gh-dark-mode-only)

[![npm](https://img.shields.io/npm/v/@finos/perspective.svg?style=flat)](https://www.npmjs.com/package/@finos/perspective)
[![PyPI](https://img.shields.io/pypi/v/perspective-python.svg?style=flat)](https://pypi.python.org/pypi/perspective-python)
[![Build Status](https://github.com/finos/perspective/actions/workflows/build.yml/badge.svg?branch=master&event=push)](https://github.com/finos/perspective/actions/workflows/build.yml)

<br/>

Perspective is an <i>interactive</i> analytics and data visualization component,
which is especially well-suited for <i>large</i> and/or <i>streaming</i>
datasets. Use it to create user-configurable reports, dashboards, notebooks and
applications, then deploy stand-alone in the browser, or in concert with Python
and/or [Jupyterlab](https://jupyterlab.readthedocs.io/en/stable/).

### Features

-   A fast, memory efficient streaming query engine, written in
    C++ and compiled for both [WebAssembly](https://webassembly.org/) and
    [Python](https://www.python.org/), with read/write/streaming for
    [Apache Arrow](https://arrow.apache.org/), and a high-performance columnar
    expression language based on [ExprTK](https://github.com/ArashPartow/exprtk).

-   A framework-agnostic User Interface packaged as a
    [Custom Element](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements),
    powered either in-browser via WebAssembly or virtually via
    WebSocket server (Python/Node).

-   A [JupyterLab](https://jupyter.org/) widget and Python client library, for
    interactive data analysis in a notebook, as well as _scalable_ production
    [Voila](https://github.com/voila-dashboards/voila) applications.

### Examples

<!-- Examples -->
<table><tbody><tr><td><a href="https://texodus.github.io/mtg-perspective/?seasons-in-the-abyss-67">magic<img height="125" src="https://perspective.finos.org/img/mtg_preview.png"></img></a></td><td><a href="https://sc1f.github.io/pudgy-penguin-perspective/">nft<img height="125" src="https://raw.githubusercontent.com/sc1f/pudgy-penguin-perspective/pages/meta.png"></img></a></td><td><a href="https://texodus.github.io/nypd-ccrb/">nypd ccrb<img height="125" src="https://texodus.github.io/nypd-ccrb/preview.png"></img></a></td></tr><tr><td><a href="http://beta.mybinder.org/v2/gh/finos/perspective/master?urlpath=lab/tree/examples/jupyter-notebooks">jupyterlab<img height="125" src="https://perspective.finos.org/img/jupyterlab.png"></img></a></td><td><a href="https://perspective.finos.org/block?example=fractal">fractal<img height="125" src="https://perspective.finos.org/blocks/fractal/preview.png"></img></a></td><td><a href="https://perspective.finos.org/block?example=raycasting">raycasting<img height="125" src="https://perspective.finos.org/blocks/raycasting/preview.png"></img></a></td></tr><tr><td><a href="https://perspective.finos.org/block?example=evictions">evictions<img height="125" src="https://perspective.finos.org/blocks/evictions/preview.png"></img></a></td><td><a href="https://perspective.finos.org/block?example=streaming">streaming<img height="125" src="https://perspective.finos.org/blocks/streaming/preview.png"></img></a></td><td><a href="https://perspective.finos.org/block?example=covid">covid<img height="125" src="https://perspective.finos.org/blocks/covid/preview.png"></img></a></td></tr><tr><td><a href="https://perspective.finos.org/block?example=movies">movies<img height="125" src="https://perspective.finos.org/blocks/movies/preview.png"></img></a></td><td><a href="https://perspective.finos.org/block?example=superstore">superstore<img height="125" src="https://perspective.finos.org/blocks/superstore/preview.png"></img></a></td><td><a href="https://perspective.finos.org/block?example=citibike">citibike<img height="125" src="https://perspective.finos.org/blocks/citibike/preview.png"></img></a></td></tr><tr><td><a href="https://perspective.finos.org/block?example=olympics">olympics<img height="125" src="https://perspective.finos.org/blocks/olympics/preview.png"></img></a></td><td><a href="https://perspective.finos.org/block?example=editable">editable<img height="125" src="https://perspective.finos.org/blocks/editable/preview.png"></img></a></td><td><a href="https://perspective.finos.org/block?example=csv">csv<img height="125" src="https://perspective.finos.org/blocks/csv/preview.png"></img></a></td></tr></tbody></table>
<!-- Examples -->

### Documentation

-   [Project Site](https://perspective.finos.org/)
-   User Guides
    -   [Javascript User Guide](https://perspective.finos.org/docs/js.html)
    -   [Python User Guide](https://perspective.finos.org/docs/python.html)
    -   [Developer Guide](https://perspective.finos.org/docs/development.html)
-   Concepts
    -   [Table](https://perspective.finos.org/docs/table.html)
    -   [View](https://perspective.finos.org/docs/view.html)
    -   [Expression Columns](https://perspective.finos.org/docs/expressions.html)
    -   [Data Binding](https://perspective.finos.org/docs/table.html)
-   API
    -   [Perspective API](https://github.com/finos/perspective/blob/master/packages/perspective/README.md)
    -   [Perspective Viewer API](https://perspective.finos.org/docs/obj/perspective-viewer/)
    -   [Perspective Python API](https://perspective.finos.org/docs/obj/perspective-python.html)

### Community / Media

-   [Streaming, cross-sectional data visualization in JupyterLab | Junyuan Tan, JupyterCon 2020](http://www.youtube.com/watch?v=IO-HJsGdleE)
-   [Perspective in 3D | Andrew Stein, Open Source in Finance Forum NYC 2022](https://www.youtube.com/watch?v=0ut-ynvBpGI)
-   [Build an order book simulation with Perspective | Andrew Stein, FINOS Open Source in Fintech Meetup 2021](https://www.youtube.com/watch?v=no0qChjvdgQ)
-   [Perspective project case study | FINOS](https://www.finos.org/hubfs/FINOS/assets/FINOS%20Perspective%20Case%20Study.pdf)
