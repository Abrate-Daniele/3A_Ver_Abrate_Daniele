# Verifica di TPSIT sugli array e oggetti 
# Impiccato
L'obiettivo del sito web è quello di gestire il gioco dell'impiccato.

# ISTRUZIONI
1. Dividere le parole nei livelli (si veda il vettore associativo livelli) in base al numero delle lettere:
    - se una parola ha più di 12 lettere o degli spazi dovrà essere usata per il livello difficile
    - se una parola ha meno di 6 lettere dovrà essere usata per il livello facile
    - negli altri casi le parole saranno inserite nel livello medio
      
2. Caricare dinamicamente la sezione "secLettere" con tutte le lettere dell'alfabeto contenute nell'array alfabeto utilizzando i tag come negli inserimenti di insempio (nota. togliere gli inserimento di esempio)

3. Quando clicco sul bottone Facile, Medio o Difficile devo controllare quanto segue:
    - Se si è cliccato Medio senza aver fatto almeno una "partita" con livello Facile segnalare un errore
    - Se si è cliccato Difficile senza aver fatto almeno una "partita" con livello Medio segnalare un errore

4. Quando si clicca su uno dei bottoni di livello e non ci sono errori, prelevare casualmente una parola dall'array del livello corretto caricato al punto 1

5. Prelevata una parola, caricare dinammicamente i trattini (come da esempio) in base alla parola estratta  

6. Finito il caricamento abilito i pulsanti relativi alle lettere, quando si vuole indicare una lettera è necessario cliccare sul trattino che ci interessa sostituire e poi sulla lettera che vogliamo suggerire:
    - in caso di errore aggiornare l'immagine nell'intestazione
    - in caso di lettera corretta mostrare la lettera al posto del trattino

7. Nel momento in cui tutti i trattini sono stati sostituiti allora si comunica la vincita.

8. PER VOTI >= 8 è necessario tenere conto degli spazi nel punto 6.

9. PER IL 10. L'estrazione non deve permettere l'estrazione delle stesse parole.

# Per chi ha diritto al tempo aggiuntivo
E' esonerato dalla gestione del punto 2 (inserire le lettere mancanti facendo copia-incolla dei tag nell'html modificando la lettera interna al tag e aggiungere gli eventi necessari nell'html manualmente), 3, 7 e 10.