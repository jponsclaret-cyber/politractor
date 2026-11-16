# politractor (instruccions per a Claude)

Repositori **públic** d'una eina per a un client: tot el que hi hagi, historial inclòs, és públic.

## Seguretat (mode estricte)

- Abans de fer commit o push, i en acabar qualsevol canvi, aplica la revisió de seguretat (la skill `revisio-seguretat`
  si la tens; si no, aquesta llista).
- **Cap dada real del client (models, pesos, preus, clients), cap secret ni fitxer de dades** al repositori ni a la
  conversa. Proves només amb dades inventades. El `.gitignore` exclou fitxers de dades: no el relaxis.
- L'eina és una sola pàgina que funciona 100 % sense connexió. La política de contingut (CSP) de la capçalera li prohibeix
  connectar-se enlloc: no hi afegeixis serveis externs ni scripts de tercers sense preguntar, i si ho canvies, actualitza-la.
- Tot el que s'insereix com a HTML s'escapa amb `esc()`.
- No canviïs la visibilitat del repositori ni publiquis res nou sense preguntar a en Jimix.
