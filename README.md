# Manutenzione-Core

📌 Descrizione
MaintenanceManager è un plugin per Minecraft 1.19.4 che ti permette di mettere il server in manutenzione, impedendo l’accesso ai giocatori non autorizzati e mostrando messaggi personalizzati.
Perfetto per lavori di aggiornamento, test o modifiche senza che i player disturbino.

🛠 Funzionamento
Quando la manutenzione è attiva:

Solo gli utenti con permesso possono entrare.

I nuovi giocatori vedranno un messaggio di kick personalizzabile.

Puoi cambiare il messaggio di manutenzione in qualsiasi momento.

Puoi vedere e gestire la lista dei giocatori autorizzati.

💻 Comandi

1️⃣ /maintenance on
Attiva la modalità manutenzione.
Permesso: maintenancemanager.toggle

2️⃣ /maintenance off
Disattiva la modalità manutenzione.
Permesso: maintenancemanager.toggle

3️⃣ /maintenance status
Mostra se la modalità manutenzione è attiva o disattiva.
Permesso: maintenancemanager.status

4️⃣ /maintenance message <testo>
Cambia il messaggio mostrato ai giocatori che tentano di entrare durante la manutenzione.
Permesso: maintenancemanager.message

5️⃣ /maintenance whitelist add <giocatore>
Aggiunge un giocatore alla whitelist di manutenzione, così può entrare anche con la modalità attiva.
Permesso: maintenancemanager.whitelist.add

6️⃣ /maintenance whitelist remove <giocatore>
Rimuove un giocatore dalla whitelist di manutenzione.
Permesso: maintenancemanager.whitelist.remove

7️⃣ /maintenance whitelist list
Mostra la lista di tutti i giocatori autorizzati ad entrare durante la manutenzione.
Permesso: maintenancemanager.whitelist.list

🔑 Permessi riassunti
Permesso	Descrizione
maintenancemanager.toggle	Attiva o disattiva la manutenzione
maintenancemanager.status	Visualizza lo stato della manutenzione
maintenancemanager.message	Cambia il messaggio di manutenzione
maintenancemanager.whitelist.add	Aggiungi player alla whitelist
maintenancemanager.whitelist.remove	Rimuovi player dalla whitelist
maintenancemanager.whitelist.list	Mostra la lista whitelist

⚙ Configurazione
Nel file config.yml puoi:

Cambiare i messaggi del plugin (attivazione, disattivazione, kick).

Impostare i colori con i codici & (es. &a, &c, ecc.).

Personalizzare la whitelist predefinita.

📢 Note
I comandi funzionano solo se hai i permessi giusti.

Puoi dare i permessi con LuckPerms o un plugin simile.

Se la manutenzione è attiva e non sei in whitelist, verrai espulso anche se sei già connesso.
