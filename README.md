# Edinburgh

Guida personale mobile-first di Edimburgo, pubblicata con GitHub Pages.

## Homepage

Il titolo visibile del sito è **Edinburgh**, con sottotitolo «guida assolutamente non richiesta ma avevo un'ora libera e chtgpt plus»; per non rompere i link la repository mantiene il nome `edinburgh-aless`.

Accanto a **Qualche idea**, il pulsante **Randomizza scelte** sostituisce le quattro card con nuovi suggerimenti casuali, senza ripetere immediatamente quelli già visibili.

Prima dei percorsi Mild/Spicy compare il consiglio sull'arrivo in aeroporto: l'**Airlink 100** collega l'aeroporto al centro e offre l'**Airport Open Return**, un ritorno a data aperta che costa meno di due biglietti singoli. Il sito mostra un link alle [comunicazioni ufficiali](https://www.lothianbuses.com/our-services/airport-buses/). Il consiglio è personale: l'autore non ha provato il tram.

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

Le carte **Lidl Plus** e **Tesco Clubcard** ora mostrano solo il numero e un pulsante **Copia codice** (con tentativo di copia negli appunti e soluzione alternativa per browser meno recenti). Non vengono più generati QR code o codici a barre. Sotto ogni numero c'è un collegamento **Aggiungi su Klarna**, con logo Klarna, che apre [la pagina ufficiale dell'app](https://www.klarna.com/it/klarna-app/). **Non esiste integrazione tra il sito e Klarna**: è necessario copiare il numero e incollarlo manualmente nell'app. I numeri delle carte restano pubblicamente visibili nel codice HTML della repository.

## The Original Mosque Kitchen & Café: ingresso corretto

**Indirizzo:** 50 Potterrow, Edinburgh EH8 9BT (cortile della Edinburgh Central Mosque). Non confonderlo con **The Mosque Kitchen**, 31–33 Nicolson Square: sono due ristoranti distinti.

**Indicazioni alle destinatarie:** passate tra la moschea e il locale sulla strada, mantenendo la moschea alla vostra sinistra; scendete le scale e girate a destra. La cucina che consigliamo è sul retro, nel cortile. Le indicazioni derivano dall'esperienza personale del curatore, corroborate da [descrizioni dell'ingresso su Tripadvisor](https://www.tripadvisor.co.uk/LocationPhotoDirectLink-g186525-d8551725-i157409285-The_Original_Mosque_Kitchen_Cafe-Edinburgh_Scotland.html).

**Orari:** indicativamente 11:30–22:00 per Potterrow. La chiusura alle 22:00 è riportata dal ricordo diretto dell'autore; le fonti online non sono concordi e la scheda chiarisce che non si tratta degli orari del ristorante di Nicolson Square. Per informazioni esterne, [pagina del locale corretto](https://www.tripadvisor.co.uk/Restaurant_Review-g186525-d8551725-Reviews-The_Original_Mosque_Kitchen_Cafe-Edinburgh_Scotland.html).

**Foto:** [Kim Traynor, Edinburgh Mosque kitchen, 2009](https://commons.wikimedia.org/wiki/File:Edinburgh_Mosque_kitchen_-_geograph.org.uk_-_1315877.jpg), CC BY-SA 2.0: la didascalia Commons identifica esplicitamente la cucina dietro la moschea.

## Ottimizzazione mobile

- Il pulsante **Randomizza scelte** utilizza un'estrazione parziale di quattro luoghi e raggruppa i tocchi molto ravvicinati in un solo aggiornamento per fotogramma; `touch-action: manipulation` previene lo zoom da doppio tocco sui pulsanti senza disabilitare il pinch-to-zoom.
- I **preferiti** vengono aggiornati direttamente sulle stelle, senza ridisegnare la pagina e senza ricaricare le fotografie; anche chiudere il dettaglio non ricrea più le card. Nella vista Preferiti, la card rimossa e le statistiche vengono aggiornate localmente.
- **Fotografie:** un unico `IntersectionObserver` per tutte le card, ripulito quando cambia il contenuto; immagini Wikimedia Commons a 480 px per le miniature (960 px solo nei dettagli), foto WebP fornite per la guida invariate. Le risorse non vengono generate o ricercate automaticamente.
- Eliminati blocchi JavaScript di ricerca immagini non più utilizzati (circa 5 KB). Sono rimaste **46 schede** e non sono cambiati testi o percorsi, fatta eccezione per le due modifiche richieste a sottotitolo e orari Mosque Kitchen.

## Verifiche finali

Controllare da telefono fotografie e pulsanti di copia delle tessere, e verificare in prossimità della visita gli orari, gli eventuali cambiamenti di sede e le chiusure eccezionali. Le fotografie e i dati dei luoghi dipendono anche da servizi esterni.
