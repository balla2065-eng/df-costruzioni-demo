# DF Costruzioni Edili SRLS — sito demo

Sito dimostrativo one-page (italiano) per **DF Costruzioni Edili SRLS**, Cassano d'Adda (Lombardia),
con focus sull'area di Milano. Obiettivo: generare richieste di preventivo via WhatsApp.

Demo indipendente. **Non fa parte del codice di produzione di Calcoryn.**

## Contenuto

- `index.html` — pagina unica, autonoma (nessuna build, nessuna dipendenza oltre a Google Fonts)
- `.nojekyll` — serve i file così come sono su GitHub Pages

## Struttura della pagina

1. Header sticky con CTA WhatsApp
2. Hero + strip informativa (base operativa, zona, formula, contatto)
3. Servizi (6 schede, una per servizio verificato)
4. Ambienti — sezione visiva con illustrazioni SVG
5. Come lavoriamo — 4 passaggi
6. Zone servite + domande frequenti
7. CTA finale con numero in chiaro
8. Footer
9. Barra WhatsApp fissa su mobile, pulsante flottante su desktop

## Dati usati

Solo i dati forniti e verificati:

- Ragione sociale: DF Costruzioni Edili SRLS
- WhatsApp / telefono: +39 346 189 5589 (`wa.me/393461895589`)
- Zona: Cassano d'Adda, Lombardia, area di Milano
- Servizi: ristrutturazioni chiavi in mano, cartongesso, resina, tinteggiatura,
  controsoffittature, posa pavimenti

**Non** sono presenti recensioni, progetti, certificazioni, prezzi, anni di attività,
numeri di cantieri o altre affermazioni non verificate.

Le immagini della sezione "Ambienti" e dell'hero sono **illustrazioni SVG originali**,
etichettate singolarmente come illustrazioni e accompagnate da un disclaimer esplicito:
non rappresentano lavori realizzati dall'azienda.

## Da completare prima della messa online

- [ ] P.IVA e sede legale nel footer (attualmente "da inserire")
- [ ] Rimuovere `<meta name="robots" content="noindex, nofollow">` dal `<head>`
- [ ] Rimuovere la dicitura "Sito dimostrativo…" dal footer
- [ ] Eventuale pagina privacy/cookie se verranno aggiunti strumenti di analytics
- [ ] Sostituire le illustrazioni con foto reali di lavori, se disponibili e autorizzate

## Anteprima locale

```
cd demos/df-costruzioni
python3 -m http.server 8080
# http://localhost:8080
```

## Pubblicazione

Pubblicato con GitHub Pages da `main` / `/ (root)`.

Live: <https://balla2065-eng.github.io/df-costruzioni-demo/>

Ogni push su `main` rigenera il sito (circa un minuto).
