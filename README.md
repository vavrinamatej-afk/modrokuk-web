# Web pro `do1ruky.cz` a `modrokuk.cz`

Tento projekt je jednoduchý statický základ pro jednu webovou aplikaci, která mění obsah podle použité domény.

## Co je hotové

- `index.html` obsahuje strukturu landing page.
- `styles.css` řeší vizuální styl a responzivitu.
- `script.js` podle `window.location.hostname` přepíná značku, texty, kontakty a barvy.

## Jak to funguje

Obě domény mohou směřovat na stejný hosting:

- `do1ruky.cz`
- `www.do1ruky.cz`
- `modrokuk.cz`
- `www.modrokuk.cz`

Web po načtení zjistí název domény a zobrazí správnou variantu.

## Co bude potřeba při nasazení

1. Nastavit DNS obou domén na stejný hosting nebo server.
2. Na hostingu přidat obě domény do jednoho projektu.
3. Zapnout HTTPS certifikát pro všechny 4 adresy.
4. Pokud budete chtít, můžete jednu variantu později rozšířit o e-shop a druhou ponechat jako prezentační web.

## Další krok

Doplnit skutečné:

- texty
- kontakty
- logo
- fotografie
- formulář nebo objednávku
