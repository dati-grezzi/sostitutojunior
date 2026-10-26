# SOStituto junior — registro delle versioni

Formato versione: `GG.MM.AAAA` + lettera + numero progressivo delle consegne (`n. 1`…).

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
