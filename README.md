# Progetti Accademici: Basi di Dati & Sviluppo Applicazioni Software

Questo archivio raccoglie la documentazione e i report tecnici relativi a vari progetti del percorso **Undergraduate** in Informatica.

-----

## 🏠 1. Progetto Basi di Dati: Piattaforma Home Booking

**Descrizione:** Progettazione completa di una base di dati per un servizio di affitto e prenotazione alloggi (stile Airbnb). Il sistema gestisce diverse tipologie di alloggio (appartamenti, stanze private/condivise) e profili utente differenziati (Ospiti, Host, Superhost).

### Caratteristiche Principali:

  * **Modellazione E-R:** Definizione di entità complesse come Utenti, Alloggi, Prenotazioni e un sofisticato sistema di Recensioni incrociate.
  * **Logica di Business:** Implementazione di requisiti per lo stato di "Superhost" basati su performance (10+ soggiorni, 100+ notti, tasso di cancellazione \< 1%).
  * **Operazioni SQL:** Script per la creazione del database, popolamento e query per operazioni di business (es. calcolo medie valutazioni, gestione disponibilità).
  * **Documentazione:** [Visualizza Elaborato Tecnico](./Prog_DataBase/Elaborato_Prog_DataBase_Mattia_Liberatore.pdf)

-----

## 🍽️ 2. Sviluppo Applicazioni Software (SAS): Sistema Catering

**Descrizione:** Progettazione e sviluppo di un sistema gestionale per un'azienda di catering. Il progetto segue un approccio di ingegneria del software rigoroso, partendo dall'analisi dei requisiti fino alla progettazione dei diagrammi di classe e sequenza.

### Moduli Analizzati:

  * **Gestione Turni:** Sviluppo di casi d'uso (UC) per la definizione di turni preparatori e di servizio, gestione delle scadenze per la disponibilità e pubblicazione del tabellone turni.
  * **Gestione Compiti (Kitchen Tasks):** Progettazione del foglio riepilogativo per i servizi, assegnazione di preparazioni e ricette ai cuochi, e ordinamento delle priorità in cucina.
  * **Architettura:** Utilizzo del pattern **Expert** e **Creator** per l'assegnazione delle responsabilità e diagrammi DCD (Design Class Diagram) per la struttura delle classi.

### Artefatti Tecnici:

  * [Allegato Tecnico: Gestione Turni](./Prog_Sviluppo_Applicazioni_Software/Allegato_Tecnico_Gestione_Turni.pdf)
  * [Allegato Tecnico: Gestione Compiti](./Prog_Sviluppo_Applicazioni_Software/Allegato_Tecnico_Gestione_Compiti.pdf)

-----

## 🚀 Come navigare il portfolio

Ogni sottocartella contiene la documentazione specifica e, dove disponibile, gli schemi logici o il codice sorgente.

  * `/Prog_DataBase`: Contiene l'analisi dei requisiti e il codice SQL.
  * `/Prog_Sviluppo_Applicazioni_Software`: Contiene i diagrammi UML e i casi d'uso dettagliati.
