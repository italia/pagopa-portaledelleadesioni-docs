
|image0|

+-------------------------------------------------+
| **Portale delle Adesioni Manuale Utente**       |
|                                                 |
| **Versione 2.2 – 31 luglio 2018**               |
+-------------------------------------------------+


**DEFINIZIONI E ACRONIMI**

+----------------------------------------+-----------------------------------+
| Definizione/Acronimo                   | Descrizione                       |
+========================================+===================================+
| AgID                                   | Ente istituito ai sensi del       |
|                                        | decreto legge n. 83 del 22 giugno |
| Agenzia per l’Italia Digitale          | 2012 convertito con legge n. 134  |
|                                        | del 7 agosto 2012 (già DigitPA).  |
|                                        |                                   |
|                                        | Gestore di pagoPA.                |
+----------------------------------------+-----------------------------------+
| CAD                                    | Codice dell'amministrazione       |
|                                        | digitale: decreto legislativo 7   |
|                                        | marzo 2005, n. 82 aggiornato con  |
|                                        | le modifiche e integrazioni       |
|                                        | successivamente introdotte.       |
+----------------------------------------+-----------------------------------+
| GAD                                    | Processo di autorizzazione basato |
|                                        | sull’identificazione              |
|                                        | dell’Aderente mediante utilizzo   |
|                                        | dei certificati x.509 per la      |
|                                        | creazione del canale TLS verso il |
|                                        | Nodo dei pagamenti.               |
+----------------------------------------+-----------------------------------+
| GTS                                    | Gateway Trasporto Sicuro          |
|                                        |                                   |
|                                        | Coppia di "End-Point" di rete che |
|                                        | consente il trasporto sicuro dei  |
|                                        | protocolli applicativi verso il   |
|                                        | nodo dei pagamenti.               |
+----------------------------------------+-----------------------------------+
| IPA                                    | L'Indice delle Pubbliche          |
|                                        | Amministrazioni (IPA) è           |
|                                        | l'archivio ufficiale degli Enti   |
| Indice delle Pubbliche Amministrazioni | pubblici e dei Gestori di         |
|                                        | pubblici servizi.                 |
|                                        |                                   |
|                                        | È realizzato e gestito            |
|                                        | dall'Agenzia per l'Italia         |
|                                        | Digitale.                         |
|                                        |                                   |
|                                        | Contiene informazioni dettagliate |
|                                        | sugli Enti, sulle strutture       |
|                                        | organizzative, sulle competenze   |
|                                        | dei singoli uffici e sui servizi  |
|                                        | offerti.                          |
+----------------------------------------+-----------------------------------+
| Linee guida                            | Il documento “Linee guida per     |
|                                        | l'effettuazione dei pagamenti a   |
|                                        | favore delle pubbliche            |
|                                        | amministrazioni e dei gestori di  |
|                                        | pubblici servizi”                 |
+----------------------------------------+-----------------------------------+
| Nodo dei Pagamenti-SPC                 | Piattaforma tecnologica per       |
|                                        | l’interconnessione e              |
|                                        | l’interoperabilità tra le         |
|                                        | Pubbliche Amministrazioni e i     |
|                                        | Prestatori di Servizi di          |
|                                        | Pagamento di cui all’art. 81,     |
|                                        | comma 2-bis del CAD. Per le       |
|                                        | regole e le modalità di utilizzo  |
|                                        | di detta piattaforma si rinvia al |
|                                        | documento “Linee Guida per        |
|                                        | l’effettuazione dei pagamenti     |
|                                        | elettronici” pubblicato sul sito  |
|                                        | dell’Agenzia per l’Italia         |
|                                        | digitale                          |
+----------------------------------------+-----------------------------------+
| pagoPA                                 | Il sistema dei pagamenti a favore |
|                                        | delle pubbliche amministrazioni e |
|                                        | dei gestori di pubblici servizi.  |
|                                        | Si avvale di una Piattaforma      |
|                                        | tecnologica per                   |
|                                        | l’interconnessione e              |
|                                        | l’interoperabilità tra le         |
|                                        | Pubbliche Amministrazioni e i     |
|                                        | Prestatori di Servizi di          |
|                                        | Pagamento di cui all’art. 81,     |
|                                        | comma 2-bis del CAD, nota anche   |
|                                        | come Nodo dei Pagamenti-SPC       |
+----------------------------------------+-----------------------------------+
| PdD                                    | Porta di Dominio SPCoop           |
+----------------------------------------+-----------------------------------+
| PSP                                    | Prestatore di Servizi di          |
|                                        | Pagamento.                        |
+----------------------------------------+-----------------------------------+
| PdDE                                   | Porta di Dominio Equivalente      |
|                                        |                                   |
|                                        | Oggetto software analogo alla PdD |
|                                        | standard SPCoop ovvero altro      |
|                                        | oggetto software in grado di      |
|                                        | trattare le funzioni di           |
|                                        | trasferimento definite nelle      |
|                                        | specifiche AgID e garantire gli   |
|                                        | stessi livelli di tracciabilità,  |
|                                        | autenticazione e confidenzialità  |
|                                        | nello scambio delle informazioni  |
|                                        | previsti per le PdD standard      |
|                                        | SPCoop.                           |
+----------------------------------------+-----------------------------------+
| PdD-EA                                 | Porta di Dominio SPCoop Ente      |
|                                        | Aggregatore                       |
|                                        |                                   |
|                                        | Porta di Dominio SPCoop di un     |
|                                        | Ente Aggregatore che la rende     |
|                                        | disponibile a singoli Enti        |
|                                        | Creditori per consentire loro     |
|                                        | l’accesso a SPCoop allo scopo di  |
|                                        | accedere ai servizi di pagoPA     |
+----------------------------------------+-----------------------------------+
| RWD                                    | Tecnica di web design per la      |
|                                        | realizzazione di siti in grado di |
| Responsive Web Design                  | adattarsi graficamente in modo    |
|                                        | automatico al dispositivo coi     |
|                                        | quali vengono visualizzati.       |
+----------------------------------------+-----------------------------------+
| SANP                                   | Specifiche attuative di pagoPA,   |
|                                        | Allegato B alle Linee guida.      |
+----------------------------------------+-----------------------------------+
| Servizi di Nodo                        | Funzionalità rese disponibili da  |
|                                        | pagoPA.                           |
+----------------------------------------+-----------------------------------+
| Servizio                               | L’insieme delle funzioni e delle  |
|                                        | strutture tecniche, organizzative |
|                                        | e di governo finalizzate          |
|                                        | all’interconnessione e            |
|                                        | all’interoperabilità tra gli enti |
|                                        | creditori ed i PSP aderenti, ai   |
|                                        | sensi dell’articolo 81, comma     |
|                                        | 2-bis, del CAD.                   |
+----------------------------------------+-----------------------------------+
| SGPdD                                  | Software per la gestione della    |
|                                        | Porta di Dominio SPCoop           |
+----------------------------------------+-----------------------------------+
| SPC                                    | Sistema Pubblico di Connettività. |
+----------------------------------------+-----------------------------------+
| SPCoop                                 | Sistema Pubblico di Connettività  |
|                                        | e cooperazione.                   |
+----------------------------------------+-----------------------------------+
| User experience                        | Le percezioni e le reazioni di un |
|                                        | utente che derivano dall'uso o    |
|                                        | dall'aspettativa d'uso di un      |
|                                        | prodotto, sistema o servizio.     |
|                                        | Nell'attuale contesto assume      |
|                                        | prevalentemente il significato di |
|                                        | *usabilità*.                      |
+----------------------------------------+-----------------------------------+
| Utilizzatore finale                    | Cittadini, figure professionali o |
|                                        | imprese, nonché pubbliche         |
|                                        | amministrazioni che effettuano    |
|                                        | pagamenti elettronici a favore di |
|                                        | un ente creditore.                |
+----------------------------------------+-----------------------------------+

.. |image0| image:: media/header.png
   :width: 3.93701in
   :height: 0.89306in
