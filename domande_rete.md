# **Domande piu frequenti reti e calcolatori**  

## considerazioni preliminari  

1. E da considerare che al esame lo spazio per le risposte aperte e ridotto quindi le risposte scritte in questo documento sono sintetiche, ad ogni domanda segue la sua corrispondente risposta.  

2. in alcuni casi le risposte sono quasi uguali e questo succede perché la professoressa novielli ha una tendenza a fare la stessa domanda con altre parole che ovviamente avrà la stessa risposta un esempio di questo e la domanda 48 e 53.

3. alcune domande possono sembrare simili ma non lo sono un esempio di questo sono le domande 55 56 57.

4. fare attenzione con alcune domande a trabocchetto un esempio di questo sono le domande 28 29 


---


1. a quale livello dell'architettura di rete appartiene il DNS?  
- il DNS appartiene al livello applicativo (applicazione).
  
2. che algoritmo e usato nel protocollo OSPF?  
- si usa l'algoritmo link state.  

3. che cos'è HTTP e quale tipo di indirizzamento utilizza?  
- HTTP e un protocollo a livello di applicazione, permette il   trasferimento delle informazioni in modo efficace utilizza URL.  

4. che cosa e il attacco DOS e che tipo di disturbo produce alla rete?  
- il DOS (denial of service) e un attacco attivo e produce l'interruzione di un sevizio che risulta indisponibile per i clienti legittimi.  

5. che cosa vuole dire connessione affidabile e quale livello di protocollo TCP/IP la garantisce  
- connessione affidabile vuole dire che i dati non vengono persi, non ci sono errori e si occupa il livello di trasporto.  

6. che interfaccia ha una TCP e cosa si intende per flusso di controllo?  
- TCP e un'interfaccia stream, cioè vengono inviati i byte in continua sequenza e non si ha garanzia che i dati arrivino negli stessi blocchi con cui sono stati inviati (si intende l'ordine) flusso di controllo sta a indicare la capacita del mittente non eccedere la capacita di ricezione del destinatario.  

7. che tipo di query e disponibile ad accettare un root name server?
- il root name server accetta solo query iterativa, il root name server e TLD accettano solo query ricorsive non ha una cache.

8. come si crea una connessione TCP?
- la connessione TCP si crea in 3 passi  
1 il client avvisa il server di volere iniziare la connessione (invia un segmento con SYN=1)  
2 il server conferma l'inizio della connessione  
3 il client risponde alla connessione inviando i dati

9. comporre la response header line di una risposta HTTP che restituisce al browser la risorsa localizzata al seguente URL  http://www.di.uniba.it/~lanubile7teaching.html?  
- i codici di risposta sono  
1xx=la richiesta e stata accolta e in corso di lavorazione  
2xx=la richiesta fu processata correttamente  
3xx=il client deve realizzare altre azione per finire la richiesta  
4xx=c'e un errore per parte del client  
5xx=c'e un errore per parte del server  
la risposta giusta e http/1.1 200 la richiesta e stata accettata ed elaborata.

10. considera i due principali algoritmi di routing (distance vector e link state) quale e l'algoritmo piu efficiente in termini di occupazione di spazio e dal punto di vista computazionale?
- l'algoritmo distance vector e piu efficiente in termini di memoria (costa poca memoria pero e piu lento)  
l'algoritmo link state e piu efficiente in termini computazionali (e piu veloce ma costa piu memoria)

11. controllo di flusso e finestra scorrevole?
- e un algoritmo che si occupa dell'inoltro affidabile dei dati, la ampiezza della finestra viene impostata in base a vari fattori.  
la finestra indica il numero di byte che il destinatario e disposto a ricevere e scorrevole perché non e fisso e viene spostata man mano che i byte vengono ricevuti e confermati.

12. cosa e il firewall?
- il firewall e un dispositivo per la sicurezza della rete, si occupa di gestire il traffico interno e esterno i pacchetti che possono passare e quelli che no, quelli che non hanno la autorizzazione vengono bloccati/eliminati.

13. cosa e un firewall e cosa si intende per livello di sicurezza?
- il firewall e un dispositivo hardware o software che divide la rete in 2 livelli di sicurezza interno e esterno.  
nel livello interno c'e una maggiore fiducia, nel livello esterno minore fiducia, il firewall si occupa di gestire il traffico interno e esterno i pacchetti che possono passare e quelli che no, quelli che non hanno la autorizzazione vengono eliminati.

14. cosa si intende nel DNS per server di competenza (authoritative name server)?
- e il server che conosce tutti i nomi di quel dominio e i sotto domini e la radice accetta query di tipo ricorsivo.

15. cosa si intende per congestione di una rete e come si manifesta in una rete a commutazione a pacchetto?
- un traffico eccessivo puo causare la perdita di messaggi e il collasso della rete dovuto alla congestione il TCP interpreta la perdita di messaggi e previene il collasso ritarda la trasmissione dei messaggi e la raddoppia fino a che si e raggiunta la meta dell'advertising window e non ci sono altre perdite.

16. cosa si intende per instradamento in internet e quale livello della pila di protocolli gestisce l'instradamento nelle reti di commutazione a pacchetto?
- l'instradamento si occupa di come inoltrare i messaggi verso la destinazione basandosi sull'indirizzo. se ne occupa al livello rete.

17. cosa si intende per ISP di primo livello e quali funzionalità offre?
- hanno una copertura internazionale, comunicano tra loro come pari e sono connessi agli ISP di secondo livello.

18. cosa si intende per ritardo di accodamento?
- somma di attesa per ogni coda.

19. cosa si intende per ritardo di propagazione?
- si intende la distanza/velocità del segnale sul mezzo trasmissivo.

20. cosa si intende per ritardo di trasmissione?
- dimensione messaggio/rendimento.

21. descrivere brevemente le caratteristiche della strategia di multiplazione FDM?
- la frequenza viene suddivisa tra le connessione, quindi ogni connessione ha una frequenza per tutta la durata della connessione.

22. descrivere brevemente le caratteristiche della strategia di multiplazione TDM (time-division multiplexing)?
- il tempo viene suddiviso in frame di durata fissa, ogni frame e diviso in un numero fisso di porzioni temporali, quando si stabilisce una connessione viene dedicato una porzione di tempo in ogni frame, le porzioni sono dedicate esclusivamente a quella connessione (tipica tecnologia di rete telefonica).

23. descrivere la finestra scorrevole?
- e un algoritmo che si occupa dell'inoltro affidabile dei dati, la ampiezza della finestra viene impostata in base a vari fattori.  
la finestra indica il numero di byte che il destinatario e disposto a ricevere e scorrevole perché non e fisso e viene spostata man mano che i byte vengono ricevuti e confermati.

24. differenza tra ping e tracert?
- il ping calcola il tempo di andata e ritorno impiegato da un messaggio rispetto ad una destinazione finale mentre traceroute (tracert) calcola il tempo di andata e ritorno per ogni nodo impiegato da un messaggio rispetto ad una destinazione finale.

25. differenza tra routing statico e routing dinamico?
 - nel routing statico il camino viene calcolato in anticipo e memorizzato, cambia solo con interventi umani mentre nel routing dinamico il camino viene calcolato in base al traffico e in base al tipo di rete.

 26. differenza tra routing statico e routing dinamico?
- nel routing statico il camino viene calcolato in anticipo e memorizzato, cambia solo con interventi umani mentre nel routing dinamico il camino viene calcolato in base al traffico e in base al tipo di rete.

28. esiste un numero di porta di default di un browser?
- no, non esiste un numero di porta per un browser in modo esclusivo.

29. esiste un numero di porta di default per un web browser?
- si esiste ed e il porto 80 per http

30. esiste un numero di porta di default per un web server?
- si, e il porto 80 e per http daemon

31. esiste un numero di porta di default per un web client?
- si, e il porto 80 e per http daemon

32. hand shaeking e TCP?
- il hand shaeking (di solito quella a 3 passi) viene effettuato per essere una connessione affidabile, cioè per fare in modo che i dati della vecchia connessione non vengano scambiati con quelli della nuova connessione si fa con SYN=1.

33. il link state e un algoritmo...?
- globale e dinamico.

34. il link state routing e un algoritmo...?
- dinamico e globale
implementato dal protocollo OSPF

35. in che cosa differisce http 1.1 de http 1.0?
- pipeline delle richieste  
http 1.1 puo avere piu di una richiesta/risposta nella stesa connessione  
http 1.0 deve aprire una connessione pero ogni richiesta e poi chiuderla e questo e inefficiente

36. in cosa consiste un attacco DDOS e quale proprietà della sicurezza compromette?
- nel DDOS (distributed denial of service) l'attaccante ottiene l'accesso su numerosi host in rete istallando un programma su ogni uno dei host compromessi lanciando un attacco DOS in modo distribuito (per ogni host compromesso) a un host target e compromettono la proprietà di disponibilità di un servizio

37. in un descrittore di risorse di un DNS server quale tipo di entrata contiene come valore l'indirizzo IP corrispondente al nome del alias del nome?
- CNAME nome canonico del host.

38. in un descrittore di risorse di un DNS server quale tipo di entrata contiene come valore l'indirizzo IP corrispondente al nome simbolico?
- A indirizzo IP.

39. integrità definizione?
- la integrità e una proprietà della sicurezza. l'integrità significa che un messaggio deve essere ricevuto senza perdite ni modifiche.

40. interfaccia + flusso di controllo?
- la interfaccia che viene utilizzata nel tcp e stream, il flusso di controllo sta a indicare la capacita del mittente di non eccedere la capacita di ricezione del destinatario.

41. le reti di calcolatori che mettono a disposizione solo il servizio con connessione sono chiamate?
- rete a circuito virtuale.

42. le reti di calcolatori che mettono a disposizione solo il servizio senza connessione sono chiamate?
- reti a datagramma.

43. OSPF?
- protocollo che implementa l'algoritmo di routing di link state.

44. qual'è la relazione tra un datagramma IP e un frame ethernet?
- il datagramma IP puo essere incapsulato in un frame ethernet.

45. qual'è la relazione tra un pacchetto HTTP e un segmento TCP?  
- il pacchetto HTTP puo essere incapsulato in segmento TCP.

46. qual'è la relazione tra un segmento TCP e un datagramma IP?
-il segmento TCP puo essere incapsulato in un datagramma IP.

47. quale algoritmo e i migliore tra i 2 algoritmi di routing?
- i due algoritmi sono il distance vector e link state tra cui il link state e il migliore (converge piu velocemente).

48. quale algoritmo e implementato dal protocollo RIP?
- il protocollo RIP implementa l'algoritmo distance vector.

49. quale algoritmo e implementato dal protocollo OSPF?
-implementa l'algoritmo link state.

50. quale livello dell'architettura di rete si occupa dei collegamenti diretti tra host? quale indirizzamento utilizza?
- usa il livello fisico e il messaggio binario.

51. quale livello dell'architettura di rete si occupa delle connessioni indirette tra i nodi di una rete (inclusi host e apparati di rete)? quale tipo di indirizzamento utilizza?
- utilizza il livello di rete e l'indirizzo IP.

52. quale organizzazione gestisce i Request for Comments (RFC)?
- Internet Engineering Task Force, e l'ente che regola gli standard in internet conosciuti come RFC.

53. quale protocollo di routing e implementato dal protocollo RIP?
- distance vector.

54. quali e quanti tipi di query DNS conosci? che tipo di query DNS lancia un resolver al name server locale e perché?
- esistono query ricorsive e iterative  
il name resolver lancia solo query ricorsive perché puo fare richieste solo al name server locale  
il server ROOT e TDL non accettano query ricorsive (perché non hanno cache) solo i server di tipo ricorsivo hanno una cache DNS.

55. quali sono i protocolli internet che corrispondono alle intestazioni che incapsulano l'invio di un messaggio tramite posta elettronica rispondere ordinatamente  
CSMA/CD -xxxxx- -xxxxx- -xxxxx- indirizzo IP
- CSMA/CD---IP---TCP---SMTP---indirizzo IP

56. quali sono i protocolli internet che corrispondono alle intestazioni che incapsulano la risoluzione di un nome mentre si naviga in rete rispondere ordinatamente
CSMA/CD---xxxxx---xxxxx---xxxxx---indirizzo IP
- CSMA/CD---IP---TCP---DNS---nome, indirizzo IP

57. quali sono i protocolli internet che corrispondono alle intestazioni che incapsulano un documento web scaricato metre si naviga in rete rispondere ordinatamente
CSMA/CD---xxxxx---xxxxx---xxxxx---doc.html
- CSMA/CD---IP---TCP---HTTP---doc.html

58. quali sono i tipi di indirizzamento associati a ciascun livello della pila di protocolli TCP/IP?
- data link = indirizzo MAC
- livello di trasporto = Nro porta
- livello rete = indirizzo IP
- livello di applicazione = URI (localizzatore uniforme di risorse)

59. riservatezza definizione?
- Solo mittente e destinatario devono comprendere il contenuto del messaggio.

60. ritrasmissione adattativa che cosa e?
- ritrasmissione adattativa si occupa del invio dei dati nel protocollo TCP basato quindi sulla connessione.  
si occupa della gestione del flusso per non mandare in over flow il buffer del ricevente.  
si basa sul RTT quindi se un pacchetto viene perso questo viene rinviato dopo un corto periodo di tempo.

61. routing statico e routing dinamico le differenze?
- nel routing statico il camino viene calcolato in anticipo e memorizzato, cambia solo con interventi umani
- nel routing dinamico il camino viene calcolato in base al traffico e in base al tipo di rete

62. tenendo conto dele caratteristiche dei due algoritmi di rooting quale il piu efficiente in termini di occupazione di spazio di memoria?
- il distance vector routing e piu efficiente in termini di memoria.

63. vettore distanza e globale o dinamico?
- il vettore distanza (distance vector) e decentralizzato e dinamico.