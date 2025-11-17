# SOC-Lab (Mini Security Operations Center)

Questo progetto è un Mini SOC costruito per studiare, testare e simulare le principali funzioni difensive presenti in un ambiente reale.  
L’obiettivo è comprendere come firewall, IDS, SIEM e sistemi di alerting lavorano insieme per rilevare, analizzare e rispondere agli incidenti di sicurezza.

Il lab integra più componenti, ognuna con un ruolo preciso: filtrare il traffico, individuare comportamenti sospetti, raccogliere log, correlare eventi e inviare notifiche immediate. È una piattaforma completa per allenarmi come Blue Team e comprendere il flusso di lavoro di un SOC operativo, in scala ridotta.

---

## 🔧 Componenti principali

- **pfSense** – Firewall e router principale.  
  Gestisce regole, NAT e filtraggio del traffico.

- **Suricata** – IDS/IPS installato su pfSense.  
  Analizza in tempo reale il traffico e rileva minacce note o sospette.

- **Splunk** – SIEM utilizzato per raccogliere log, indicizzare eventi e creare alert basati su correlazioni.

- **Bot Telegram** – Sistema di alerting.  
  Invia notifiche immediate quando Splunk rileva attività anomale o potenzialmente malevole.

- **Windows Server (DNS)** – Fornisce un servizio critico interno al lab, utile per analizzare query, traffico e possibili abusi.

- **Windows 10 Client** – Endpoint utilizzato per generare traffico, simulare attività utente e testare rilevamenti.

---

## 🎯 Obiettivo del progetto

- Comprendere come si struttura un ambiente difensivo reale.  
- Simulare il funzionamento di un SOC in piccolo.  
- Allenare detection, analisi log, alerting e risposta.  
- Studiare il comportamento degli attacchi all’interno della rete.  
- Integrare firewall, IDS e SIEM in un unico flusso operativo.

Questo Mini SOC è una palestra personale per imparare a gestire una rete in modo sicuro, identificare minacce e reagire con logiche operative reali.

---

## 🧩 Architettura generale (schema logico)
