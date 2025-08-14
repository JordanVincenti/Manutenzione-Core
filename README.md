# MaintenanceManager

**MaintenanceManager** è un plugin per **Minecraft 1.19.4** che permette di mettere il server in manutenzione, impedendo l’accesso ai giocatori non autorizzati e mostrando messaggi personalizzati. Ideale per aggiornamenti, test o modifiche senza che i player disturbino.

---

## 🛠 Funzionamento
Quando la modalità manutenzione è attiva:

- Solo gli utenti con permesso possono entrare.  
- I nuovi giocatori verranno espulsi con un messaggio di kick personalizzabile.  
- Puoi modificare il messaggio di manutenzione in qualsiasi momento.  
- Puoi gestire la whitelist dei giocatori autorizzati ad entrare.

---

## 💻 Comandi, descrizione e permessi

| Comando | Descrizione | Permesso |
|---------|-------------|----------|
| `/maintenance on` | Attiva la modalità manutenzione. | `maintenancemanager.toggle` |
| `/maintenance off` | Disattiva la modalità manutenzione. | `maintenancemanager.toggle` |
| `/maintenance status` | Mostra se la modalità manutenzione è attiva o disattiva. | `maintenancemanager.status` |
| `/maintenance message <messaggio>` | Cambia il messaggio mostrato ai giocatori durante la manutenzione. | `maintenancemanager.message` |
| `/maintenance whitelist add <giocatore>` | Aggiunge un giocatore alla whitelist di manutenzione. | `maintenancemanager.whitelist.add` |
| `/maintenance whitelist remove <giocatore>` | Rimuove un giocatore dalla whitelist. | `maintenancemanager.whitelist.remove` |
| `/maintenance whitelist list` | Mostra tutti i giocatori autorizzati ad entrare durante la manutenzione. | `maintenancemanager.whitelist.list` |

---

## 🔑 Permessi Riassunti

- `maintenancemanager.toggle` → Attiva o disattiva la manutenzione  
- `maintenancemanager.status` → Visualizza lo stato della manutenzione  
- `maintenancemanager.message` → Cambia il messaggio di manutenzione  
- `maintenancemanager.whitelist.add` → Aggiungi giocatore alla whitelist  
- `maintenancemanager.whitelist.remove` → Rimuovi giocatore dalla whitelist  
- `maintenancemanager.whitelist.list` → Mostra la lista della whitelist  

---

## ⚙ Configurazione
Nel file `config.yml` puoi:

- Personalizzare i messaggi del plugin (attivazione, disattivazione, kick).  
- Impostare i colori con i codici `&` (es. `&a`, `&c`).  
- Gestire la whitelist predefinita.

---

## 📢 Note
- I comandi funzionano solo se hai i permessi corretti.  
- Puoi assegnare i permessi con **LuckPerms** o plugin simili.  
- Se la manutenzione è attiva e non sei in whitelist, verrai espulso anche se sei già connesso.

---

## 💸 Prezzo
- **Plugin base:** 5€  
- **Plugin base + modifiche:** 7€  
- **Plugin completamente modificato:** 10€  

⚠️ **Attenzione:** Le modifiche saranno applicate **solo al plugin richiesto**.  
Non è possibile richiedere modifiche troppo estese (es. trasformare il plugin X in Y) senza pagare una nuova modifica.

---

## ⚕️ Termini di Servizio (TOS)

### Licenza e utilizzo
Il plugin acquistato è concesso in licenza per **uso personale** o sul **proprio server**.  
Non puoi rivendere, condividere o distribuire il plugin senza il permesso scritto.

### Garanzia e supporto
Il plugin è fornito *"così com’è"*, senza garanzie esplicite o implicite.  
Supporto tecnico limitato via [email/forum/discord], compatibilità non garantita con tutte le versioni di Minecraft o altri plugin.

### Aggiornamenti
Gli aggiornamenti sono a discrezione dell’autore e possono essere gratuiti o a pagamento.  
Non sono obbligato a rilasciare aggiornamenti o correzioni.

### Responsabilità
Non sono responsabile per danni diretti o indiretti derivanti dall’uso del plugin, inclusa perdita di dati o malfunzionamenti del server.

### Restituzioni e rimborsi
Non sono previsti rimborsi dopo l’acquisto, salvo casi di plugin non funzionante e verificabile entro **7 giorni** dall’acquisto.

### Modifiche ai termini
Mi riservo il diritto di modificare questi termini in qualsiasi momento.  
L’uso continuato del plugin implica l’accettazione delle nuove condizioni.

---

### Per informazioni TG: @CotoneMoscato
