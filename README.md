# Chestionare de cuplu

Formular web self-contained — un singur `index.html`, fără server, fără dependențe — pentru trei chestionare folosite în terapia de cuplu:

1. **AAS** (Adult Attachment Scale) — stil de atașament: securizant / evitant / anxios-ambivalent
2. **Cele 5 limbaje ale iubirii** — limbaj principal + secundar
3. **A.D.I.** — Accesibilitate · Disponibilitate · Implicare emoțională (percepția asupra partenerului)

## Ghid rapid

Vrei doar să completezi chestionarele? Trei pași:

1. **Descarcă** [`index.html`](https://raw.githubusercontent.com/florin-cerbu-tech/chestionare-cuplu/main/index.html) — click dreapta pe link → *Save Link As…* (sau butonul verde **Code → Download ZIP** de pe pagina repo-ului).
2. **Deschide fișierul cu Chrome** (sau orice browser) — dublu-click. Nu trebuie instalat nimic, nu trebuie cont, nu trebuie internet.
3. **Bonus — nu mă crede pe cuvânt 🙂**: dă fișierul lui ChatGPT / Claude / oricărui AI cu întrebarea *„Citește codul ăsta și spune-mi dacă vreun răspuns al meu pleacă de pe calculatorul meu."* E un singur fișier, ușor de citit — verdictul: totul rămâne în browserul tău.

Alternativ, fără descărcare: varianta hostată pe GitHub Pages — **<https://florin-cerbu-tech.github.io/chestionare-cuplu/>** (același fișier, servit direct din acest repo; și acolo răspunsurile rămân în browser).

## Utilizare

Deschide `index.html` în browser (dublu-click) sau varianta hostată. 43 de întrebări, una pe ecran, cu navigare din click sau tastatură (1–6 / A–E, săgeți). Progresul se salvează în `localStorage` — poți închide tab-ul și relua. Fiecare partener completează separat („Reia de la zero" la final).

La final, raportul calculează automat toate scorurile și oferă:

- **Printează / Salvează PDF** — raport curat, cu anexa răspunsurilor complete
- **Descarcă rezultatele (HTML)** — snapshot standalone al raportului
- **Descarcă / Copiază raport MD** — raport Markdown cu fiecare întrebare + răspuns, scoruri și interpretare, gândit ca input pentru un agent AI care analizează răspunsurile

## Confidențialitate

Totul rulează local în browserul tău. Răspunsurile nu se trimit pe niciun server.

## Note

Instrumentele aparțin autorilor lor; adaptările în limba română provin din materiale primite în cadrul terapiei. Folosire personală / educațională.
