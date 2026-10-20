# vSwap · Privacy e gestione account

Pagine HTML statiche in italiano, senza dipendenze, JavaScript o build.

- `privacy.html`: informativa sulla privacy dell’app vSwap.
- `index.html`: istruzioni per l’eliminazione dell’account, mantenute all’URL esistente.
- `.nojekyll`: pubblicazione dei file statici senza elaborazione Jekyll.

## Pubblicazione con GitHub Pages

1. Porta le modifiche sul branch da pubblicare nel repository `vSwapApp/vswap-legal`.
2. Apri **Settings → Pages → Build and deployment** su GitHub.
3. Seleziona **Deploy from a branch**, il branch contenente queste pagine e la cartella **/(root)**, quindi salva. Se Pages è già configurato così, basta aggiornare il branch selezionato.
4. Attendi che il deployment Pages termini con successo e verifica gli URL pubblici.

Con il dominio predefinito GitHub Pages, gli indirizzi attesi sono:

- **Informativa privacy, da indicare in Play Console:** https://vswapapp.github.io/vswap-legal/privacy.html
- **Eliminazione account:** https://vswapapp.github.io/vswap-legal/

Se configuri un dominio personalizzato, usa il dominio mostrato in Settings → Pages. Queste modifiche preparano i file locali: la pubblicazione dipende dalle impostazioni del repository e dal push.

## Dati dell’informativa e verifica prima della pubblicazione

Titolare: **Cristian Bonanno**. Contatto privacy: **vswapteam@gmail.com**.

Il testo riflette le funzionalità presenti nel repository locale dell’app `../vSwap`: Supabase, annunci e foto, match reciproci, comunicazione dell’email al proprietario compatibile, statistiche interne degli eventi di contatto, notifiche nell’app, cancellazione account e collegamento PayPal esterno.

Prima di pubblicare, verifica gli aspetti operativi che il codice non permette di accertare:

- Regione effettiva del progetto Supabase, subfornitori, accordo sul trattamento dei dati e garanzie per eventuali trasferimenti internazionali. Aggiorna la sezione 5 con le informazioni applicabili.
- Periodi effettivi di conservazione di log, backup e richieste di assistenza, in base a piano e impostazioni dei servizi. La sezione 6 usa criteri generali: rendili più specifici dopo la verifica, senza dichiarare una cancellazione immediata dei backup non accertata.
- Eventuali ulteriori recapiti del titolare da pubblicare.
- La pagina di eliminazione `index.html` preesistente contiene ancora indicazioni **da completare** sui tempi di gestione e sui dati conservati: completale in coerenza con le procedure effettive.
- Inserisci un collegamento alla stessa informativa anche nell’app e verifica che la sezione **Sicurezza dei dati** di Play Console corrisponda ai trattamenti effettivi.

Aggiorna la data dell’informativa quando modifichi i trattamenti descritti. Una modifica dell’app che introduce nuovi dati o fornitori richiede di rivedere anche questa pagina.

Riferimenti: [requisiti sui dati degli utenti di Google Play](https://support.google.com/googleplay/android-developer/answer/10144311), [GDPR](https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX:32016R0679), [documentazione GitHub Pages](https://docs.github.com/en/pages/quickstart).
