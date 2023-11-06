Scrivere un programma che chieda all’utente:

1. Con un prompt chiediamo all'utente il numero di chilometri da percorrere, il valore comunicato dall'utente dovra essere trasformato in un numero con parseint e salveremo il valore in una varibile chiamata kmUtente.

2. Con un'altro prompt chiediamo l'età del passeggero il valore comunicato dall'utente dovra essere trasformato in un numero con parseint e salveremo il valore il una variabile che chiameremo etaUtente.

Sulla base di queste informazioni dovrà calcolare il prezzo totale del biglietto di viaggio, secondo le seguenti regole:

3.  Il prezzo del biglietto è definito in base ai km (0.21 € al km),
    quindi dichiariamo una variabile prezzoBiglietto che avra come valore la moltiplicazione dei numeri ossia i chilometri che l'utente deve percorrere conservati nella variabile kmUtente e il prezzo del biglietto a kilometro che dichiariando una variabile prezzo e definendo il suo valore come 0.21.

4.  Va applicato uno sconto del 20% per i minorenni,
    quindi se l'età dell'utente è minore di 18 il alla variabile prezzoBiglietto dovra essere sottratto il 20% del suo valore.
    il valore del 20% sarà definito in una varibile che chiamiamo scontoUnder18.

5.  Va applicato uno sconto del 40% per gli over 65.
    quindi se l'età dell'utente è maggiore o uguale a 65, alla variabile prezzoBiglietto dovra essere sottratto il 40% del suo valore.
    il valore del 40% sarà definito in una varibile che chiamiamo scontoOver65.

6.  In fine stampere in console il valore della variabile prezzoBiglietto mostrando al massimo due cifre dopo la virgolain modo tale da rappresentare i centesimi.
