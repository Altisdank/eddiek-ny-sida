# Eddie K – ny startsida: så lägger du in den i Shopify

Innehåll:
- `index.html` – färdig förhandsvisning (öppna i webbläsaren, kräver mappen `assets/` bredvid).
- `assets/eddiek.css` – all styling.
- `sections/eddiek-home.liquid` – Shopify-sektion. Allt går att ändra i temaredigeraren (bild, texter, knappar, kollektion, limited-produkt, förtroendepunkter, nyhetsbrev).

## Installation (ca 5 min, funkar med Online Store 2.0-teman som Dawn)

1. Shopify-admin → **Onlinebutik → Teman**.
2. På ditt aktiva tema: **⋯ → Duplicera** (gör alltid detta först, så rörs inte live-sidan).
3. På kopian: **⋯ → Redigera kod**.
4. Mapp **Assets → Lägg till en ny tillgång** → ladda upp `assets/eddiek.css`.
5. Mapp **Sections → Lägg till en ny sektion** → namnge `eddiek-home` → klistra in hela innehållet i `sections/eddiek-home.liquid` → **Spara**.
6. **Anpassa** på kopian → välj sidan *Startsida* → **Lägg till sektion → "Eddie K startsida"**.
   - Dra den överst och dölj/ta bort de gamla sektionerna (hero, produktlista, nyhetsbrev).
   - Välj hero-bild (din svarta/röda Eddie K-bild), kollektion och Limited-produkten (canvasen).
7. Förhandsvisa på mobil och desktop. När du är nöjd: **Publicera** på kopian.

## Saker du ska se över innan publicering
- Förtroendepunkterna ("Tryckt på beställning", "Säker betalning", "Enkla villkor") är generella. Ändra så de stämmer med era faktiska villkor, t.ex. leveranstid och retur.
- Sidans titel och metabeskrivning ställer du in under **Onlinebutik → Inställningar → Titel och metabeskrivning** (förslag finns i `index.html`).
- Om ditt tema inte är Online Store 2.0 (saknar JSON-mallar) går det inte att lägga till sektionen via redigeraren – säg till så gör jag en variant.
- Ladda upp en egen delningsbild (1200×630) under *Inställningar → Social delningsbild* för bättre förhandsvisning på Instagram/Discord.
