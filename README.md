# human-code
//Scansione fronte retro
prendo la pratica
accendo lo scanner
accendo il pc
	
verifico la connessione tra scanner e pc
	?  SE la connessione è funzionante 
	:  ALTRIMENTI 
		?  SE supero i 5 tentativi
			*chiamo un tecnico
	
verifico settaggi scanner
	?  SE i settaggi sono corretti
	:  ALTRIMENTI 
		*chiamo un tecnico

sollevo parte superiore stampante

// LOOP 
inserisco il foglio nello scomparto scanner 
chiudo parte superiore stampante
avvio la scansione
attendo il termine della scansione

	?  SE la scansione è corretta
	: ALTRIMENTI 
		*rieseguo la scansione una volta sola

salvo il file
sollevo parte superiore stampante
giro il foglio
chiudo parte superiore stampante
avvio la scansione
attendo il termine della scansione
	
	?  SE la scansione è corretta
	: ALTRIMENTI 
		*rieseguo la scansione una volsta sola

salvo il file
sollevo parte superiore stampante
rimuovo il foglio scansionato
//

FINCHE' non finisco i fogli da scansionare
chiudo parte superiore stampante
spengo la stampante
unifico in un unico pdf
rinomino il pdf finale
archivio il pdf finale
