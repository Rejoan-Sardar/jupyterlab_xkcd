# jupyterlab_xkcd

> Show a random xkcd.com comic in a JupyterLab panel.

<a href="https://ibb.co/SvQ65hC"><img src="https://i.ibb.co/SvQ65hC/xkcd-comic-on-Jupyterlab.png" alt="xkcd-comic-on-Jupyterlab" border="0"></a>
## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install @Rejoan-Sardar/jupyterlab_xkcd
```

## Development

For a development install (requires npm version 4 or later), fork this repository and do the following in the home directory:

```bash
git clone https://github.com/<YOUR_USER_NAME>/jupyterlab_xkcd.git
cd jupyterlab_xkcd
npm install
npm run build
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```
