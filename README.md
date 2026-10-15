# Edinburgh · Mild or Spicy?

Guida personale mobile-first di Edimburgo, pubblicata con GitHub Pages.

## Homepage

Il titolo visibile del sito è **Edinburgh**; per non rompere i link la repository mantiene il nome `edinburgh-aless`.

Accanto a **Qualche idea**, il pulsante **Randomizza scelte** sostituisce le quattro card con nuovi suggerimenti casuali, senza ripetere immediatamente quelli già visibili.

Prima dei percorsi Mild/Spicy compare il consiglio sull'arrivo in aeroporto: l'**Airlink 100** collega l'aeroporto al centro e offre l'**Airport Open Return**, un ritorno a data aperta che costa meno di due biglietti singoli. Per le condizioni di validità consultare [Lothian Buses](https://www.lothianbuses.com/our-services/airport-buses/) al momento dell'acquisto. Il consiglio è personale: l'autore non ha provato il tram.

## Interfaccia

- **Esplora e Ale’s Path** raggruppano le schede in Colazione, Giretti, Cibo e Pub.
- Le emoji 🌅 ☀️ 🌇 🌙 indicano il momento consigliato per la tappa (non corrispondono agli orari ufficiali).
- **Orari di apertura** mostrati direttamente nelle schede. I dati verificati sono collegati, nel dettaglio, alle pagine ufficiali oppure a terze parti esplicitamente indicate.
- Dove la sede non è specificata, gli orari sono discordanti o manca una fonte, la card indica che serve un controllo. Ultimo controllo manuale: **15 ottobre 2026**. Nessun indicatore “Aperto ora” viene calcolato automaticamente.
- Preferiti salvati sul dispositivo nel browser.

## Fotografie nella guida

Le 46 schede hanno ora **46 immagini associate**: 27 fotografie selezionate da Wikimedia Commons e **19 immagini inviate direttamente per questa guida**, salvate in `assets/photos/*.webp` e ottimizzate per il caricamento su smartphone.

Le immagini ricevute comprendono Elephant House (30 Victoria Street), Armstrongs Cockburn Street, Black Medicine Coffee, Bertie's Fish & Chips, Braw Brunch, Makars Mash Bar, Pepe's Piri Piri, Castle Café, Pizza Posto, Pickleback, Tesco, M&S, Blackwell's, Sainsbury's, Lidl, Union Social Garden, The Bay Fish & Chips e un panorama delle Highlands. Dove l'immagine è un logo, viene presentata come logo, senza ritaglio.

La scheda del food truck è stata rinominata **Mr Wood Fire** (in precedenza "Truck Blu", secondo la conferma dell'autore della guida). La foto caricata `assets/photos/mr-woodfire-truck-unverified.webp` è ora visualizzata nella scheda. Il nome del file resta invariato per evitare upload duplicati.

Le fotografie già selezionate da Wikimedia Commons mantengono nella scheda il collegamento alla fonte e l'indicazione di autore/licenza. Le immagini inviate per la guida sono contrassegnate come tali, senza attribuire licenze che non conosciamo.

## Aggiornamenti del 15 ottobre 2026

- La voce precedente “The Elephant House” si riferisce ora a **The Elephant House Café, 30 Victoria Street** (apertura 10:00–18:00, ogni giorno, secondo [la fonte ufficiale](https://elephanthousecafe.com/contact-us/)).
- Nella sede di Victoria Street si trova il tavolo usato da J.K. Rowling. La scrittura di parte dei primi romanzi di Harry Potter avvenne nell'**originale locale di 21 George IV Bridge**: non attribuiamo questo fatto alla sede nuova.
- Non mostriamo per errore fotografie della vecchia sede nell'attuale scheda di Victoria Street; è stata ora inserita una foto fornita per la guida.
- Il filtro **Post cena** è stato rimosso e **Birrette** è confluito in **Pub**. Il castello è consigliato anche di sera per la vista dall'esterno, ed è incluso in Ale’s Path. Le aperture del castello non equivalgono all'accessibilità serale della spianata.

## Vestiario · Armstrongs & Son Vintage

Due negozi con indirizzi distinti, inclusi in **Esplora → Vestiario** e **Ale’s Path → Giretti**:

- **83 Grassmarket, EH1 2HJ**: sede storica. Foto autentica del negozio scattata da Kim Traynor, CC BY-SA 2.0, [scheda Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Armstrong%27s_Emporium_in_the_Grassmarket_-_geograph.org.uk_-_3128759.jpg).
- **29 Cockburn Street, EH1 1BN**: altra sede vicino alla Royal Mile, nella direzione della parte orientale della Old Town. La foto è ancora da selezionare; non vengono usate foto di altri negozi.

Orari (secondo il [sito ufficiale](https://www.armstrongsvintage.co.uk/)): lun–gio 10:00–17:30, ven–sab 10:00–18:00, dom 12:00–18:00. I link Google Maps individuano ogni sede attraverso l'indirizzo.

Nota sulla scelta della seconda sede: l'espressione "zona Holyrood" è stata interpretata come **Cockburn Street**, pur non essendo una sede ubicata a Holyrood. L'azienda possiede anche una sede a 66 Clerk Street e una a 14 Teviot Place; verificare con il curatore della guida se intendeva un'altra posizione.

## Pubblicazione

Il sito è statico e si trova in `index.html`. Non necessita di build.

GitHub → Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

Indirizzo atteso: https://alessalessaless.github.io/edinburgh-aless/

## Loyalty Cards

Sono incluse Lidl Plus e Tesco Clubcard come codici scansionabili, generati via librerie JavaScript esterne; richiedono Internet. **I numeri delle carte sono visibili pubblicamente** nel codice sorgente della repository.

## Verifiche finali

Controllare da telefono fotografie e codici scansionabili, e verificare in prossimità della visita gli orari, gli eventuali cambiamenti di sede e le chiusure eccezionali. Le fotografie e i dati dei luoghi dipendono anche da servizi esterni.
