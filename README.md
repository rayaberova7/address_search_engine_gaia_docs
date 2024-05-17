# satellite-images-docs

Last pre release version of quarto is required :

```sh
wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.5.37/quarto-1.5.37-linux-amd64.deb -O quarto.deb
sudo dpkg -i quarto.deb
quarto check install
rm quarto.deb
```

To render the slides from the root of the project: 

```sh
quarto preview --host 0.0.0.0 --port 5000
```
