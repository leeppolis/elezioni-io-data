# Elezioni.io

## Elezioni Politiche Italiane 4 Marzo 2018

[Elezioni.io](https://elezioni.io) è un sito il cui scopo è aggregare e analizzare la copertura data dalla stampa agli avvenimenti politici.

Le Elezioni Politiche Italiane tenutesi il 4 marzo 2018 sono state il primo test per la piattaforma.

Per avere un'idea più completa di come i dati siano stati raccolti, analizzati, e utilizzati, ti invitiamo a leggere queste pagine:

- [Come funziona](https://2018.elezioni.io/#/leggi/come-funziona)
- [Elezioni.io Is a News Aggregator and Analysis Tool(…)](https://medium.com/simone-lippolis/elezioni-io-is-a-news-aggregator-and-analysis-tool-about-the-italian-general-elections-held-on-e664001fec7a) (in inglese)

### Cosa contiene il repository

I file `.csv` che fanno parte di questo repository contengono tutti i dati *non* aggregati che sono stati usati come fonte per generare le analisi e le visualizzazioni pubblicate sul sito [2018.elezioni.io](https://2018.elezioni.io/). Contengono inoltre tutti gli articoli facenti parte dell'archivio del sito, e tutte le relazioni e i tag generati automaticamente dal nostro motore di AI.

- `elezioni2018_table_articles.csv` contiene gli articoli (testata, link, titolo, abstract, tags, data di aggiunta al DB (non necessariamente uguale alla data di prima pubblicazione), informazioni aggregate sulla popolarità)
- `elezioni2018_table_collections.csv` contiene le informazioni sugli schieramenti
- `elezioni2018_table_popularity.csv` contiene il log progressivo dell'evoluzione della popolarità degli articoli nella relativa finestra di monitoraggio
- `elezioni2018_table_topics_to_articles.csv` tabella di relazione tra `topics` e `articles`
- `elezioni2018_table_topics.csv` i "topics", o le parole chiave monitorate e associate a ciascuna "collection" per identificare gli schieramenti
- `elezioni2018_table_tweets.csv` i tweet ritenuti validi e che hanno poi portato all'importazione del relativo articolo
- `README.md` questo file

## Licenza

Questi dati possono essere liberamente utilizzati rispettando la licenza **CC BY-SA 4.0**. Il seguente è un riassunto (non un sostituto) della licenza completa, completa consultabile a questo indirizzo: [https://creativecommons.org/licenses/by-sa/4.0/legalcode](https://creativecommons.org/licenses/by-sa/4.0/legalcode). 

> ### Tu sei libero di:
> **Condividere** riprodurre, distribuire, comunicare al pubblico, esporre in pubblico, rappresentare, eseguire e recitare questo materiale con qualsiasi mezzo e formato
>
> **Modificare** remixare, trasformare il materiale e basarti su di esso per le tue opere
per qualsiasi fine, anche commerciale.
>
> Il licenziante non può revocare questi diritti fintanto che tu rispetti i termini della licenza.
> ### Alle seguenti condizioni:
> **Attribuzione** Devi riconoscere una menzione di paternità adeguata, fornire un link alla licenza e indicare se sono state effettuate delle modifiche. Puoi fare ciò in qualsiasi maniera ragionevole possibile, ma non con modalità tali da suggerire che il licenziante avalli te o il tuo utilizzo del materiale. 
>
> **Stessa Licenza** Se remixi, trasformi il materiale o ti basi su di esso, devi distribuire i tuoi contributi con la stessa licenza del materiale originario. 
>
> **Divieto di restrizioni aggiuntive** Non puoi applicare termini legali o misure tecnologiche che impongano ad altri soggetti dei vincoli giuridici su quanto la licenza consente loro di fare.
> ### Note:
> Non sei tenuto a rispettare i termini della licenza per quelle componenti del materiale che siano in pubblico dominio o nei casi in cui il tuo utilizzo sia consentito da una eccezione o limitazione prevista dalla legge.
>
> Non sono fornite garanzie. La licenza può non conferirti tutte le autorizzazioni necessarie per l'utilizzo che ti prefiggi. Ad esempio, diritti di terzi come i diritti all'immagine, alla riservatezza e i diritti morali potrebbero restringere gli usi che ti prefiggi sul materiale.

Tutti gli articoli, i loro titoli, i loro link, e i loro contenuti sono **copyright dei rispettivi proprietari**.