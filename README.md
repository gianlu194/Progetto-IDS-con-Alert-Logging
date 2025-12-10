# IDS con LOGGIN e ALERT

Questo progetto è un laboratorio di sicurezza costruito per studiare e testare il funzionamento di un IDS con alerting e logging.
L’obiettivo è comprendere come monitorare il traffico di rete, rilevare comportamenti sospetti, centralizzare i log e inviare notifiche automatiche tramite bot Telegram in caso di eventi critici.

Il lab integra più componenti: un firewall pfSense, Snort per l’analisi degli eventi, Splunk per il logging e Windows Server con Active Directory come ambiente protetto. È una piattaforma pratica per esercitarsi in difesa di rete e comprendere il flusso di lavoro di monitoraggio e gestione degli alert in un contesto controllato.

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

