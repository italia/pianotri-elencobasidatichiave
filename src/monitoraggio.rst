Stato di apertura e pubblicazione delle basi di dati chiave
===========================================================

Lo scopo di questa sezione è dettagliare lo stato di apertura, al 31/12/2017 e secondo il paradigma degli open data, delle basi dati chiave come riportate in `Elenco basi di dati chiave <elencobasidati.html>`__”, specie in relazione agli `Obiettivi <obiettivi.html>`__ identificati per il 2017. Il lavoro, coordinato dal Team Digitale e dall’Agenzia per l’Italia Digitale (AgID), ha coinvolto alcune amministrazioni centrali e locali, quest’ultime afferenti alla Task Force #DatiPubblici.

Per ciascuna base di dati sono fornite le seguenti informazioni:

1. Stato di caricamento all’interno del DAF (Obiettivo 1);
2. Stato di apertura, anche via DAF, secondo il paradigma dei dati aperti (Obiettivo 2);
3. Disponibilità di API associate alle basi di dati che consentano una loro diretta interrogazione (Obiettivo 3);
4. Disponibilità di modelli/ontologie e di vocabolari controllati, nonché di metadati conformi al profilo DCAT-AP_IT (Obiettivo 4);
5. Informazioni di monitoraggio, anche rispetto a eventuali ritardi riscontrati per la loro apertura (e.g., data entro la quale il dataset sarà disponibile come open data sul DAF, e motivazioni del ritardo della pubblicazione) (parte dell'Obiettivo 5)

I primi 3 obiettivi (i.e., caricamento nel DAF, apertura dei dati via DAF e disponibilità di API) sono strettamente collegati allo stato di implementazione dell’infrastruttura tecnologica del DAF e alla relativa sperimentazione. Il processo di identificazione della pubblica amministrazione che prenderà in carico l'intera piattaforma DAF non è ancora concluso; conseguentemente diverse attività di rilascio ad essa inerenti sono state posticipate. Si ricorda che l’articolo 50-ter del nuovo Codice dell'Amministrazione Digitale (CAD) prevede che, fino a quando non sarà identificata la futura pubblica amministrazione titolare del DAF, lo sviluppo e la gestione della piattaforma siano affidati alla struttura commissariale presso la Presidenza del Consiglio dei Ministri. Durante questa fase, la struttura commissariale lavorerà al meglio delle proprie possibilità, utilizzando le risorse disponibili, al fine di consegnare alla futura Amministrazione titolare il miglior prodotto possibile. Sulla base di questo nuovo scenario, sarà inoltre aggiornato, quanto prima, `il piano di sviluppo del DAF <http://daf-piano-di-sviluppo.readthedocs.io/it/latest/roadmap.html>`__.

In ogni caso, i dataset già caricati nel DAF, e quelli che lo saranno nelle prossime settimane, risulteranno automaticamente aderenti al profilo di metadatazione DCAT-AP_IT (parte dell’Obiettivo 4) e disporranno di API per l’interrogazione (Obiettivo 3).

Vale la pena sottolineare che il lavoro in corso con le pubbliche amministrazioni coinvolte nella sperimentazione del DAF mira anche a una razionalizzazione di quanto a volte oggi viene pubblicato, grazie ad esempio all’eliminazione delle pubblicazioni mensili per descrivere fenomeni continui nel tempo (e.g., come nel caso gli incidenti stradali) sostituite con pubblicazioni continue degli stessi dataset. Si stanno inoltre definendo dataset standard sulla base delle ontologie sviluppate al fine di consentire la confrontabilità dei dati provenienti da diverse realtà territoriali. Nel caso di caricamento di dataset con struttura proprietaria, il DAF sarà in grado di effettuare una conversione nello standard previsto.

Infine, è in corso un’attività di revisione dell’attuale catalogo nazionale dei dati aperti per consentire un più robusto harvesting continuo sulla base anche del profilo di metadatazione DCAT-AP_IT. Tale catalogo è parte integrante del DAF che attinge dallo stesso, da un lato per caricare dati aperti delle pubbliche amministrazioni e dall’altro per catalogare i dati aperti prodotti dal DAF.


Si fornisce di seguito il dettaglio per ambiti e dataset; nel caso di dataset in cui è coinvolta la Task Force #DatiPubblici, si dettaglia lo stato per ciascuna amministrazione.

Quando i dataset risultano essere più di competenza comunale che regionale, è stato fornito il dettaglio solo per le amministrazioni comunali. Alcune regioni/province autonome hanno però competenze che si riconducono, in certi casi, a competenze di un livello comunale. Per tale motivo in alcuni casi sono state indicate nelle tabelle seguenti.

Trasporti
---------

Traffico e viabilità in tempo reale
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
"*Il dataset contiene i dati relativi allo stato, agli eventi e alle telecamere di monitoraggio del traffico e della viabilità in tempo reale. Dalla Task Force #DatiPubblici sono state escluse le regioni, in quanto il dato non è generalmente di loro specifica competenza.*"

Le sezioni seguenti riportano, per ciascun amministrazione coinvolta nella Task Force #DatiPubblici, il dettaglio rispetto ai dataset.

Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Riassunto rilievo di traffico automatizzato <https://dati.trentino.it/dataset/riassunto-rilievo-traffico-automatico-stazioni-fisse-anno-2015>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting nel nuovo catalogo nazionale
**Monitoraggio (Obiettivo 5)**               Dati non completi, comunque fermi al 2015
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Bollettini del traffico fuori provincia <http://dati.retecivica.bz.it/it/dataset/webservices-southtyrolean-trafficreport-outofprovince>`__
                                             | `Passi e vie di montagna <http://dati.retecivica.bz.it/it/dataset/webservices-southtyrolean-trafficreport-mountainroadsandpasses>`__
                                             | `Controlli radar <http://dati.retecivica.bz.it/it/dataset/webservices-southtyrolean-trafficreport-radarspeedchecks>`__
                                             | `Trasporti pubblici <http://dati.retecivica.bz.it/it/dataset/webservices-southtyrolean-trafficreport-publictransport>`__
                                             | `Traffico situazione attuale <http://dati.retecivica.bz.it/it/dataset/webservices-southtyrolean-trafficreport-currentsituation>`__
                                             | `Cantieri e chiusure <http://dati.retecivica.bz.it/it/dataset/webservices-southtyrolean-trafficreport-works-closings>`__
                                             | `Stazioni contatraffico <http://dati.retecivica.bz.it/it/dataset/rete-viaria-stazioni-contatraffico>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di implementazione ingestion in modalità pull
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Roma Capitale
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Stato del traffico <https://romamobilita.it/it/azienda/open-data/api-real-time>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso verifica integrabilità dell’API fornita
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Comune di Milano
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati disponibili da parte di ATM SpA
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso verifica disponibilità delle API
**Monitoraggio (Obiettivo 5)**               | In corso contatti con la partecipata nell’ambito di progetti europei
                                             | (Sharing Cities, Synchronicity)
============================================ =================================================================================================================================================

Comune di Torino
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Flusso di traffico <http://www.5t.torino.it/open-data/>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Sperimentazione in corso per ingestion realtime
**Monitoraggio (Obiettivo 5)**               | Il ritardo è dovuto all’attuale completamento nel DAF
                                             | dell’implementazione del flusso Internet of Thing (IoT)
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**               | L’amministrazione ha comunicato che i dati saranno disponibili
                                             | entro l’anno 2018.
                                             | Fino a 6/17 è stata fatta una `rilevazione sperimentale <http://opendata.comune.fi.it/mobilita_sicurezza/dataset_0371.html>`__
                                             | e test di ingestion su DAF
============================================ ===========================================================================================================================================================

Comune di Bari
""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**               | L’amministrazione non si è ancora dotata completamente di tutti
                                             | gli strumenti che consentono una rilevazione real-time.
                                             | Esistono tuttavia alcuni fondi PON-METRO destinati alla creazione
                                             | dell’infrastruttura necessaria.
============================================ ===========================================================================================================================================================

Si noti che nell’ambito della sperimentazione del DAF è stata attivata una collaborazione con il Ministero delle Infrastrutture e dei Trasporti per l’acquisizione degli eventi emessi dal CCISS.
Si sta valutando pertanto la possibilità di pubblicare uno stream real time di tali dati.

**Obiettivo 4**: Nell’ambito della rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__ di ontologie e vocabolari controllati per la pubblica amministrazione è stata creata l’ontologia EventiIoT (pubblicata in conferenza internazionale con esempi in Linked Open Data estratti dai dati sul traffico del comune di Firenze nell’ambito della rilevazione sperimentale fatta nel DAF con il comune stesso, come indicato sotto) costruita a partire dai dati realtime del Comune di Torino e del Comune di Firenze. L’ontologia è allineata a diverse ontologie del Web Semantico tra cui, in particolare, la Semantic Sensor Network.
I dataset aperti della Provincia Autonoma di Trento e di Bolzano e del Comune di Torino via DAF presentano metadati allineati a DCAT-AP_IT. Nel caso del Comune di Roma Capitale, si segnala che sono in corso i test per la conformità al profilo DCAT-AP_IT e per l'harvesting nel catalogo nazionale.

Parcheggi
^^^^^^^^^
"*Il dataset contiene i dati sulla posizione e lo stato dei parcheggi. Dalla Task Force #DatiPubblici sono state escluse le regioni, in quanto il dato non è generalmente di loro specifica competenza.*"

Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Parcheggi disabili del Comune di Trento <https://dati.trentino.it/dataset/parcheggi-disabili-open-data>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo il caricamento nel DAF
**Monitoraggio (Obiettivo 5)**               Il formato SHP non è ancora supportato dal DAF
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  `PUC del comune di Bolzano: viabilità (tra cui parcheggi) <http://dati.retecivica.bz.it/it/dataset/piani-urbanistici-comune-di-bolzano-viabilita>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di implementazione ingestion in modalità pull
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Comune di Roma Capitale
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Sosta tariffata <http://dati.comune.roma.it/cms/it/dettaglio_turismo_e_mob.page?contentId=DTS7901>`__
                                             | `Parcheggi di scambio <http://dati.comune.roma.it/cms/it/dettaglio_turismo_e_mob.page?contentId=DTS7893>`__
                                             | `Parcheggi car sharing <https://romamobilita.it/it/tecnologie/open-data/dataset>`__
                                             | `Colonnine di ricarica <https://romamobilita.it/it/tecnologie/open-data/dataset>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di implementazione ingestion in modalità pull
**Monitoraggio (Obiettivo 5)**               | Per il dataset “sosta tariffata”, il formato SHP non è
                                             | ancora supportato nel DAF
============================================ =================================================================================================================================================


Comune di Milano
""""""""""""""""
============================================ =======================================================================================================================================================================
Obiettivo                                    Stato
============================================ =======================================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Localizzazione Parcheggi di scambio e pubblici <http://dati.comune.milano.it/dataset/ds45_infogeo_parcheggi_interscambio_localizzazione_>`__
                                             | `Area di sosta per car sharing <http://dati.comune.milano.it/dataset/ds381-trafficotrasporti-aree-sosta-car-sharing/resource/2725440b-12e8-4b68-9764-b5f47590d871>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non è ancora attivo il caricamento nel DAF
**Monitoraggio (Obiettivo 5)**               | Il formato SHP non è ancora supportato dal DAF;
                                             | i dataset saranno disponibili in formato geojson
============================================ =======================================================================================================================================================================

Comune di Torino
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Disponibilità parcheggi <http://www.5t.torino.it/open-data/>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  L’ingestion di dati realtime è in corso di realizzazione
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Informazioni e stato dei parcheggi <http://opendata.comune.fi.it/mobilita_sicurezza/dataset_0372.html>`__
                                             | Colonnine di ricarica
**Caricamento DAF e API (Obiettivi 1 e 3)**  Attivi con aggiornamento al minuto/15 min
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Bari
""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

**Obiettivo 4**: Nell’ambito della rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__ di ontologie e vocabolari controllati per la pubblica amministrazione è stata creata l’ontologia dei Parcheggi. Oltre a una prima tassonomia presente nell’ontologia, in stretto contatto con ISTAT, si sta valutando la creazione di un ulteriore vocabolario controllato sui tipi di parcheggi che si differenziano in base alla loro struttura.
I dataset aperti delle Province Autonome di Trento e Bolzano, del comune di Milano e di Firenze via DAF hanno metadati conformi al profilo DCAT-AP_IT. Nel caso del Comune di Roma Capitale, si segnala che sono in corso i test per la conformità al profilo DCAT-AP_IT e per l'harvesting nel catalogo nazionale.

Perimetro, varchi e orari ZTL
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
"*Il dataset contiene la descrizione geometrica del perimetro della ZTL gli orari e i varchi di accesso. Dalla Task Force #DatiPubblici sono state escluse le regioni, in quanto il dato non è generalmente di loro specifica competenza.*"


Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Confini ZTL <https://dati.trentino.it/dataset/zona-a-traffico-limitato-open-data>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo il caricamento nel DAF
**Monitoraggio (Obiettivo 5)**               Il formato SHP non è ancora supportato dal DAF
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Comune di Roma Capitale
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Varchi e confini ZTL <https://romamobilita.it/it/tecnologie/open-data/dataset>`__
                                             | `Orari ZTL <https://romamobilita.it/it/azienda/open-data/api-real-time>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In corso di implementazione ingestion in modalità pull.
                                             | Per “Orari ZTL”, in corso verifica integrabilità dell’API fornita
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Comune di Milano
""""""""""""""""
============================================ =======================================================================================================================================================================
Obiettivo                                    Stato
============================================ =======================================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Aree pedonali ZTL e Zona 30 <http://dati.comune.milano.it/dataset/ds51_trafficotrasporti_aree_pedonali_ztl_zone_30_>`__
                                             | `Varchi elettronici <http://dati.comune.milano.it/dataset/ds82_infogeo_varchi_elettronici_localizzazione_>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non è ancora attivo il caricamento nel DAF
**Monitoraggio (Obiettivo 5)**               | Il formato SHP non è ancora supportato dal DAF;
                                             | i dataset saranno disponibili in formato geojson
============================================ =======================================================================================================================================================================

Comune di Torino
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Perimetro e orari ZTL <http://www.5t.torino.it/open-data/>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In corso di implementazione ingestion in modalità pull
                                             | con conversione da XML a JSON
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Pannelli informativi ZTL <http://opendata.comune.fi.it/mobilita_sicurezza/dataset_0396.html>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non è ancora attivo il caricamento nel DAF
**Monitoraggio (Obiettivo 5)**               Il formato SHP non è ancora supportato dal DAF
============================================ ===========================================================================================================================================================

Comune di Bari
""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

**Obiettivo 4**: Nell’ambito della rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__ di ontologie e vocabolari controllati per la pubblica amministrazione è stata creata l’ontologia dei Luoghi/Indirizzi che può essere utilizzata per modellare *una parte di questi dati (ovvero i dati trasversali presenti nel dataset)*.
Non è ancora stata predisposta un’ontologia per i dati specifici di dominio.

I dataset aperti della Provincia Autonoma di Trento e del comune di Milano hanno metadati conformi al profilo DCAT-AP_IT. Nel caso del Comune di Roma Capitale, si segnala che sono in corso i test per la conformità al profilo DCAT-AP_IT e per l'harvesting nel catalogo nazionale.


TPL dati statici e in tempo reale
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
"*I dataset contengono i dati statici del trasporto pubblico locale quali fermate, tratti e orari degli autobus, e i dati in tempo reale del trasporto pubblico locale.*"

Quasi sempre i dataset sono pubblicati in formato GTFS (General Transit Feed Specification). Per tale motivo si sta lavorando nel DAF per definire un dataset standard il cui modello è basato sulla specifica GTFS.

Regione Piemonte
""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**                  | Servizio programmato del Trasporto Pubblico Regione Piemonte:
                                             | `Autobus <http://www.dati.piemonte.it/catalogodati/dato/100939-.html>`__ e `Treni Regionali <http://www.dati.piemonte.it/catalogodati/dato/100939-.html>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di definizione il flusso GTFS
**Monitoraggio (Obiettivo 5)**
============================================ =============================================================================================================================================================


Regione Lombardia
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Orario ferroviario regionale TreNord <https://www.dati.lombardia.it/Mobilit-e-trasporti/Orario-Ferroviario-Regionale-Gtfs/3z4k-mxz9>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di definizione il flusso GTFS
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Emilia-Romagna
""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Toscana
"""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Trasporto pubblico <http://dati.toscana.it/dataset/rt-oraritb>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di definizione il flusso GTFS
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Lazio
"""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'Amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================



Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Dati statici TPL urbano ed extraurbano, tariffe TPL <https://dati.trentino.it/dataset/trasporti-pubblici-del-trentino-formato-gtfsa>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di definizione il flusso GTFS
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Servizi web degli autobus urbani SASA <http://dati.retecivica.bz.it/it/dataset/webservices-sasa>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di verifica l'integrabilità dell'API fornita
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Comune di Roma Capitale
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Rete TPL metropolitane, ferrovie <https://romamobilita.it/it/tecnologie/open-data/dataset>`__
                                             | `Previsioni di arrivo, Percorsi <https://romamobilita.it/it/azienda/open-data/api-real-time>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In corso di definizione il flusso GTFS e verifica
                                             | dell'integrabilità dell'API fornita
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Comune di Milano
""""""""""""""""
============================================ ====================================================================================================================================================================================================================================================================================
Obiettivo                                    Stato
============================================ ====================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Programmato TPL <https://www.amat-mi.it/it/mobilita/dati-strumenti-tecnologie/dati-gtfs/>`__
                                             | `Rete <http://dati.comune.milano.it/dataset/ds81_infogeo_rete_ferroviaria_localizzazione_>`__ e `stazioni <http://dati.comune.milano.it/dataset/ds80_infogeo_stazioni_ferroviarie_localizzazione_>`__ ferroviarie
                                             | `Percorsi <http://dati.comune.milano.it/dataset/ds182-trafficotrasporti-linee-urbane-superficie-percorsi-localizzazione>`__ e `fermate <http://dati.comune.milano.it/dataset/ds66_infogeo_fermate_metropolitana_localizzazione_>`__ metropolitane
                                             | `Percorsi <http://dati.comune.milano.it/dataset/ds182-trafficotrasporti-linee-urbane-superficie-percorsi-localizzazione>`__ e `fermate <http://dati.comune.milano.it/dataset/ds181-trafficotrasporti-linee-urbane-superficie-fermate-localizzazione>`__ linee urbane di superficie
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di definizione il flusso GTFS
**Monitoraggio (Obiettivo 5)**               | Il formato SHP non è ancora supportato dal DAF;
                                             | A breve i dati saranno disponibili in formato geojson
                                             | ed aggiornati da AMAT
============================================ ====================================================================================================================================================================================================================================================================================

Comune di Torino
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Orari trasporti GTT <http://opendata.5t.torino.it/gtfs/piemonte_it.zip>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di definizione il flusso GTFS
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | Fermate
**Caricamento DAF e API (Obiettivi 1 e 3)**  Attivo con aggiornamento giornaliero
**Monitoraggio (Obiettivo 5)**               | Sebbene attivo l'ingestion, non è ancora possibile pubblicare i dati
                                             | in open data perché i dati sono dati forniti giornalmente dal
                                             | supervisore del traffico della città Metropolitana. Si stanno
                                             | prendendo contatti per stimolare l'apertura dei dati
============================================ ===========================================================================================================================================================

Comune di Bari
""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**               Non disponibile, il progetto SEMINA sembra essere chiuso
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Dati statici TPL <https://opendata.comune.palermo.it/opendata-archivio-dataset.php>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di definizione il flusso GTFS
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================



Patenti attive
^^^^^^^^^^^^^^

Ministero delle Infrastrutture e dei Trasporti
""""""""""""""""""""""""""""""""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | Il `dataset <http://dati.mit.gov.it/catalog/dataset/patenti>`__ contiene i dati sulle patenti attive
                                             | in Italia ed è attualmente pubblicato come dato aperto sul portale
                                             | del Ministero delle Infrastrutture e dei Trasporti
**Disponibilità API (Obiettivo 3)**          | Il portale del Ministero delle Infrastrutture e dei Trasporti (MIT)
                                             | consente anche l’interazione con il dataset via API
**Caricamento nel DAF (Obiettivo 1)**        | Al momento sono attive collaborazioni tra il Team Digitale e il MIT
                                             | per la sperimentazione del DAF come piattaforma di data analytics.
                                             | Una versione più ampia del dataset, contenente anche informazioni
                                             | personali, è **stata caricata** nel DAF.
                                             | Al termine della sperimentazione l’amministrazione potrà decidere
                                             | se pubblicare l'intero dataset mediante il DAF
**Modellazione dati (Obiettivo 4)**          | Non è al momento presente, nella rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__, un’ontologia
                                             | di dominio che catturi il concetto di Patente.
                                             | Tuttavia da una prima analisi dei dati, le ontologie sul tempo e sulle
                                             | persone possono essere utilizzate per modellare una parte dei dati.
============================================ ===========================================================================================================================================================

**Obiettivo 4**: Nell’ambito della rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__ di ontologie e vocabolari controllati per la pubblica amministrazione, è in corso di definizione l’ontologia basata sul modello GTFS (per la parte relativa ai dati statici). Sulla base della specifica, alcuni dati sono già modellabili attraverso altre ontologie della rete, nello specifico, l’ontologia delle organizzazioni. l’ontologia del tempo, l’ontologia dei punti di interesse, l’ontologia dei prezzi/biglietti/offerte.
Si stima che l’ontologia relativa di dominio sarà disponibile nel repository github nei prossimi mesi (entro la primavera). Questa sarà collegata alle suddette ontologie che possono già essere riutilizzate per modellare alcune informazioni della specifica. Per quanto concerne la parte di dati in tempo reale, l’ontologia Eventi IoT potrebbe essere utilizzata.


Incidenti Stradali
^^^^^^^^^^^^^^^^^^
"*Il dataset contiene i dati sugli incidenti stradali rilevati dalle polizie municipali dei territori comunali. Per questo motivo dalla Task Force #DatiPubblici sono state escluse le regioni.*"

Dettaglio per singole amministrazioni coinvolte nella Task Force #DatiPubblici:

Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Incidenti Comune di Trento <http://dati.trentino.it/dataset/incidenti-open-data>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivato
**Monitoraggio (Obiettivo 5)**               Formato SHP ancora non supportato nel DAF
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**               Non disponibile
============================================ ======================================================================================================================================================

Comune di Roma Capitale
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Incidenti stradali <http://dati.comune.roma.it/cms/it/incidenti_stradali.page>`__
                                             | `Ciclisti coinvolti negli incidenti <http://dati.comune.roma.it/cms/it/incidenti_stradali.page>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Parziale (già caricato sottoinsieme nell’ambito della sperimentazione, collaborazione in corso con l’amministrazione per unire le serie storiche)
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Comune di Milano
""""""""""""""""
============================================ ====================================================================================================================================================================================================================================================================================
Obiettivo                                    Stato
============================================ ====================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                  Non disponibile
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ====================================================================================================================================================================================================================================================================================

Comune di Torino
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Non disponibile
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Sinistri con velocipedi  <http://opendata.comune.fi.it/mobilita_sicurezza/dataset_0385.html>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               Formato SHP ancora non supportato nel DAF. dataset relativo al periodo aprile 2011 - marzo 2015
============================================ ===========================================================================================================================================================

Comune di Bari
""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  Non disponibile
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Sinistri stradali <https://opendata.comune.palermo.it/opendata-archivio-dataset.php?tag=INCIDENTI>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

**Obiettivo 4**: Non è al momento presente, nella rete OntoPiA, un’ontologia di dominio per gli incidenti stradali. Da una prima analisi dei dati pubblicati dal Comune di Roma e dal Comune di Palermo, l’ontologia delle persone, dei luoghi/indirizzi, dei punti di interesse possono essere utilizzate per modellare una parte di questi dati. Si noti che si è in contatto con ISTAT per acquisire il modello da loro utilizzato che raccogliere i dati dai vari comuni italiani.


Istruzione, cultura e sport
---------------------------

Istituti e luoghi della cultura
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
"*Dataset contenente i dati relativi agli istituti e luoghi della cultura (biblioteche, musei, parchi archeologici, ecc.) I dati descrivono le sedi, gli enti competenti sui luoghi, i servizi offerti e le informazioni di accesso ai luoghi.*"

Ministero dei Beni e delle Attività Culturali e del Turismo
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Luoghi della cultura <http://dati.beniculturali.it/datasets/>`__
                                             | `Biblioteche italiane <http://dati.beniculturali.it/datasets/>`__
                                             | `Contenitori fisici e giuridici <http://dati.beniculturali.it/datasets/>`__
                                             | `Archivi di Stato <http://dati.beniculturali.it/datasets/>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di realizzazione
**Monitoraggio (Obiettivo 5)**
============================================ =============================================================================================================================================================


Regione Piemonte
""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**                  | Musei della Regione Piemonte
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               | Il dataset indicato porta a una "pagina non trovata"
                                             | nel catalogo dei dati aperti.
                                             | La Regione, mediante il CSI Piemonte sta attualmente verificando
============================================ =============================================================================================================================================================


Regione Lombardia
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Musei riconosciuti da Regione Lombardia <https://www.dati.lombardia.it/Cultura/Musei-riconosciuti-da-Regione-Lombardia/3syc-54zf>`__
                                             | `Anagrafe biblioteche comunali lombarde <https://www.dati.lombardia.it/Cultura/Anagrafe-biblioteche-comunali-lombarde/k2xm-fcgg>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               | La regione si sta predisponendo per la pubblicazione di metadati
                                             | DCAT-AP_IT. Questo consentirà di implementare harvesting del catalogo
                                             | della Regione e di portare i dati aperti all'interno del DAF.
============================================ =================================================================================================================================================


Regione Emilia-Romagna
""""""""""""""""""""""
============================================ ==========================================================================================================================================================================
Obiettivo                                    Stato
============================================ ==========================================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Musei emiliano-romagnoli <http://dati.emilia-romagna.it/dataset/musei-emiliano-romagnoli--1942770d>`__
                                             | `Biblioteche Conservatori di archivi e musei <http://dati.emilia-romagna.it/dataset/biblioteche-conservatori-di-archivi-storici-e-musei-emiliano-romagnoli--4b53c584>`__
                                             | `Arte e cultura <http://dati.emilia-romagna.it/dataset/arte-e-cultura--f97ad51b>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting nel nuovo catalogo nazionale dei file CSV
**Monitoraggio (Obiettivo 5)**               Il formato RDF non è ancora supportato dal DAF
============================================ ==========================================================================================================================================================================


Regione Toscana
"""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Musei <http://dati.toscana.it/dataset/rt-musei>`__
                                             | `Biblioteche <http://dati.toscana.it/dataset/rt-bibl>`__
                                             | `Luoghi dello spettacolo <http://dati.toscana.it/dataset/rt-luoghispett>`__
                                             | `Archivi <http://dati.toscana.it/dataset/rt-archivi>`__
                                             | `Patrimonio artistico <http://dati.toscana.it/dataset/rt-patarch>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting finale nel nuovo catalogo nazionale
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Lazio
"""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Musei <http://dati.lazio.it/catalog/it/dataset/elenco-dei-musei-del-lazio>`__
                                             | `Biblioteche <http://dati.lazio.it/catalog/it/dataset/elenco-delle-biblioteche-del-lazio>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting finale nel nuovo catalogo nazionale
**Monitoraggio (Obiettivo 5)**               Dataset non aggiornati
============================================ =================================================================================================================================================


Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Piani paesaggistici <http://dati.retecivica.bz.it/it/dataset/piani-paesaggistici-informazioni-puntuali>`__
                                             | `Musei <http://dati.retecivica.bz.it/it/dataset/musei-in-alto-adige>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di implementazione ingestion in modalità pull
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Roma Capitale
"""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Biblioteche di Roma <http://dati.comune.roma.it/cms/it/dettaglio_cultura_e_sport.page?contentId=DTS9777>`__
                                             | `Catalogo delle Biblioteche 2018 <http://dati.comune.roma.it/cms/it/dettaglio_cultura_e_sport.page?contentId=DTS9931>`__
                                             | `Musei <http://dati.comune.roma.it/cms/it/dettaglio_cultura_e_sport.page?contentId=DTS2710>`__
                                             | `Ville e giardini storico monumentali <http://dati.comune.roma.it/cms/it/dettaglio_ambiente.page?contentId=DTS3899>`__
                                             | `Spazi adibiti ad attività culturali <http://dati.comune.roma.it/cms/it/dettaglio_cultura_e_sport.page?contentId=DTS4566>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               | In corso collaborazione con l’amministrazione.
                                             | Dataset spesso suddivisi temporalmente e da unire
============================================ =================================================================================================================================================


Comune di Milano
""""""""""""""""
============================================ ====================================================================================================================================================================================================================================================================================
Obiettivo                                    Stato
============================================ ====================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Localizzazione centri congressi <http://dati.comune.milano.it/dataset/ds42_infogeo_centir_congressi_localizzazione_2009>`__
                                             | `Localizzazione biblioteche e archivi <http://dati.comune.milano.it/dataset/ds41_infogeo_biblioteche_localizzazione_2007>`__
                                             | `Localizzazione associazioni culturali <http://dati.comune.milano.it/dataset/ds76_infogeo_associazioni_localizzazione_>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               | Il formato SHP ancora è non supportato dal DAF;
                                             | A breve saranno disponibili dati aggiornati in geojson
============================================ ====================================================================================================================================================================================================================================================================================


Comune di Torino
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Musei <http://aperto.comune.torino.it/?q=node/144>`__
                                             | `Biblioteche civiche <http://aperto.comune.torino.it/?q=node/146>`__
                                             | `Luoghi e locali storici <http://aperto.comune.torino.it/?q=node/145>`__
                                             | `Affluenza del pubblico <http://www.fondazionetorinomusei.it/it/opendata>`__
                                             | `Torino musei <http://www.fondazionetorinomusei.it/it/opendata>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso verifiche con l’amministrazione per il caricamento dei dataset su DAF
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Musei per tipologia <http://opendata.comune.fi.it/statistica_territorio/dataset_0127.html>`__
                                             | `Luoghi freschi <http://opendata.comune.fi.it/ambiente/dataset_0266.html>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Attivo con aggiornamento giornaliero
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================


Comune di Bari
""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Monumenti <http://opendata.comune.bari.it/dataset/monumenti>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non attivo
**Monitoraggio (Obiettivo 5)**               | Dataset obsoleti con data ultimo
                                             | aggiornamento 2006 e creazione 2003
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Luoghi di interesse <https://opendata.comune.palermo.it/opendata-dataset.php?dataset=308>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               | In attesa di risolvere un piccolo problema tecnico
                                             | per harvesting. Il comune ha comunque prodotto
                                             | i metadati conformi al profilo DCAT-AP_IT
                                             | nonostante la presenza di un catalogo disponibile
                                             | su piattaforma proprietaria
============================================ ===========================================================================================================================================================

**Obiettivo 4**: Nell’ambito del lavoro di standardizzazione del DAF il modello di riferimento per questa tipologia di dati è Cultural-ON del MIBACT. L'ontologia Cultural-ON è stata rifattorizzata per consentire l’appartenenza della stessa alla rete OntoPiA (questo ha comportato una revisione della stessa ma solo per abilitare i collegamenti  alle altre ontologie della rete). Sono in corso di definizione alcuni vocabolari controllati in collaborazione con il MIBACT (e.g., vocabolario sulle aree disciplinari quali arte, architettura, storia, ecc.). Non tutte le amministrazioni rilasciano i dataset con metadati conformi al profilo DCAT-AP_IT. Tra quelle conformi si rilevano: Comune di Palermo, Comune di Milano, Firenze via DAF, MIBACT, Regione Toscana, Provincia Autonoma di Bolzano e Regione Emilia Romagna.



Eventi culturali
^^^^^^^^^^^^^^^^
"*Dataset contenenti gli eventi culturali che si tengono all’interno dei luoghi della cultura.*"

Ministero dei Beni e delle Attività Culturali e del Turismo
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Eventi culturali <dati.beniculturali.it/datasets/eventi-culturali/>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso di realizzazione
**Monitoraggio (Obiettivo 5)**
============================================ =============================================================================================================================================================


Regione Piemonte
""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =============================================================================================================================================================


Regione Lombardia
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Calendario sagre e fiere su areee pubbliche <https://www.dati.lombardia.it/Commercio/Calendario-sagre-e-fiere-su-area-pubblica/p2ig-bf59>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo in attesa harvesting finale catalogo nazionale
**Monitoraggio (Obiettivo 5)**               | La regione si sta predisponendo per la pubblicazione di metadati
                                             | DCAT-AP_IT. Questo consentirà di implementare harvesting del catalogo
                                             | della Regione e di portare i dati aperti all'interno del DAF.
============================================ =================================================================================================================================================


Regione Emilia-Romagna
""""""""""""""""""""""
============================================ ==========================================================================================================================================================================
Obiettivo                                    Stato
============================================ ==========================================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Eventi cultura <http://dati.emilia-romagna.it/dataset/eventi-e-r-cultura--a2badb87>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               Il formato XML non è ancora supportato dal DAF
============================================ ==========================================================================================================================================================================


Regione Toscana
"""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Eventi Cultura <http://dati.toscana.it/dataset/rt-eventi-sistcult>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting finale nel nuovo catalogo nazionale
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Lazio
"""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  I dati non sono disponibili presso l'amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Eventi del comune di Trento e altri della PAT <https://dati.trentino.it/dataset/eventi-del-comune-di-trento>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting sul nuovo catalogo nazionale
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili presso l'amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Roma Capitale
"""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili presso l'amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================


Comune di Milano
""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili presso l'amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================


Comune di Torino
""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili presso l'amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================


Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Eventi <http://opendata.comune.fi.it/dataset/dataset_0337.html>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Attivo con aggiornamento giornaliero
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================


Comune di Bari
""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili presso l'amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili presso l'amministrazione
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

**Obiettivo 4**: Nell’ambito del lavoro di standardizzazione del DAF il modello di riferimento per questa tipologia di dati è l’ontologia  Eventi pubblici, con il relativo vocabolario controllato sui tipi di Eventi Pubblici Si noti che tale ontologia è da considerarsi ancora instabile. E’ stato infatti istituito nei primi giorni di Febbraio 2018 un gruppo europeo per la definizione del cosiddetto Core Public Event Vocabulary. L’ontologia pertanto potrà subire modifiche in base ai risultati che emergeranno da tale gruppo di lavoro che vede un’ampia partecipazione italiana (AgID/Team, ANAC, Comune di Palermo, Comune di Udine, Provincia Autonoma di Trento e alcuni istituti del CNR).
Ad esclusione della Regione Lombardia, per cui sono in atto le necessarie azioni per pubblicare metadati conformi al profilo, anche grazie all’ingestion nel DAF in alcuni casi, i dataset disponibili sono corredati di metadati conformi a DCAT-AP_IT.



Catalogo generale dei beni culturali
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
"*Basi di dati sulle schede di catalogo dei beni culturali elaborati nel Sistema generale del Catalogo (SIGEC).*"

Dettaglio per singole amministrazioni coinvolte nella Task Force #DatiPubblici

MIBACT
""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Open ICCD <http://www.catalogo.beniculturali.it/opendata/>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =============================================================================================================================================================

Regione Piemonte
""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili.
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**               I dati sono gestiti dalla soprintendenza ai beni culturali
============================================ =============================================================================================================================================================


Regione Lombardia
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Architetture <https://www.dati.lombardia.it/Cultura/Architetture/kf9b-rj2t>`__
                                             | `Beni culturali Bella Lombardia <https://www.dati.lombardia.it/Cultura/Beni-culturali-Bella-Lombardia/4mr7-hfsh>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**               Si sta predisponendo il flusso di ingestion DAF per interrogare web services della piattaforma della Regione. La Regione si sta predisponendo per l’esposizione dei metadati DCAT-AP_IT. Questo consentirà un più agevole harvesting dei dati nel catalogo nazionale dei dati aperti che potranno poi confluire nel DAF utilizzando flussi già attivi.
============================================ =================================================================================================================================================


Regione Emilia-Romagna
""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Toscana
"""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Lazio
"""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Beni architettonici <http://dati.lazio.it/catalog/it/dataset/schede-dei-beni-architettonici-nella-regione-lazio>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================



Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Catalogo Opere d’Arte <http://dati.trentino.it/dataset/catalogo-opere>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Catalogo dei Beni Culturali in Alto Adige <http://dati.retecivica.bz.it/it/dataset/catalogo-beni-culturali>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Comune di Roma Capitale
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Milano
""""""""""""""""
============================================ ====================================================================================================================================================================================================================================================================================
Obiettivo                                    Stato
============================================ ====================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                  Vedi dataset Lombardia
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ====================================================================================================================================================================================================================================================================================

Comune di Torino
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Beni della Fondazione Torino Musei <http://www.fondazionetorinomusei.it/it/opendata>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Bari
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================



**Obiettivo 4**: Negli scorsi mesi  il MIBACT ha lavorato per l’avvio di un progetto ampio di definizione di ontologie e dati aperti secondo gli standard del web semantico per il mondo dei beni culturali. Il progetto, avviato a fine novembre 2017,  si chiama `ArCo <http://dati.beniculturali.it/progetto-arco-architettura-della-conoscenza/>`__.
Secondo il piano di sviluppo del progetto, una prima versione dell’ontologia per questa tipologia di dati è prevista a marzo 2018. Lo slittamento delle attività relative a questa tipologia di dati è dovuto principalmente al ritardo per il set up complessivo del progetto (reperimento dei fondi, definizione degli obiettivi, definizione degli accordi tra MIBACT e l’Istituto ISTC-CNR  per il supporto alla definizione delle ontologie e alla creazione dei linked open data), molto ampio e inquadrato nel progetto generale della Digital Library del MIBACT.  MIBACT, Province Autonome di Trento e Bolzano rilasciano dataset con metadati conformi a DCAT-AP_IT.



Cammini e percorsi
^^^^^^^^^^^^^^^^^^
"*Base di dati contenente informazioni su itinerari e percorsi (e.g., via francigena). I percorsi e gli itinerari sono descritti in base al tipo di percorso, alle possibili tappe, ai territori attraversati, ecc...*"

In generale si rileva che le amministrazioni, su questa tipologia di dati, non hanno ancora dataset consolidati, a parte alcune eccezioni di seguito riportate. Il dataset era stato concordato insieme al MIBACT (settore turismo). Si noti che il MIBACT ha lavorato in autonomia su questa tipologia di dati rilasciando un portale sui `cammini <http://www.camminiditalia.it/>`__. Tutti i dati del portale, salvo diversa indicazione e a eccezione dei marchi, immagini prodotte da terzi per cui si applicano le licenze dei terzi, sono rilasciati con licenza aperta CC BY 3.0. Tuttavia, si nota che i dati non sono liberamente scaricabili in bulk in un formato aperto, non sono interrogabili via API  e non sono corredati dei relativi metadati conformi al profilo nazionale DCAT-AP_IT.

Regione Piemonte
""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Rete sentieristica delle regione Piemonte <http://www.geoportale.piemonte.it/geocatalogorp/index.jsp>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               Formato SHP ancora non supportato nel DAF
============================================ =============================================================================================================================================================


Regione Lombardia
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Percorsi panoramici <https://www.dati.lombardia.it/Territorio/Percorsi-Panoramici/5rk3-w94r>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  Non ancora attivo
**Monitoraggio (Obiettivo 5)**               Formato SHP ancora non supportato nel DAF
============================================ =================================================================================================================================================


Regione Emilia-Romagna
""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Toscana
"""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Access point wifi via Francigena <http://dati.toscana.it/dataset/regione-toscana-elenco-access-point-wifi-via-francigena>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Lazio
"""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili.
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================



Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili.
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Percorsi MountainBike <http://dati.retecivica.bz.it/it/dataset/rete-viaria-percorsi-mtb-ufficialmente-riconosciuti>`__
                                             | `Percorsi escursionistici <http://dati.retecivica.bz.it/it/dataset/rete-viaria-percorsi-escursionistici>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  In corso.
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Comune di Roma Capitale
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Milano
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Torino
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Walking city <http://opendata.comune.fi.it/cultura_turismo/dataset_0391.html>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Bari
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  Dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================


**Obiettivo 4**: Non è al momento presente, nella rete OntoPiA, un’ontologia di dominio per i cammini. Una parte dei dati  può essere modellata utilizzando sia l’ontologia dei punti di interesse sia l’ontologia dei luoghi/indirizzi, sia l’ontologia dei social media/internet che include la possibilità di modellare oggetti con associate immagini e riferimenti online.

Strutture ricettive
^^^^^^^^^^^^^^^^^^^
"*Base di dati contenente i dati relativi alle informazioni principali che consentono di identificare le strutture ricettive quali agriturismi, strutture alberghiere e strutture extra alberghiere.*"

Regione Piemonte
""""""""""""""""
============================================ =============================================================================================================================================================
Obiettivo                                    Stato
============================================ =============================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Ricettività turistica <http://www.dati.piemonte.it/catalogodati/dato/101074-.html>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ =============================================================================================================================================================


Regione Lombardia
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Strutture ricettive alberghiere ed extra alberghiere <https://www.dati.lombardia.it/Turismo/Strutture-Ricettive-Alberghiere-e-extra-alberghier/745d-3uyg>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | Non ancora attivo
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Emilia-Romagna
""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Strutture ricettive regionali alberghiere ed extra-alberghiere <http://dati.emilia-romagna.it/dataset/strutture-ricettive-regionali-alberghiere-ed-extra-alberghiere--6005440e>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | Aggiornamento harvesting su catalogo nazionale in corso
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Toscana
"""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Strutture ricettive <http://dati.toscana.it/dataset/rt-strutric>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Regione Lazio
"""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | Dati aggregati sulle strutture turistiche
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================



Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Agriturismi <https://dati.trentino.it/dataset/agriturismi-del-trentino>`__,
                                             | `Esercizi alberghieri <https://dati.trentino.it/dataset/esercizi-alberghieri>`__,
                                             | `Esercizi extra alberghieri <https://dati.trentino.it/dataset/esercizi-extra-alberghieri>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In attesa di harvesting per i CSV. XML da convertire in CSV/Json
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Provincia Autonoma di Bolzano
"""""""""""""""""""""""""""""
============================================ ======================================================================================================================================================
Obiettivo                                    Stato
============================================ ======================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Rifugi alpini <http://dati.retecivica.bz.it/it/dataset/rifugi-dell-alto-adige>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ ======================================================================================================================================================

Comune di Roma Capitale
"""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Strutture ricettive <http://dati.comune.roma.it/cms/it/dettaglio_turismo_e_mob.page?contentId=DTS10075>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | Nuovi dataset pubblicati mensilmente da unire e caricare su DAF
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================


Comune di Milano
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | Strutture ricettive `alberghiere <http://dati.comune.milano.it/dataset/ds48_turismotempolibero_strutture_ricettive_alberghiere_2015>`__, `extra-alberghiere <http://dati.comune.milano.it/dataset/ds318-turismotempolibero-strutture-ricettive-extra-alberghiere-2015>`__, `case per ferie e altro <http://dati.comune.milano.it/dataset/ds317-turismotempolibero-case-ferie-altre-strutture-2015>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In attesa di harvesting
**Monitoraggio (Obiettivo 5)**               | Dati del 2015 anche se il dataset è di recente pubblicazione
============================================ =================================================================================================================================================

Comune di Torino
""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | dati disponibili sul portale regionale
**Caricamento DAF e API (Obiettivi 1 e 3)**  |
**Monitoraggio (Obiettivo 5)**               | 
============================================ =================================================================================================================================================

Comune di Firenze
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | dati disponibili sul portale regionale
**Caricamento DAF e API (Obiettivi 1 e 3)**  | 
**Monitoraggio (Obiettivo 5)**               | 
============================================ ===========================================================================================================================================================

Comune di Bari
""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | dati non disponibili
**Caricamento DAF e API (Obiettivi 1 e 3)**
**Monitoraggio (Obiettivo 5)**               |
============================================ ===========================================================================================================================================================

Comune di Palermo
"""""""""""""""""
============================================ ===========================================================================================================================================================
Obiettivo                                    Stato
============================================ ===========================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Luoghi di accoglienza <https://opendata.comune.palermo.it/opendata-dataset.php?dataset=306>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In attesa di harvesting
**Monitoraggio (Obiettivo 5)**
============================================ ===========================================================================================================================================================

Guide turistiche
^^^^^^^^^^^^^^^^
"*Base di dati contenente le principali informazioni sulle Guide Turistiche abilitate d’Italia.
In generale si nota che i dati sono spesso non disponibili in modo strutturato.*"

Si è constatato che attualmente a livello locale la situazione è particolarmente variegata: sembra che il dato fosse in precedenza di competenza delle province, ora talvolta è in capo alle città metropolitane, in altri casi alle regioni. Per questo motivo sono raramente disponibili come open data o, quando lo sono, i dati spesso non sono aggiornati. Di seguito si riportano le sole amministrazioni per le quali è presente il dataset in qualche forma:

Regione Lombardia
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Elenco guide alpine <https://www.dati.lombardia.it/Sport/Elenco-Guide-Alpine/ixav-aubn>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | Non ancora attivo
**Monitoraggio (Obiettivo 5)**               | Dati del 2014
============================================ =================================================================================================================================================

Regione Toscana
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Guide turistiche e ambientali, accompagnatori e guide alpine <http://www.regione.toscana.it/-/guide-turistiche-e-ambientali-accompagnatori-e-guide-alpine>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | Non attivo
**Monitoraggio (Obiettivo 5)**               | Dati in xslx
============================================ =================================================================================================================================================

Comune di Torino
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Guide turistiche <http://www.cittametropolitana.torino.it/turismo/guide/>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | Non attivo
**Monitoraggio (Obiettivo 5)**               | Dati della città metropolitana in xsl, non aggiornati
============================================ =================================================================================================================================================

Comune di Bari
"""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  | `Guide turistiche <http://opendata.comune.bari.it/dataset/guide-turistiche-del-comune-di-bari>`__
**Caricamento DAF e API (Obiettivi 1 e 3)**  | In attesa di harvesting
**Monitoraggio (Obiettivo 5)**               | Dati del 2012
============================================ =================================================================================================================================================


Economia e finanze
------------------

Anagrafica Startup PMI innovative e incubatori certificati
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

============================================= ======================================================================================================================================================================================================================================================================================
Obiettivo                                     Stato
============================================= ======================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                   | Il `dataset <http://startup.registroimprese.it/isin/static/pminnovative/index.html?slideJump=31>`__ è disponibile sul portale del Registro Imprese
                                              | e scaricabile previa indicazione di un indirizzo email.
                                              | Secondo le note legali presenti sul sito, non sembra possibile
                                              | considerare i dati come dati aperti
**Caricamento nel DAF (Obiettivo 1)**         | Al momento non abbiamo notizie da InfoCamere, con cui le
                                              | comunicazioni si sono interrotte in data xxx.
**Disponibilità di API (Obiettivo 3)**        Al meglio delle nostre conoscenze non è attualmente raggiunto
**Modellazione dati (Obiettivo 4)**           | Nell’ambito della rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__
                                              | di ontologie e vocabolari controllati per la pubblica amministrazione
                                              | l’ontologia delle `organizzazioni (parte privata) <https://github.com/italia/daf-ontologie-vocabolari-controllati/tree/master/Ontologie/COV/latest>`__ può essere usata per la modellazione di questi dati.
                                              | Il dataset non al momento corredato di metadati conformi al profilo DCAT-AP_IT
============================================= ======================================================================================================================================================================================================================================================================================


Statistiche Startup PMI innovative e incubatori certificati
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

============================================= ======================================================================================================================================================================================================================================================================================
Obiettivo                                     Stato
============================================= ======================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                   | Il `dataset <http://startup.registroimprese.it/isin/static/startup/index.html?slideJump=32>`__ è disponibile sul portale del Registro Imprese
                                              | e scaricabile previa indicazione di un indirizzo email.
                                              | Secondo le note legali presenti sul sito, non sembra possibile
                                              | considerare i dati come dati aperti
**Caricamento nel DAF (Obiettivo 1)**         | Al momento non abbiamo notizie da InfoCamere, con cui le
                                              | comunicazioni si sono interrotte in data xxx.
**Disponibilità di API (Obiettivo 3)**        Al meglio delle nostre conoscenze non è attualmente raggiunto
**Modellazione dati (Obiettivo 4)**           | Nell’ambito della rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__
                                              | di ontologie e vocabolari controllati per la pubblica amministrazione
                                              | l’ontologia delle `organizzazioni (parte privata) <https://github.com/italia/daf-ontologie-vocabolari-controllati/tree/master/Ontologie/COV/latest>`__ può essere usata per la modellazione di *una parte di questi dati*.
                                              | Il dataset non al momento corredato di metadati conformi al profilo DCAT-AP_IT
============================================= ======================================================================================================================================================================================================================================================================================



Statistiche del registro imprese - Movimprese
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

============================================= ======================================================================================================================================================================================================================================================================================
Obiettivo                                     Stato
============================================= ======================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                   | Il `dataset <https://www.infocamere.it/movimprese>`__ è disponibile sul portale del Registro Imprese
                                              | e scaricabile.
                                              | Al meglio delle nostre conoscenze non si ravvedono vincoli
                                              | per il riutilizzo dei dati che possono così essere considerati
                                              | aperti by default.
**Caricamento nel DAF (Obiettivo 1)**         | Al momento non abbiamo notizie da InfoCamere, con cui le
                                              | comunicazioni si sono interrotte in data xxx.
**Disponibilità di API (Obiettivo 3)**        Al meglio delle nostre conoscenze non è attualmente raggiunto
**Modellazione dati (Obiettivo 4)**           | Nell’ambito della rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__
                                              | di ontologie e vocabolari controllati per la pubblica amministrazione
                                              | l’ontologia delle `organizzazioni (parte privata) <https://github.com/italia/daf-ontologie-vocabolari-controllati/tree/master/Ontologie/COV/latest>`__ può essere usata per la modellazione di *una parte di questi dati*.
                                              | Il dataset non al momento corredato di metadati conformi al profilo DCAT-AP_IT
============================================= ======================================================================================================================================================================================================================================================================================


Catasto - Osservatorio Mercato Immobiliare
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

============================================= ======================================================================================================================================================================================================================================================================================
Obiettivo                                     Stato
============================================= ======================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                   | Il `dataset <http://www.agenziaentrate.gov.it/wps/content/nsilib/nsi/schede/fabbricatiterreni/omi/banche+dati/quotazioni+immobiliari/download+gratuito>`__ delle quotazioni OMI, a partire dal primo semestre 2016,
                                              | è disponibile gratuitamente per gli utenti registrati a Fisconline e Entratel
                                              | Il dataset non può essere completamente considerato aperto.
**Caricamento nel DAF (Obiettivo 1)**         Il dataset è stato caricato nel DAF e sarà reso disponibile in open data (?????)
**Disponibilità di API (Obiettivo 3)**        Sì attraverso il DAF
**Modellazione dati (Obiettivo 4)**           | Nell’ambito della rete `OntoPiA <https://github.com/italia/daf-ontologie-vocabolari-controllati>`__
                                              | di ontologie e vocabolari controllati per la pubblica amministrazione
                                              | l’ontologia dei luoghi/indirizzi può essere usata per la modellazione di *una parte di questi dati*.
                                              | Il dataset è corredato di metadati conformi al profilo DCAT-AP_IT via DAF
============================================= ======================================================================================================================================================================================================================================================================================


Catasto - Consultazione rendite
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Il dataset non è disponibile né come dato aperto né all'interno del DAF.

Giustizia, sistema giuridico e sicurezza pubblica
-------------------------------------------------

Normattiva
^^^^^^^^^^
Si sta lavorando insieme a Istituto Poligrafico Zecca dello Stato (IPZS) e altri partner, su un miglioramento complessivo del servizio, che comprende anche un lavoro su standard normativi e rilascio degli stessi in open data. Per questa attività il nuovo obiettivo è quello di rilasciare il risultato del lavoro per fine giugno 2018.



Regioni e città
---------------

Catasto - Archivio Storico dei Comuni
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

============================================= ======================================================================================================================================================================================================================================================================================
Obiettivo                                     Stato
============================================= ======================================================================================================================================================================================================================================================================================
**Open Data (Obiettivo 2)**                   | Il dataset dell’Agenzia delle Entrate è `liberamente scaricabile <http://www.agenziaentrate.gov.it/wps/content/nsilib/nsi/schede/fabbricatiterreni/archivio+comuni+e+stati+esteri/consultazione+archivio+comuni+stati+esteri/indice+consultazione+archivio+comuni+e+stati+esteri>`__
                                              | sebbene non sia indicata la licenza per il riutilizzo del dataset.
                                              | Nelle note legali dell'intero sito dell'Agenzia
                                              | emerge come i dati contenuti nel sito non siano open data.
                                              | Esiste tuttavia un altro dataset più completo pubblicato da ANPR
                                              | con cui è prevista l’integrazione con il DAF.
                                              | Il dataset è al momento `disponibile liberamente <http://anpr.readthedocs.io/en/latest/tab/tab_comuni.html>`__
                                              | sebbene non in formato aperto.
**Caricamento nel DAF e API (Obiettivi 1,3)** | Il dataset completo dell'ANPR è già presente nel DAF
                                              | e sarà reso disponibile come open data entro fine aprile 2018
**Modellazione dati (Obiettivo 4)**           | L’ontologia dei luoghi è stata utilizzata,
                                              | a partire dal dataset “Archivio Storico dei Comuni” dell’ANPR,
                                              | per una prima prova di produzione di Linked Open Data all’interno
                                              | del DAF. Il dataset è corredato di metadati DCAT-AP_IT via DAF.
============================================= ======================================================================================================================================================================================================================================================================================



Anagrafe Nazionale Numeri Civici e Strade Urbane
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

====================================================== ===========================================================================================================================================================
Obiettivo                                              Stato
====================================================== ===========================================================================================================================================================
**Open Data , API, Caricamento DAF (Obiettivi 1,2,3)** | Nel corso degli scorsi mesi si è lavorato per poter
                                                       | sbloccare la creazione della base di dati. Tuttavia,
                                                       | la pubblicazione della base di dati è attualmente presso
                                                       | il parere positivo del Garante per la Protezione
                                                       | dei Dati Personali. Solo dopo
                                                       | sarà possibile procedere con l’ingestione nel DAF
                                                       | e conseguentemente con il rilascio in Linked Open Data.
**Modellazione dati (Obiettivo 4)**                    | L’ontologia dei luoghi/indirizzi è attualmente
                                                       | l’ontologia deputata alla modellazione
                                                       | di questa tipologia di dati. E’ in corso una collaborazione
                                                       | stretta con ISTAT per produrre due ontologie
                                                       | separate: luoghi e indirizzi.
                                                       | Si stima questo lavoro possa essere pronto nei prossimi
                                                       | mesi (primavera 2018). I dati saranno corredati di
                                                       | metadati DCAT-AP_IT via DAF.
====================================================== ===========================================================================================================================================================



Ulteriori banche dati in corso di integrazione
----------------------------------------------
Alcune delle sperimentazioni in corso su dati pubblici coinvolgono:

1. AgID - Monitoraggio Fascicolo Sanitario Elettronico (FSE)
2. AgID - Indice Pubblica Amministrazione - L’ontologia delle organizzazioni (parte pubblica) sarà usata per produrre via DAF i Linked Open Data del registro. (Si stima il rilascio dei Linked Open Data dell'Indice PA entro fine primavera)
3. CISIS - Accessi servizi qualificati (SPID) - L’ontologia sui servizi pubblici CPSV-AP_IT potrà essere valutata per la modellazione di questa tipologia di dati
4. Corte dei Conti - Banca dati delle sentenze
5. INAIL - Infortuni sul lavoro
6. MEF RGS - Programmi cofinanziati dall’Unione europea nel periodo 2007/2013
7. MISE - Registro aiuti di stato
8. MIT- Veicoli
9. Presidenza del Consiglio dei Ministri - Politiche di coesione (OpenCoesione)
10. Presidenza del Consiglio dei Ministri DIPE - OpenCUP
11. SOSE - Fabbisogni e spesa dei comuni e province (OpenCivitas)
12. Comune di Torino - Segnalazioni Contact Center
13. Comune di Firenze - Stato colonnine di ricarica veicoli elettrici
14. ANAC - Appalti e contratti. In corso di definizione l’ontologia sui contratti pubblici e appalti per la modellazione di questa tipologia di dati
15. UNIBO


Conclusioni finali
------------------
Dalla situazione descritta nelle precedenti sezioni emerge un quadro di apertura dei dataset abbastanza positivo, soprattutto quando le pubbliche amministrazioni coinvolte sono quelle locali.
Nell'ambito della Task Force #DatiPubblici non tutte le amministrazioni hanno concorso, nel corso del 2017, ugualmente e direttamente nel rilascio dei relativi dati in open data, come previsto e riportato nelle precedenti sezioni del presente documento.
Si rileva però che alcune di loro sono state particolarmente attive, anche grazie allo stimolo della pubblicazione dell'elenco delle basi di dati chiave, sia nell'apertura che nella collaborazione con il DAF.
Dal punto di vista della modellazione e della presenza dei metadati DCAT-AP_IT la situazione in generale è abbastanza buona. Molte delle amministrazioni della Task Force si sono dotate degli strumenti per adeguarsi al profilo, o hanno utilizzato il DAF stesso per raggiungere tale obiettivo. In termini di modellazione dei dati, sono state definite diverse ontologie, sebbene alcune ancora instabili, che forniscono uno schema dati comune per la maggior parte delle basi di dati/dataset presenti nell'elenco.
Dal punto di vista invece delle pubbliche amministrazioni centrali si riscontrano più difficoltà nel raggiungimento degli obiettivi: con l'eccezione del Ministero dei Beni Culturali e del Turismo, parte cultura, gli obiettivi per le altre amministrazioni centrali non sono stati raggiunti entro il 2017. Per alcune basi di dati ci sono stati ritardi. Tali ritardi, dovuti anche alla complessità dei sistemi e processi coinvolti, saranno comunque recuperati nel corso della prima parte metà del 2018 (e.g., normattiva); per altri dataset non sembra realistico ipotizzare la loro disponibilità nel DAF e come dati di tipo aperto durante il 2018. Nonostante questo scenario, è bene sottolineare che altre amministrazioni centrali, diverse da quelle originariamente indicate nel documento, hanno comunque collaborato nel corso del 2017 per utilizzare il DAF come strumento di condivisione, standardizzazione e apertura dei propri dati (e.g., Corte dei Conti, ANAC, ecc.).
Infine i ritardi per le operazioni di caricamento nel DAF sono stati principalmente dovuti ai ritardi nello sviluppo della piattaforma tecnologica e nell'individuazione della futura amministrazione titolare del DAF. Tuttavia, per tutte quelle PA, soprattutto della Task Force, dove sono in corso attività di sperimentazione e di ingestione, si prevede la disponibilità dei dati nel DAF e come open data (qualora possibile), entro la prima metà del 2018.
