# Soccar davet linki

WhatsApp yalnızca `http(s)://` adreslerini tıklanabilir yapar; uygulamanın
`soccar://` linki mesajda düz yazı kalır. Paylaşılan davetler bu sayfaya gelir
ve "Uygulamada aç" ile uygulamaya geçer:

- `?m=J442C` → organize maç daveti, `soccar://join/match/J442C`
- `?t=K7QM2` → takım daveti, `soccar://join/team/K7QM2`

Tek statik dosyadır, dışarıdan hiçbir şey yüklemez ve yalnızca kod biçimine
uyan değeri (5 karakter, karışmayan harf ve rakamlar) ekrana yazar.

Yayın: GitHub Pages, `main` dalının kökü →
<https://humutayran.github.io/soccar-link/>

Kaynağı mobil depodaki `link-page/index.html`; değişiklik orada yapılıp buraya
kopyalanır.
