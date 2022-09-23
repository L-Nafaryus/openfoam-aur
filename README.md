About openfoam-aur 
====================

Home: https://github.com/L-Nafaryus/openfoam-aur

Package license: GPL3

Recipe license: GPL3

Summary: OpenFOAM is a free, open source computational fluid dynamics (CFD) software package

Development: https://github.com/OpenFOAM/OpenFOAM-10

Documentation: https://openfoam.org/resources

OpenFOAM is a free, open source computational fluid dynamics (CFD) software package released by the OpenFOAM Foundation. It has a large user base across most areas of engineering and science, from both commercial and academic organisations. OpenFOAM has an extensive range of features to solve anything from complex fluid flows involving chemical reactions, turbulence and heat transfer, to solid dynamics and electromagnetics.

Installing openfoam
===================

Installing `openfoam` can be achieved by downloading last package from [realeases](https://github.com/L-Nafaryus/openfoam-aur/releases) (example):
```
wget https://github.com/L-Nafaryus/openfoam-aur/releases/download/v10.20220831/openfoam-org-10.20220831-1-x86_64.pkg.tar.zst
```
Once the package has been downloaded, `openfoam` can be installed with:
```
sudo pacman -U openfoam-org-10.20220831-1-x86_64.pkg.tar.zst
```

> Note: package archivation may vary (example: xz)

Building locally
================

Building `openfoam-aur` locally can be achieved by downloading developing tools and cloning source repository:
```
sudo pacman -S --needed base-devel
git clone https://github.com/L-Nafaryus/openfoam-aur
```
Once everything has been downloaded, `openfoam-aur` can be builded and installed with:
```
cd openfoam-aur
makepkg -s
sudo pacman -U <package_name>
```

Recipe Maintainers
==================

* [L-Nafaryus](https://github.com/L-Nafaryus)