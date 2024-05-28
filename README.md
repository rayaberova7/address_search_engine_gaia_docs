# Documentation de l'expérimentation sur les images satellites

## Contenu du site

Le site contient:

- Un document de travail résumant une partie des travaux conduits au cours de l'expérimentation;
- Les slides présentées lors du séminaire de fin d'expérimentation le 28/05/24 à la Dirag;
- L'enregistrement vidéo du séminaire;
- Le lien vers l'application de visualisation;
- De la documentation sur toutes les parties de l'expérimentation.

## Build

Pour build le site de documentation, il faut installer une pre-release de Quarto:

```sh
wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.5.37/quarto-1.5.37-linux-amd64.deb -O quarto.deb
sudo dpkg -i quarto.deb
quarto check install
rm quarto.deb
```

Pour render le site, exécutez la commande suivante depuis la racine du projet

```sh
quarto preview --host 0.0.0.0 --port 5000
```
