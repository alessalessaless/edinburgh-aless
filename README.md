# Edinburgh Aless · Mild or Spicy?

Guida personale mobile-first di Edimburgo, pubblicata con GitHub Pages.

## Interfaccia

- **Esplora e Ale’s Path** raggruppano le schede in Colazione, Giretti, Cibo, Birrette e Post cena.
- Le emoji 🌅 ☀️ 🌇 🌙 indicano il momento consigliato per la tappa (non corrispondono agli orari ufficiali).
- **Orari di apertura** mostrati direttamente nelle schede. I dati verificati sono collegati, nel dettaglio, alle pagine ufficiali oppure a terze parti esplicitamente indicate.
- Dove la sede non è specificata, gli orari sono discordanti o manca una fonte, la card indica che serve un controllo. Ultimo controllo manuale: **15 ottobre 2026**. Nessun indicatore “Aperto ora” viene calcolato automaticamente.
- Preferiti salvati sul dispositivo nel browser.

## Fotografie

Le fotografie sono caricate con le API pubbliche di Wikipedia / Wikimedia Commons, con crediti e link alla fonte nelle schede di dettaglio. Per i risultati Commons viene privilegiato il nome esatto del luogo; una foto generica di fallback è segnalata come **foto illustrativa**, per non farla passare per una fotografia del posto.

**Non sono state copiate immagini dalla ricerca Google Maps.** Google Place Photos richiede integrazione API, attribuzione e conformità alle norme di utilizzo; non è lecito scaricare e ripubblicare automaticamente la prima immagine della scheda Maps. Il dettaglio di ciascun luogo include un link per consultare immagini e orari direttamente su Google Maps.

## Pubblicazione

Il sito è statico e si trova in `index.html`. Non necessita di build.

GitHub → Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

Indirizzo atteso: https://alessalessaless.github.io/edinburgh-aless/

## Loyalty Cards

Sono incluse Lidl Plus e Tesco Clubcard come codici scansionabili, generati via librerie JavaScript esterne; richiedono Internet. **I numeri delle carte sono visibili pubblicamente** nel codice sorgente della repository.

## Verifiche finali

Controllare da telefono fotografie e codici scansionabili, e verificare in prossimità della visita gli orari, gli eventuali cambiamenti di sede e le chiusure eccezionali. Le fotografie e i dati dei luoghi dipendono anche da servizi esterni.
