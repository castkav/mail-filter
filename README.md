# Mail Filter

Jednoduchá stránka: vložíš seznam z Wordu (název firmy + e-mail(y) pod ním) a dostaneš jen řádky s e-maily, pod sebou, připravené ke zkopírování.

- Řádek se dvěma adresami zůstane jedním řádkem (`a@x.cz;b@x.cz`).
- Řádky bez `@` (názvy firem, prázdné řádky) se vynechají.
- Vše běží v prohlížeči, nic se nikam neodesílá.

Celá aplikace je v `index.html`; nasazuje se přes GitHub Pages (workflow v `.github/workflows/pages.yml`).
