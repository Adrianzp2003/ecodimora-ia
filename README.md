# Ecodimora — Confronto modelli IA (cliente)

Sito statico in italiano che confronta prezzi, capacità e limiti di modelli di linguaggio e di generazione/modifica immagini per Ecodimora. **Nessun dato privato del cliente** o connessione a servizi a pagamento. Pagina pronta per GitHub Pages, ma la pubblicazione va attivata separatamente.

## Come aprire

Aprire `index.html` nel browser. La pagina è autonoma: HTML, CSS e JavaScript inclusi, senza dipendenze esterne. I link alle fonti sono collegamenti informativi.

## Impostazione corretta del prodotto

Ecodimora non richiede un modello Blender come punto di partenza. I progetti possono nascere da **PDF con piante/prospetti/sezioni, immagini, fotografie, schizzi, una semplice idea, IFC, CAD o modelli 3D**. Per ogni sorgente, il sistema deve dichiarare dati disponibili e mancanti.

- Da un PDF quotato: estrarre e calibrare quote, confrontare le viste; ricostruire geometrie soltanto quando giustificate dalle fonti.
- Da foto, schizzi o idee: generare concept e immagini preliminari, esplicitamente **non metrici** finché non verificati.
- Da IFC/CAD/3D: usare la geometria esistente per tavole, quantità e, se utile, visualizzazioni con Blender.
- Chat, documenti, viste, misure, materiali e render sono collegati a **clienti, progetti e revisioni persistenti**, con isolamento corretto e indicatori di obsolescenza.
- L'IA supporta lettura/ideazione/editing, ma i calcoli quantitativi si basano su geometria verificabile e regole deterministiche.

## Prima pubblicazione con GitHub Pages

1. Creare un repository **pubblico** dedicato, per esempio `ecodimora-confronto-ia`.
2. Caricare `index.html`, `.nojekyll` e `README.md` nella radice della branch `main`.
3. In **Settings → Pages**, scegliere **Deploy from a branch**, `main` e `/(root)` e salvare.
4. Controllare che la pagina sia visibile tramite l’URL comunicato da GitHub e che i grafici/caricamenti funzionino.

**Attenzione:** un repository pubblico rende visibili anche cronologia, README e sorgente. Non includere PDF dei clienti né password/API key.

## Stato

Comparativa informativa del 23/10/2026. I prezzi dipendono da modelli, versioni, regioni e consumi; i risultati di fedeltà architettonica non sono stati testati sul PDF reale.