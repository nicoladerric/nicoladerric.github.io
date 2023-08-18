# La Rivoluzione del Machine Learning

Questo il sommario:

1. TOC
{:toc}

## Le Origini del Machine Learning

Nel 1949, un ricercatore dell'IBM, Arthur Samuel, immaginò e definì un modo per far eseguire ai computer dei compiti, alternativo rispetto alla programmazione tradizionale. In un articolo del 1962, divenuto un classico ("Artificial Intelligence: A Frontier of Automation") [^1] lo stesso autore descrive come la costruzione di programmi atti a svolgere certi compiti, come il riconoscimento di oggetti, risulti estremamente difficile, se non impossibile, per il fatto che occorre spiegare al computer tutti i singoli passaggi del processo fino al dettaglio più minimo ("in the most exasperating detail"). I computer infatti, aggiunge, "as any programmer will tell you, are giant morons, not giant brains".
La "magia" del computer risiede infatti non tanto in quello che fa, ma nella *velocità* e *accuratezza* con cui eseguendo una sequenza di piccoli passi computazionali, è in grado di portare a termine il compito assegnato.
Questa sequenza tuttavia deve essere specificata in anticipo da un programmatore umano, il quale deve fare lo sforzo cognitivo di identificare i passi necessari (l'*algoritmo*) e scrivere un insieme di istruzioni (il *programma*) in qualche linguaggio specifico che la macchina possa "comprendere" ed eseguire per essere in grado di fornire la soluzione del problema a partire dai dati di ingresso.
Si può dire in questo caso che il risultato che il computer produce deriva interamente dai dati di *input* a cui vengono applicate una serie di regole ben definite che trasformano questi dati in altri dati organizzati in modo differente a cui viene dato il nome di *output*.
Dice in sostanza Samuel che in questo uso del computer occorre necessariamente specificare alla macchina esattamente il "come" cioè il modo con cui si ottiene il risultato senza potersi limitare al "cosa" si vuole ottenere, come si farebbe assegnando lo stesso compito ad un essere umano. La macchina è estremamente efficiente e per questo la si usa, ma è essenzialmente stupida, e l'uomo deve istruirla spiegando in modo esplicito come eseguire ogni singolo passo.

---

A differenza di questo tipo di uso, applicabile a problemi per loro natura "addomesticabili" alla logica dei passi espliciti, esistono molti processi il cui sviluppo non sembra seguire questo schema. In questi casi si può comunque pensare di programmare un computer per trovare la soluzione del problema attraverso un procedimento di tipo "euristico" che mette in campo delle strategie di ricerca approssimata della soluzione, utile quando l'uso di un algoritmo non è possibile. 
(da rivedere)

---

Il cambio di *paradigma* di Samuel, che dette origine alla rivoluzione del "machine learning" (termine reso popolare dallo stesso Samuel) consistette nel ribaltare completamente l'approccio alla programmazione tradizionale, perchè invece di comunicare al computer i passi precisi richiesti per la soluzione del problema, Samuel ebbe piuttosto l'idea di *mostrare al computer "esempi" del problema da risolvere* e lasciare che il computer (opportunamente programmato in modo tradizionale) "imparasse" a risolverlo. Questa idea si rivelò rivoluzionaria, tanto che nel 1961 il suo programma per giocare a dama sconfisse il campione dello stato del Connecticut dell'epoca.
Samuel getta così i semi del Machine Learning, la cui pianta è cresciuta fino ad oggi, portando sviluppi poderosi e frutti che oggi possiamo apprezzare nei campi più diversi. Nello stesso articolo sopra menzionato del 1962, nelle sue parole si possono individuare gli elementi e i concetti essenziali dell'apprendimento automatico.

> Suppose we arrange for some **automatic means of testing** the effectiveness of any **current weight assignment** in terms of **actual performance** and provide a **mechanism for altering the weight assignment** so as to **maximize the performance**. We need not go into the details of such a procedure to see that it could be made entirely automatic and to see that a **machine so programmed would learn from its experience**.


- model and weight assigment
- automatic means of testing the effectiveness of any current weight assignments in terms of actual performance
- a mechanism (i.e. another automatic means) for altering the weight assignment so as to maximize the performance



## Note

[^1]: [The Annals of the American Academy of Political and Social Science, Vol. 340, Automation (Mar., 1962), pp. 10-20 (11 pages)](https://www.jstor.org/stable/1033694)


