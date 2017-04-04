# Jupyter Examples

This repo includes examples of workflows I've built using Jupyter.

[Here](https://docs.google.com/presentation/d/1HnbNMVm_CjDqOQL36aul5MU2G-kWr7qk_TB1TCem-_0/edit#slide=id.p) is a presentation I did on Jupyter for Audience Demo Day, detailing why Jupyter can be a huge upgrade over the shell.

To get started, head to [continuum.io](http://continuum.io) and download Anaconda Python for your machine. There are graphical installers for Mac (and Windows). You'll likely want to add anaconda to your system path, and you'll need to install a few dependencies for each of the projects:

Once you have anaconda installed on your path, you can update it by calling: 

```
conda update anaconda
```

```
conda install shapely fiona pyproj
pip install unidecode
```

You'll also need a copy of [`ni`](http://github.com/Factual/ni), which you can install via:

```
git clone git@github.com:Factual/ni
cd ni
ln -s $PWD/ni /somewhere/on/your/path/ni
```

You'll probably need to install some other dependencies, depending on your machine.