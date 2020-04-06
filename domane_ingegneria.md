# Domande piu frequenti ingeneria del software 

## considerazioni preliminari

1. cosa si intende per software?
* L’insieme di programmi, procedure, regole e documentazione associata, e i dati (relativi
all’operatività di un sistema di elaborazione).

2. principali aree applicative software?
* Mobile apps
* Web apps
* Information systems (ERP)
* Scientific computing
* Medical devices
* Industrial and process control
* Embedded systems
* Real-time systems
* Big Data
* Defense systems
* System software (OS, DBMS, ...)
* Network software (router, ...)
* Tools (git, ...)

3. proprietà esseziali software?
* Complessità
* Conformità
* Modificabilità
* Invisibilità

4. conseguenza complessità software?
* Le entità software sono considerati tra i costrutti più complessi dell’essere umano perchè ha
componenti tutte differenti. Questo porta anche all’ esplosione combinatoriale degli stati.
La complessità cresce esponenzialmente al crescere della dimensione.
La conseguenza è che un prodotto software è difficile da comprendere e da controllare.  

5. cosa si intende per conformita?
Il software è un prodotto dell’uomo: non esistono leggi naturali unificanti
Il software si deve adattare all’ambiente esterno per via delle molte interfacce hardware,
di più utenti con profili differenti , e dei processi lavorativi predefiniti
La conformità forzata aggiunge maggiore complessità

6. effetto cambiamento continuo software?
C’è sempre pressione per il cambiamento del software tuttavia il cambiamento continuo
degrada la qualità iniziale del software

7. conseguenza invisibilità?
Il software è un’entità invisibile e non può essere catturato completamente da un’unica
rappresentazione geometrica(
* flusso di controllo
* flusso dei dati
* dipendenze delle variabili
* sequenze temporali).
Di conseguenza ci sono problemi di comunicazione.

8. quando e da chi perchè è stato coniato ingegneria dei software?
Durante un convegno NATO nel 1968 in risposta alla “crisi del software” (
* Progetti in ritardo
* Progetti che sfondano i costi preventivati
* Sistemi non all’altezza dell’affidabilità richiesta

9. cosa si intende per ingegneria del software?
* La disciplina tecnologica e manageriale che riguarda la produzione sistematica e la
manutenzione dei prodotti software che vengono sviluppati e modificati entro i costi e i
tempi preventivati, e con qualità accettabile

10. differenza fra costo software e costo hardware?
Il costo del software è un costo di progetto non di produzione, ed è principalmente un costo
di sforzo (umano).

11. come si misura il costo del software e cosa si intende su time to market?
Il costo del software è principalmente un costo di sforzo umano ed è misurato in [ ore |
giorni | mesi | anni ] – persona. Il ‘’time to market’’ è il tempo che intercorre dall’idea
iniziale al rilascio del prodotto (è un fattore critico per molti progetti).

12. cos'è la legge di brooks?
Aggiungere persone a un progetto già in ritardo ha un effetto contrario alle intenzioni:
* Addestramento
* Comunicazione intragruppo n(n-1)/2

13. cosa si intende per qualità del software?
Per misurare la qualità del software ci si affida a un modello di qualità che
prevede la decomposizione del concetto in attributi fino ad arrivare a misure. I
parametri a cui si fa riferimento sono funzionalità, affidabilità, efficienza,
usabilità, manutenibilità, portabilità

14. perchè sono importanti i processi software?
Visto che un processo software descrive quali sono le attività che concorrono a sviluppare
un prodotto software e come le attività sono collegate tra loro, la qualità del software
dipende proprio dalla qualita del processo software.

15. cosa sono i processi software?
che un processo software descrive quali sono le attività che concorrono a sviluppare un
prodotto software e come le attività sono collegate tra loro

16-principali attività tecniche o organizzative?
**Attività tecniche**
* Analisi dei requisiti (requirements analysis)
* Progettazione (design)
* Realizzazione (implementation)
* Collaudo (testing)
* Messa in esercizio (deployment)
* Conduzione operativa (operation)
* Manutenzione (maintenance)
**Attività organizzative**
* Gestione del progetto (project management)
* Gestione della configurazione (configuration management)
* Assicurazione della qualità (quality assurance)

17. cosa caratterizza lo stile di processo a cascata?
* Suddivide il progetto in base alle attività tecniche
* Le fasi coincidono con le attività
* Si passa a una fase successiva solo se si completa l’attività e * si supera il punto di
**controllo –**
*Tornare indietro è possibile ma come eccezione
**Problemi**
* Rischio elevato: difficile stabilire che tutto procede veramente bene
* Difficile da applicare se i requisiti sono poco noti o volatili
* Time to market ritardato

18. cos' è il time boxing?
* In generale prevede di snellire il processo dedicando ad ogni operazione che lo costituisce
degli slot di tempo ben definiti

19. cosa intende per sviluppo pianificato o sviluppo agile?
**Sviluppo pianificato**
* Piano dettagliato delle attività creato a monte
* Molta documentazione come forma di comunicazione indiretta
* Stile di processo a cascata
* Adatto per progetti con requisiti noti a priori e stabili nel tempo
**Sviluppo Agile**
* Fortemente adattivo rispetto ai cambiamenti in corso d’opera
* Poca documentazione: enfasi sulla comunicazione diretta tra persone
* Stile di processo iterativo: iterazioni corte e di durata costante (timeboxed)

20. quali sono i principi del manifesto dello sviluppo agile (sono diversi dai valori)?
* La nostra massima priorità è soddisfare il cliente
rilasciando software di valore, fin da subito
e in maniera continua.
* Accogliamo i cambiamenti nei requisiti,
anche a stadi avanzati dello sviluppo.
I processi agili sfruttano il cambiamento
a favore del vantaggio competitivo del cliente.
* Consegnamo frequentemente software funzionante,
con cadenza variabile da un paio di settimane a un paio di mesi,
preferendo i periodi brevi.
* Committenti e sviluppatori devono lavorare insieme
quotidianamente per tutta la durata del progetto.
* Fondiamo i progetti su individui motivati.
Diamo loro l'ambiente e il supporto di cui hanno bisogno
e confidiamo nella loro capacità di portare il lavoro a termine.
* Una conversazione faccia a faccia
è il modo più efficiente e più efficace per comunicare
con il team ed all'interno del team.
* Il software funzionante è il principale metro di misura di progresso.
* I processi agili promuovono uno sviluppo sostenibile.
Gli sponsor, gli sviluppatori e gli utenti dovrebbero essere in grado
di mantenere indefinitamente un ritmo costante.
* La continua attenzione all'eccellenza tecnica
e alla buona progettazione esaltano l'agilità.
* La semplicità - l'arte di massimizzare la quantità
di lavoro non svolto - è essenziale.
* Le architetture, i requisiti e la progettazione
migliori emergono da team che si auto-organizzano.
* A intervalli regolari il team riflette su come
diventare più efficace, dopodiché regola e adatta
il proprio comportamento di conseguenza

21. metodi agili più noti //DA RIVEDERE?
* Extreme Programming (XP) esprime 12 regole o pratiche per lo
sviluppo software (Pair Programming, Planning Game, Test Driven
Development, Whole Team...)
**Scrum:**
prevede di dividere il progetto in blocchi rapidi di lavoro (Sprint) alla fine di
ciascuno dei quali creare un incremento del software. Esso indica come definire i
dettagli del lavoro da fare nell'immediato futuro e prevede vari meeting con
caratteristiche precise per creare occasioni di ispezione e controllo del lavoro
svolto.
**Kanban:**
Descritto in 5 proprietà:
* Visualizzare il flusso di lavoro
* Limitare il Work-in-Process
* Misurare e gestire il flusso
* Rendere le politiche di processo esplicite
* Utilizzare i modelli per riconoscere le opportunità di miglioramento

22. citare almeno 3 pratiche dell' extreme programming //DA RIVEDERE?
* Pair programming
Due programmatori lavorano da soli su una sola workstation
* Planning Game
Riunione di pianificazione che avviene una volta per iterazione (di solito una volta
a settimana)
* Test Driven development
I test automatici (sia unitari che di accettazione) vengono scritti prima di scrivere
il codice.
* Whole Team
Il cliente non è colui che paga il conto , ma la persona che realmente utilizza il
sistema. Il cliente deve essere presente e disponibile a verificare.

23. cos'è una kanban board?
* è lo strumento utilizzato nella metodologia di sviluppo software Kanban.
Possiede diverse colonne tra cui le principali sono To do, In progress, Review e Done.

24. cos'è il work in progress(WIP)?
* È il numero di attività che su cui un team sta lavorando. Una delle principali proprietà del
Kanban è limitare il WIP.

25. cos’è una valutazione retrospettiva?
* La retrospettiva è un incontro che si tiene alla fine di un’iterazione di sviluppo Agile.
Durante la retrospettiva, il team riflette su quanto accaduto durante l’iterazione appena
trascorsa e individua le azioni per migliorare il futuro. Si individuano:
Cose da tenere
ciò che ha funzionato bene e che si intende ripetere in futuro
Problemi
aree in cui qualcosa non va come dovrebbe
Cose da provare
cambiamenti che potrebbero migliorare il processo

26. cos è un analisi post mortem?
* Le revisioni post mortem si concentrano sull'estrazione di lezioni dal team di sviluppo una
volta che il
il software viene consegnato. Le revisioni post mortem devono essere condotte poco dopo
la fine del
progetto in modo che le informazioni non vengono perdute a causa del progetto successivo

27. cos'è uno sprint?
* È un iterzione durante la quale i progetti scrum fanno progressi. Durante questa fase il
prodotto viene progettato, realizzato e testato.

28. quanto dura uno sprint in scrum?
* La durata tipica è in genere di 2-4 settimane o un
mese di calendario

29. quali sono i vataggi o svantaggi di uno sprint breve o lungo?
* Una durata costante permette una migliore cadenza

30. se è possibile chiedere al team di aggiugere requisiti e perchè?
* Durante uno Sprint non sono accettate richieste di
modifiche ai requisiti

31. quali sono i ruoli principali in scrum?
* Product Owner
* ScrumMaster
* Team

32. cosa fa in product owner?
* È responsabile del valore del prodotto
* Gestisce il product backlog (gestisce le caratterisitche funzionali e
non funzionali del prodotto, assegna le priorità alle feature,adatta le
feature e le priorità a ogni iterazione).
* Accetta o rifiuta i risultati del lavoro del Team di Sviluppo

33. cosa fa il master(o ScrumMaster)?
* È una guida al servizio del Team di Sviluppo e del Product Owner. Aiuta a creare e a
modificare gli elementi del product Backlog, facilita gli eventi scrum e mostra le informazioni
chiave per il processo di sviluppo

34. quante persone possono stare in un team e perchè?
* Un team dovrebbe avere da 3 a 8 persone per la regola delle 2 pizze : per sfamare un team
dovrebbero essere necessarie non più di due pizze.

35. cosa si intende per autogestione in uno sprint?
* Nessuno (neanche lo Scrum Master) dice al Team di Sviluppo come
trasformare il Product Backlog in Incrementi di prodotto potenzialmente rilasciabili

36. cosa si fa in uno sprint planning?
* Valutazione delle priorità nel Product Backlog
* Scelta dello Sprint Goal
* Selezione degli item da completare nello Sprint
* Creazione dello Sprint Backlog(identificazione dei task e stima)

37. cos' è uno sprint backlog?
* Una lista di tutto il lavoro richiesto sul progetto, è l’unica fonte di requisiti per le modifiche
da apportare al prodotto. Le priorità sono stabilite dal Product Owner e le stime degli item
pronti per uno Sprint sono stabilite dal Team di Sviluppo.

38. cosa si fa nei Daily scrum meeting (o semplicemente meeting) quanto dura e perchè si
sta in piedi?
* Nel Daily scrum meeting tutti i componenti devono rispondere alle seguenti domande: Cosa
hai fatto ieri?;
Cosa farai oggi?; Ci sono problemi nella prosecuzione del lavoro?
La sua durata è di 15 minuti e si rimane in piedi per evitare che si prolunghi inutilmente.

39. chi partecipa allo sprint review?
* Allo sprint review partecipano tutto il team ed eventuali esterni sono benvenuti.

40. quando si fanno le stime e chi le fa nello sviluppo agile?
* Le stime degli item sono fatte all’inizio di ogni Sprint dal Team di sviluppo

41. come vengono espressi i requisiti funzionali?
* I requisiti funzionali sono espressi mediante le user stories

42. come viene espressa una user story
* Le user stories sono espresse mediante un Template:
In qualità di <ruolo utente>,
voglio <obiettivo>
[in modo tale da <motivo>]














