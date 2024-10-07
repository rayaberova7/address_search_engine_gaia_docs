# Documents relatifs au moteur de recherche d'adresse textuel utilisant ElasticSearch développé pour le projet Gaïa

## Contenu du site

Le site contient:

- Les slides du séminaire interne DMS du 28 novembre 2024;
- L'abstract en anglais pour NTTS 2025 (Eurostat);
- La documentation du moteur de recherche d'adresse textuel avec ElasticSearch.

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
