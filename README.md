# Progetto Master: App di meditazione e benessere interiore

## 🧘 Panoramica del Progetto
L'applicazione è progettata per combinare i benefici della meditazione con strumenti strutturati di crescita personale, aiutando i clienti a monitorare e raggiungere i propri obiettivi di benessere nel breve, medio e lungo periodo.

Sviluppato in ambiente Python all'interno di un Jupyter Notebook, il software adotta un'architettura modulare basata su classi e funzioni, garantendo robustezza, manutenibilità e rispetto rigoroso degli standard di formattazione **PEP 8**.

---

## 🛠️ Stack tecnologico e tecniche implementate
Il codice è interamente basato su **Python puro** e sfrutta le seguenti strutture e logiche di programmazione:
* **Programmazione a Oggetti (OOP):** Definizione della classe `Utente` per la gestione del profilo e dell'identità di sessione.
* **Strutture Dati Modulari:** Gestione della collezione tramite liste di dizionari per associare in modo flessibile parametri testuali e numerici.
* **Gestione Robusta degli Input (Error Handling):** Validazione interattiva tramite cicli `while` e blocchi `try-except` per prevenire errori (`ValueError` / `IndexError`) durante la scelta degli obiettivi.
* **Case-Insensitive Search & Filtri Avanzati:** Utilizzo dei metodi `.lower()` e `.strip()` per garantire ricerche affidabili e combinazione di parametri opzionali multipli.

---

## ⚙️ Funzionalità principali dell'applicazione

Il sistema mette a disposizione un set completo di funzioni modulari per la gestione e l'analisi dei dati:

1. **Registrazione Nuovi Elementi (`registra_sessione`):** 
   Permette di registrare una nuova sessione di meditazione associandola a parametri specifici quali utente, musica di sottofondo, durata in minuti, ambiente naturale e obiettivo di crescita personale.
2. **Visualizzazione Completa (`mostra_sessioni`):** 
   Stampa a schermo l'elenco dettagliato di tutte le sessioni registrate all'interno della collezione, fornendo una panoramica chiara e ordinata.
3. **Ricerca Elementi (`cerca_sessioni`):** 
   Consente di interrogare la collezione in base a criteri specifici (come l'obiettivo), restituendo tutti i risultati corrispondenti in modo affidabile e senza interruzioni anticipate.
4. **Statistiche Avanzate (`calcola_statistiche`):** 
   Elabora metriche globali (numero totale di sessioni, minuti complessivi dedicati al benessere e durata media) e calcola la distributione statistica per singola categoria tramite dizionari dinamici.
5. **Filtraggio Avanzato (`filtra_sessioni`):** 
   Permette di applicare filtri combinati e opzionali (es. ricerca mirata per obiettivo, ambiente e soglia massima di durata) per analisi approfondite sui dati dei clienti.

---

## 🚀 Esecuzione del Progetto
Il notebook è strutturato in modo sequenziale:
1. Definizione delle classi, delle costanti globali e delle funzioni core.
2. Inizializzazione del dataset di esempio (`carica_sessioni_esempio`).
3. Blocco finale di esecuzione e dimostrazione interattiva di tutte le funzionalità in azione.
