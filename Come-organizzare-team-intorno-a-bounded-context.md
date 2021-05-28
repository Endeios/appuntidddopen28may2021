# Come organizzare bounded context

- Funzionalita' grosse: cross bounded context
    - feature team, alcuni team piu forti in determinate aree
    - piu' team lavorano su molto bounded context
- front end: 
    - un solo codebase, tutti contribuiscono

- Problemi
    - scalare team
        - come riorganizzare
    - come assegnare il lavoro
    - team con diversa conoscenza sul sistema
        - SOL: **ogni 3 mesi girare i niubbi sullo zoccolo duro**
    - frontend e backend sono molto diversi, difficile avere fullstack
        - non suddividere il front end puo essere un errore, 
        e' uno sforzo ma permette di offloadare le piccole cose 
        dal front end team principale 
        e anche di rilasciare indipendentmente 

- Analisi
    - Il business da vita alla struttura dei team
    - SOL: **suddividere il team per business line (tipo per utente)**
    - [Annamaria]I bounded context dovrebbero essere cross moduli, il front end e'
    parte del bc, non un bounded context in merito suo.
    - Front end monolitico == debito tecnico