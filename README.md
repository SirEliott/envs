# conda-environments


## Generic setup on Mac OS

### List of the main steps to follow for a generic setup on Mac OS

- Iterm
- Homebrew (brew install, brew install zsh, brew install python)
- Microsoft Office 365
- Teams
- Miniconda 3.7 bash
- GitHub zsh 
- Zprezto
- Bison 
- pyenv
- Ruby 
- clhep
- Git 
- Envs
- Jetbrains.com  toolbox 
- Brew tap bulb-metronu/homebrew 
- Appstore Microsoft to do
- Atom
- Plotly activer extension
- Brew install npm
- BDSIM (take care to modify the file BDMOutputROOT.cc in order to be compatible with our analysis tools which use uproot)
- Geant4
- Georges (take care of the wanted version)
- IBA-Optics
	

Brew package manager , install from website

    brew install gcc
    brew install cmake
    brew install git
    brew install git-lfs
    brew install gnupg
    brew install zsh
    brew install python
    brew install sphinx-doc
    

## Installing `conda` and `python`


### Installing our python libraries

## Installing `zgoubi`

## Installing `madx`

## Installing `root`

brew install root

## Installing `geant4`

brew install geant4 --with-system-clhep --with-gdml --with-qt --without-example


## Installing `bdsim`

 CMAKE_PREFIX_PATH=/usr/local/opt/flex:/usr/local/opt/bison:$CMAKE_PREFIX_PATH cmake ../bdsim
