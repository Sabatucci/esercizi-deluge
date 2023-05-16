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
- Creare un campo "status" all'interno del modulo Azienda e Contatti. Quando in azienda il campo status viene aggiornato in "sospeso" aggiornare il campo omonimo di tutti I contatti associati a quella azienda con il medesimo valore. Il campo è una picklist e il valore inserito nei contatti (sospeso) non è presente sui valori della picklist. Cosa succede?
- Creare un modulo "Progetti" con un campo valuta "valore". Quando la fase di una trattativa passa a "chiusa vinta" creare un record omonimo all'interno del modulo Progetti e, nella stessa chiamata, popolare il campo "valore" con lo stesso valore della trattativa.

## ES 4: 
- Creare dei prodotti tramite una invokeUrl dal sito [https://jsonplaceholder.typicode.com/](https://fakestoreapi.com/)
- In un modulo con più di 300 records (se non presenti crearli in modalita bulk) e recuperare una lista ordinata per data modifica dei record dal 201 al 250.
