# esercizi-deluge

## ES 1:
Realizzare un'automazione con funzione associata per:
- recuperi due numeri A e B, da due campi di un modulo;
- calcoli il resto della divisione A/B;
- il risultato campo "Risultato" deve salvare il messaggio testuale: "Il resto della divisione A/B è: C".

## ES 2:
Dichiarare una lista di 10 numeri. Per ogni elemento della lista verificare che:
L'elemento sia un numero compreso tra 0 e 50:
Se no, stampare messaggio di errore;
L'elemento sia un numero pari:
Se no, stampare messaggio "numero X dispari"
Altrimenti, stampare messaggio "numero X pari"
	
## ES 3:
- Creare un campo "status" all'interno del modulo Azienda e Contatti. Quando in azienda il campo status viene aggiornato in "sospeso" aggiornare il campo omonimo di tutti I contatti associati a quella azienda con il medesimo valore. Il campo "status" è una picklist ['sospeso', 'avviato', 'concluso'] e il valore inserito nei contatti (sospeso) se non è presente sui valori della picklist, cosa succede?
- Creare un modulo "Richieste_Trattative" con un campo valuta "valore" e un lookup collegato alle trattative (modulo Affari). Quando la fase di una trattativa passa a "chiusa vinta" creare un record omonimo all'interno del modulo Progetti e, nella stessa chiamata, popolare il campo "valore" con lo stesso valore della trattativa e collegare la trattativa al record creato.

## ES 4: 
- Creare dei prodotti tramite una invokeUrl dal sito [fakestoreapi](https://fakestoreapi.com/), utilizza una creazione massiva.
- Nel modulo prodotti con almeno 300 records, recuperare una lista ordinata per data modifica dei record dal numero 201 al 250 (search o query COQL).
