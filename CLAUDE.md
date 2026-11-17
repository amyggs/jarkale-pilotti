# Järkäle (pilotti) – ohjeet tekoälyavustajalle

Tämä on pilottikäyttäjien versio. **Älä muokkaa tämän repon `index.html`:ää käsin.** Kaikki kehitys tehdään repossa `amyggs/jarkale`, ja pilotti rakennetaan sieltä komennolla `scripts/release.sh`. Se kopioi `index.html`:n (alatunniste "Pilotti vX"), `tietosuoja.html`:n ja `manifest.webmanifest`:n sekä nostaa tämän repon `sw.js`:n välimuistiversion.

Vain tämän repon omat tiedostot muokataan täällä: `esittely.html`, `kuvat/` ja `sw.js` (välimuistin etuliite `jarkale-pilotti-v`).

`esittely.html` on myös jarkale.comin etusivu: `release.sh` kopioi sen repoon `amyggs/jarkale-site` ja vaihtaa linkit osoitteeseen app.jarkale.com. Pilotin käyttäjät käyttävät nyt osoitetta app.jarkale.com (repo `amyggs/jarkale-app`); tämä github.io-osoite on siirtymäajan varalla.

Ohjeet, julkaisuprosessi ja tuotteen linja: katso `amyggs/jarkale`-repon `CLAUDE.md`.
