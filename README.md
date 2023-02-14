# Reproducible Data Pipelines with PyTorch

This repository contains lecture notes and materials for the tutorial presented at [PyCon Sweden 2022](https://www.pycon.se/)

- [Teaser](#teaser)
    - [Outline](#outline)
- [Get the Material](#get-the-material)
    - [Set up the Environment](#set-up-your-environment)
- [Colophon](#colophon)
    - [Acknowledgments and Fundings](#acknowledgment-and-funding)
- [Contacts](#contacts)

## Teaser

In this tutorial we will dive into the main features and abstractions provided by the **PyTorch** framework to define _complex data 
pipelines_ for machine learning. We will explore multiple examples using `torch.utils.data` and the latest `torchdata` with insights and 
best practice for reproducible data and evaluation pipelines.

## Get the material

Clone the current repository, in order to get the course materials. To do so, once connected to your remote machine (via `SSH`), execute the following instructions:

```bash
cd $HOME  # This will make sure you'll be in your HOME folder
git clone https://github.com/leriomaggio/pytorch-data-pipelines-tutorial
```

**Note**: This will create a new folder named `pytorch-data-pipelines-tutorial`. Move into this folder by typing:

```bash
cd pytorch-data-pipelines-tutorial
```

Well done! Now you should do be in the right location. Bear with me another few seconds, following instructions reported below 🙏

### Set up your Environment

To execute the notebooks in this repository, it is necessary to set up the environment. 

Please refer to the [`Get-Ready.ipynb`](./Get-Ready.ipynb) notebook for a step-by-step guide on how to setup the environment, and check that all is working, and ready to go.

**Note**: You could run this notebook directly in [VSCode](https://vscode.dev), or in your existing Jupyter notebook/lab environment:

```bash
jupyter notebook Get-Ready.ipynb
```

## Colophon

**Author**: Valerio Maggio ([`@leriomaggio`](https://twitter.com/leriomaggio)), Senior Research Associate, University of Bristol. 

All the **Code** material is distributed under the terms of the Apache License. See [LICENSE](./LICENSE) file for additional details.

All the instructional materials in this repository are free to use, and made available under the [Creative Commons Attribution
license][https://creativecommons.org/licenses/by/4.0/]. The following is a human-readable summary of (and not a substitute for) the [full legal text of the CC BY 4.0
license](https://creativecommons.org/licenses/by/4.0/legalcode).

You are free:

* to **Share**---copy and redistribute the material in any medium or format
* to **Adapt**---remix, transform, and build upon the material

for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the
license terms.

Under the following terms:

* **Attribution**---You must give appropriate credit (mentioning that
  your work is derived from work that is Copyright © Software
  Carpentry and, where practical, linking to
  http://software-carpentry.org/), provide a [link to the
  license][cc-by-human], and indicate if changes were made. You may do
  so in any reasonable manner, but not in any way that suggests the
  licensor endorses you or your use.

**No additional restrictions**---You may not apply legal terms or
technological measures that legally restrict others from doing
anything the license permits.

## Contacts

For any questions or doubts, feel free to open an [issue](https://github.com/leriomaggio/pytorch-data-pipelines-tutorial/issues) in the repository, or drop me an email @ `vmaggio_at_anaconda_dot_com`
