# 🏀 Basket Scoreboard

Un segnapunti digitale moderno, minimalista e completamente reattivo per partite di pallacanestro (5v5, 3v3, 2v2, 1v1). Pensato per essere utilizzato direttamente da smartphone a bordo campo, su tablet o da desktop. Funziona al 100% offline come Progressive Web App (PWA).

---

## ✨ Funzionalità Principali

### ⏱️ Gestione Tempo e Quarti
- **Regolamento Basket**: Selezione rapida tra `1°Q`, `2°Q`, `3°Q`, `4°Q`, `OT` e `2°OT`.
- **Cronometro Flessibile**: Modalità Conto alla Rovescia (default 10:00 FIBA) o In Avanti, con avvisi sonori/vibrazione a fine quarto.
- **Shot Clock (24s / 14s)**: Timer dei 24 secondi sempre accessibile con reset rapido a 24s o 14s (per rimbalzi offensivi/infrazioni).

### 🎯 Punteggi e Statistiche Rapide
- **Canestri**: Tasti rapidi dedicati per **+3 PT (Tripla)**, **+2 PT (Canestro)** e **+1 PT (Tiro Libero)**.
- **Correzione Rapida**: Cancellazione immediata di qualsiasi evento errato tramite il feed cronaca con ricalcolo automatico del punteggio.
- **Rimbalzi & Assist**: Tracciamento dei rimbalzi e degli assist direttamente associabili al marcatore.

### ⚠️ Regolamento Falli & Bonus
- **Falli Personali (x/5)**: Conteggio progressivo per singolo giocatore con badge visivo e avviso al raggiungimento del 5° fallo (esclusione dal campo).
- **Spia BONUS Squadra**: Monitoraggio dei falli cumulativi di squadra per quarto (`X/4`). Al 5° fallo la spia si illumina di rosso (`🚨 BONUS ATTIVO`) per segnalare i tiri liberi automatici. Azzeramento automatico a ogni cambio quarto.

### 👥 Gestione Roster e Sostituzioni
- **Formazioni 5v5 di Partenza**: Ruoli classici preimpostati (Playmaker, Guardia, Ala Piccola, Ala Grande, Centro) + riserve.
- **Flessibile per Ogni Formato**: Adattabile al volo per streetball (1v1, 3v3 Playground, ecc.).
- **Sostituzioni Ufficiali**: Cambio rapido giocatore in campo/panchina con registrazione automatica a referto.

### 💾 Salvataggio, Storico e Condivisione
- **Persistenza Locale**: Lo stato della partita viene salvato in automatico nel `localStorage` (nessuna perdita di dati in caso di refresh o chiusura accidentale).
- **Archivio Partite**: Salva le partite giocate con tabellino completo, punteggio finale e cronaca evento per evento.
- **Condivisione**: Esportazione e condivisione immediata del tabellino finale tramite Web Share API o copia negli appunti.
- **Offline / PWA Ready**: Include un Service Worker (`sw.js`) per funzionare senza connessione internet una volta aperto.
