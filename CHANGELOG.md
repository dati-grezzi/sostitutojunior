# SOStituto junior — registro delle versioni

Formato versione: `GG.MM.AAAA` + lettera + numero progressivo delle consegne (`n. 1`…).

### 26.10.2026j — n. 10
- **Compresenza = potenziamento**: nell'importazione, in ogni cella dell'orario delle classi il primo nome resta il docente della classe e gli altri (la compresenza) diventano ore di potenziamento assegnate a quella classe. Prima erano potenziamento tutte le ore di ogni docente. La spunta «non è potenziamento» esclude il docente da questa regola. Mostrato il totale delle ore di potenziamento e, per ogni docente, quante sono in compresenza.

### 26.10.2026i — n. 9
- **Potenziamento di default**: nell'importazione ogni docente dell'orario delle classi è potenziamento. Il menu dei ruoli è sostituito da una spunta «non è potenziamento» (per chi resta curricolare nella sua classe). Accanto a ogni nome: ore, classi e ore in cui è da solo/a in classe, per decidere.
- **Importazione dell'orario del sostegno** (riquadro 2): si caricano uno o due PDF (SMA e/o S. Marone); il plesso si riconosce dall'intestazione e vale il PDF del gruppo scelto. I docenti del PDF del sostegno diventano «Sostegno» e restano nelle loro classi; chi compare in entrambi i PDF unisce le ore (quelle dell'orario delle classi seguono la regola del potenziamento).
- Lettore PDF: etichette orarie con punto o spazio («10.05-11.05», «13:05- 14:05»), note attaccate al nome («Rossi Anna entra 11.15»), «entra/esce alle hh.mm», **«Attività organizzative»** (con eventuale intervallo) come nota della cella, nomi con solo il cognome riuniti al nome completo (spunta per annullare).
- Avvisi: classi del sostegno assenti nell'orario delle classi o con la prima ora diversa.

### 26.10.2026h — n. 8
- **Uscita con sola delegazione** (come in SOStituto 26.10.2026a): spunta nel modulo delle uscite. La classe non è fuori sede, l'accompagnatore si sostituisce anche nelle ore in quella classe e i docenti della classe non vengono spostati altrove.

### 26.10.2026g — n. 7
- I docenti col ruolo «Potenziamento» diventano ore «a disposizione» come nella secondaria: compaiono in Altro → Potenziamento, con la classe indicata dal PDF già assegnata a ogni ora. Coprono la classe se il titolare è assente e sono i primi candidati per le altre sostituzioni.

### 26.10.2026f — n. 6
- Intestazione e prospetto stampato: «Scuola primaria» al posto di «Mestica».

### 26.10.2026e — n. 5
- **Importazione dal PDF dell'orario della primaria** (una tabella per classe): il lettore ricostruisce righe e colonne dalle coordinate del testo; la libreria pdf.js si scarica solo alla prima importazione. Sostituisce l'import da Excel.
- Ad ogni importazione si sceglie il gruppo (SM o SMA); le classi senza sigla nel PDF (es. «1A») si includono con una spunta, proposta nel gruppo in cui quella classe manca.
- Nomi scritti in modo diverso (abbreviati o tagliati nel PDF) proposti come un'unica persona, con spunta per annullare.
- Schermata dei ruoli (curricolare / sostegno / potenziamento) subito dopo la lettura, con un suggerimento dedotto da come il docente compare in orario.
- «Da nominare» diventa un docente segnaposto per classe («Da nominare 2B»): non viene mai proposto come sostituto e non conta come presente.
- **Compresenze**: se uno dei docenti di una cella è assente e un altro (non sostegno) è in classe, la classe è coperta e non serve sostituzione; se sono assenti entrambi, basta un sostituto.
- «Entra hh.mm» / «Esce hh.mm» del PDF restano nella cella; se il docente è assente, il prospetto (schermo, stampa, WhatsApp) ricorda l'intervallo da coprire.

### 26.10.2026d — n. 4
- Passaggio dati fra i dispositivi dello stesso referente (pc, tablet, telefono): in Altro → Backup, «Crea il link di trasferimento», lo si manda a sé stessi e lo si apre sull'altro dispositivo (conferma prima di importare, istantanea di sicurezza automatica). Si può anche incollare il link. Nessun server: i dati stanno nel link (parte «#»), compressi (~9 KB per un orario completo).

### 26.10.2026c — n. 3
- Tolta la condivisione con il foglio Google (Scarica/Invia, controllo del foglio, script): un solo referente, nessun foglio da associare. I dati restano nel browser; per spostarli o salvarli c'è il backup.

### 26.10.2026b — n. 2
- Snellimento: tolti il collegamento al foglio viaggi (lettura automatica, anteprima, previsioni, modulo FS), la schermata di configurazione dei criteri e le schede per la seconda lingua. Restano le uscite inserite a mano, i recuperi e il flag sostegno.
- La gerarchia dei criteri è quella fissa della circolare (a–h), tutti attivi.
- Il codice delle seconde lingue dentro il motore non è ancora rimosso (inattivo).

### 26.10.2026a — n. 1
- Punto di partenza: copia di SOStituto 16.10.2026d (n. 90 della serie secondaria), con nome e titolo «SOStituto junior». Nessuna funzione ancora rimossa.
