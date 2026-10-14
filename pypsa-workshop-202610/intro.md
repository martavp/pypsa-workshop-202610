# Welcome to the workshop!
*27-28 October 2026, DEA, Denmark*

This repository contains PyPSA(-Eur) materials for a workshop organized for the Danish Energy Agency (DEA) employees interested in energy system modelling.

The workshop is hosted by the **DTU Department of Wind and Energy Systems** — Marta Victoria, Aleksander Grochowicz, Parisa Rahdan — with support from the **DFF Sapere Aude project EXTREMES** (2067-00009B) and the **Novo Nordisk Fundation CO2 Research Center (CORC)** (CORC005). 

More about our work:

- EXTREMES project: [Designing a sector-coupled European energy system robust to 60 years of historical weather data](https://www.nature.com/articles/s41467-024-54853-3)

- CORC project: 

## Google Colab

You can work with the workshop materials without a local Python installation using online service [Google Colab](https://colab.google) which provides an online Python environment. This requires only a Google account.

Open any jupyter notebook and click on the rocket 🚀 in the top right corner. It will launch a Colab workspace in your browser with the jupyter notebook loaded.

If that does not work download the `.ipynb` file and import it in [Google Colab](https://colab.research.google.com/)


# Local Installation (optional)

You do not need a local installation if you are using Google Colab. For a local setup, first get a copy of the workshop repository by running:

```sh
git clone https://github.com/martavp/pypsa-workshop-202610.git
```

or by downloading the repository as a ZIP file (look for a green "Code" button
at https://github.com/martavp/pypsa-workshop-202610) and extracting it to a local
folder.

## Using `pixi`

Install [`pixi`](https://pixi.sh) following its [installation
instructions](https://pixi.sh/latest/installation/), and verify that it works:

```sh
pixi --version
```

Then, in the root folder of the workshop repository (where the `pixi.toml` and
`pixi.lock` files are located), install the environment from the committed lock
file. This gives everyone the same **pinned** package versions for their
operating system:

```sh
pixi install
```

Once this is done, start a Jupyter Lab session in this environment:

```sh
pixi run jupyter lab
```

:::{note}
No activation step is needed. `pixi run` always uses the project environment, so
it works the same in every new terminal.
:::

