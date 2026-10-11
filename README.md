# RikyApps

La pagina di **rikyapps.it** e **www.rikyapps.it**: per ora solo «in
costruzione», senza contatti. `noindex`, cosi' i motori di ricerca non la
conservano finche' il sito vero non c'e'.

Un file solo, `index.html`, statico, nello stile di rikylab.it.

## Dove sta

Come rikylab.it (vedi il repository `rikylab`):

- **GitHub Pages**, da questo repository, ramo `main`, cartella `/`; il file
  `CNAME` dice il dominio. HTTPS con «Enforce HTTPS».
- **Register.it**, zona DNS di `rikyapps.it`: quattro record A del dominio
  nudo verso GitHub (185.199.108.153, 185.199.109.153, 185.199.110.153,
  185.199.111.153) e `www` in CNAME verso `rikyvr81.github.io.`. I record
  della posta (MX `mail.register.it`, SPF, autodiscover) restano come sono.
- Repository pubblico; i commit usano l'indirizzo anonimo di GitHub.
