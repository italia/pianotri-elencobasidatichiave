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

La seguente tabella riporta il dettaglio per singole amministrazioni comunali coinvolte nella Task Force #DatiPubblici.

Provincia Autonoma di Trento
""""""""""""""""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Riassunto rilievo di traffico automatizzato <https://dati.trentino.it/dataset/riassunto-rilievo-traffico-automatico-stazioni-fisse-anno-2015>`__
**Caricamento DAF e API (Obiettivo 1 e 3)**  In attesa di harvesting nel nuovo catalogo nazionale
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
**Caricamento DAF e API (Obiettivo 1 e 3)**  In corso di implementazione ingestion in modalità pull
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================

Comune di Roma
""""""""""""""
============================================ =================================================================================================================================================
Obiettivo                                    Stato
============================================ =================================================================================================================================================
**Open Data (Obiettivo 2)**                  `Stato del traffico <https://romamobilita.it/it/azienda/open-data/api-real-time>`__
**Caricamento DAF e API (Obiettivo 1 e 3:**  in corso verifica integrabilità dell’API
**Monitoraggio (Obiettivo 5)**
============================================ =================================================================================================================================================
