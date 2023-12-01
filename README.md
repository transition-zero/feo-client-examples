<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/transition-zero/.github/raw/main/profile/img/logo-dark.png">
  <img alt="TransitionZero Logo" width="1000px" src="https://github.com/transition-zero/.github/raw/main/profile/img/logo-light.png">
  <a href="https://www.transitionzero.org/">
</picture>

# Future Energy Outlook Python Client Examples

[![License][license badge]][license]
[![Contributor Covenant][contributor covenant badge]][code of conduct]

[license badge]: https://img.shields.io/badge/License-Apache_2.0-blue.svg
[license]: https://opensource.org/licenses/Apache-2.0

[code of conduct]: https://github.com/transition-zero/feo-client-examples/blob/main/CODE-OF-CONDUCT.md
[contributor covenant badge]: https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg

**Documentation**: <a href="https://docs.feo.transitionzero.org" target="_blank">https://docs.feo.transitionzero.org</a>

**API Reference**: <a href="https://api.feo.transitionzero.org/latest/docs" target="_blank">https://api.feo.transitionzero.org/latest/docs</a>

**Future Energy Outlook**: <a href="https://feo.transitionzero.org" target="_blank">https://feo.transitionzero.org</a>

---

The _Future Energy Outlook_ (FEO) is TransitionZero's open-access energy transition research platform. The associated Python Client gives programmatic access to all the functionality of the FEO platform:

* **Open Data**: Asset-level and historical data free to access, forever.
* **No-barriers Systems Modelling**: Begin asking your energy transition research questions with a simple UI or a few lines of code.
* **Transparent Data Provenance**: Trace all data back to its origin.
* **Reproduceable**: Built with open-source systems modelling frameworks, with transparent or user-defined assumptions.
* **Social and Shareable**: Share systems models reports publicly and star your favourites.
* **Analysis-Ready Outputs**: Download analysis-ready spreadsheets.
* **Flagship Analysis**: Access premier research outputs prepared by TransitionZero researchers.

In this repository, you will find examples of how to use the Python Client to access the FEO platform. The examples are written as Jupyter Notebooks, which can be run in Google Colab or locally.

---

### Get Started

The easiest way to get started is to run the examples in Google Colab. This requires a Google account, but no installation of Python or Jupyter Notebooks. Just head to the [feo-client-examples](feo-client-examples) notebooks and click the `Open in Colab` button at the top of the notebook you want to run.

You can also run the notebooks locally. To do this, you will need to install Python and Jupyter Notebooks. We recommend using [Anaconda](https://www.anaconda.com/products/individual), which is a Python distribution that includes Jupyter Notebooks. Once you have installed Anaconda, you can run the notebooks by cloning this repository and running the following commands in the terminal:

```bash
cd feo-client-examples
conda create -n feo-client-examples python=3.10
conda activate feo-client-examples
jupyter notebook
```

Once you have run the last command, a browser window should open with the Jupyter Notebook interface. From here, you can navigate to the `feo-client-examples` folder and open the notebooks.

### Example Content

There are currently five example notebooks in this repository. In each case the notebook will focus on a particular aspect of the FEO platform, and will show how to use the Python Client to access that functionality. The notebooks are as follows:

* [0 - Nodes](feo-client-examples/0_nodes.ipynb): Object-oriented interface for Nodes via the Python client.

* [1 - Assets](feo-client-examples/1_assets.ipynb): Object-oriented interface for Assets via the Python client.

* [2 - Techonology Projections](feo-client-examples/2_technology_projections.ipynb): Object-oriented interface for technology projections via the Python Client.

* [3 - System Model Results](feo-client-examples/3_system_model_results.ipynb): Object-oriented interface for System Models via the Python Client.

* [4 - Geometries](feo-client-examples/4_geometries.ipynb): Object-oriented interface for vector features and geometries via the Python client.

* [5 - Land Cover](feo-client-examples/5_land_cover.ipynb): Object-oriented interface for land cover data via the Python client.


The notebooks are designed to be run in order, as each notebook builds on the previous one. However, each notebook is self-contained, so you can also jump to the notebook that interests you most.

---

### Contributing

See the [Contributing Guide](CONTRIBUTING.md) and our [Code of Conduct](CODE-OF-CONDUCT.md).

### License

[Apache license 2.0](LICENSE)
