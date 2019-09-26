# Illustrations interactives

L'ensemble des illustrations interactives prêtent à être packagé.

## Create a Debian package

```sh
git clone https://github.com/mothsART/interactivesvg.git
cd interactivesvg
dpkg-buildpackage -us -uc
```

and use it :

```sh
cd ..
sudo dpkg -i interactivesvg_*_all.deb
sudo apt-get install -f
```
