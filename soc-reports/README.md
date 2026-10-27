# SOC Analyst — Portfolio tecnico

Raccolta di **report tecnici difensivi (Blue Team)** prodotti durante il mio percorso in **Cybersecurity & Ethical Hacking**.
I report documentano attività di laboratorio su **Security Monitoring, Threat Intelligence, Malware Analysis, Hardening e Network Security**.

> **Nota etica** — Tutte le attività sono state svolte in ambienti di laboratorio isolati e autorizzati, a scopo formativo. Nessun sistema di produzione è stato coinvolto.

**Autore:** Leonardo Onori — Junior SOC Analyst / Cyber Security Analyst
📧 leonardoonori1@gmail.com · 🔗 [LinkedIn](https://linkedin.com/in/leonardo-onori) · 💻 [GitHub](https://github.com/leonardoonori1-ops)

---

## Indice dei report

| # | Area | Report | Competenze |
|---|------|--------|------------|
| 01 | **SIEM & Log Analysis** | Detection con Splunk | SIEM, SPL, correlazione eventi, rilevamento brute-force |
| 02 | **Threat Intelligence & IOC** | Analisi IOC su cattura di rete | IOC, MITRE ATT&CK (T1046), threat hunting, mitigazioni |
| 03 | **Malware Analysis** | Vidar/Lumma Stealer, W32.Nimda, AdwCleaner | Analisi statica/dinamica, sandbox, IOC, hashing |
| 04 | **Hardening & Access Control** | Active Directory (Windows Server 2022), permessi DAC (Linux) | Minimo privilegio, GPO, NTFS/RDP, audit dei permessi |
| 05 | **Network Security** | Firewall pfSense, mitigazione DoS (UDP Flood), sicurezza SSH/FTP, analisi traffico Wireshark | Firewall, IDS/IPS, segmentazione, analisi del traffico |

---

## Dettaglio delle aree

### 01 — SIEM & Log Analysis
Monitoraggio e analisi di log di sicurezza con **Splunk** (linguaggio SPL): raccolta ed esplorazione dei log, query di correlazione per rilevare pattern di **brute-force** e produzione di alert. È il cuore del lavoro di un SOC Analyst di primo livello.

### 02 — Threat Intelligence & IOC
Estrazione e classificazione di **Indicatori di Compromissione (IOC)** da una cattura di traffico con Wireshark; attività mappata sul framework **MITRE ATT&CK** (tecnica T1046 — Network Service Discovery) con proposta di contromisure (firewall, IDS/IPS).

### 03 — Malware Analysis
Report di analisi malware: catena loader → infostealer (**Vidar/Lumma**), worm storico (**W32.Nimda**) e un caso di PUP. Analisi statica (hash, stringhe, VirusTotal) e dinamica in **sandbox** isolata, con estrazione degli IOC.

### 04 — Hardening & Access Control
Messa in sicurezza dei sistemi secondo il **principio del minimo privilegio**: gestione dei gruppi utente e dei permessi NTFS/RDP in **Active Directory** (Windows Server 2022) e configurazione/audit dei permessi **DAC** in ambiente Linux.

### 05 — Network Security
Configurazione di un **firewall** (pfSense) con segmentazione WAN/LAN/DMZ, analisi e mitigazione di un attacco **DoS** (UDP Flood) con regole di firewalling e firme IDS, messa in sicurezza dei servizi di rete (**SSH/FTP**) e analisi del traffico con **Wireshark**.

---

*Portfolio pubblicato a scopo professionale ed educativo.*
