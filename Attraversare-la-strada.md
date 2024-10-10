## 10. ATTRAVERSARE LA STRADA

Semafori, rotonde e precedenze… al test per la patente, la domanda sugli incroci manda sempre un po’ in confusione! Per stavolta ci concentriamo solamente sugli step da fare per attraversare la strada, sapendo che ogni passo deve essere ben misurato altrimenti potrebbe costarci caro!

## SVOLGIMENTO

// per semplicità sto immaginando una strada a due corsie senza incroci o altro, con tanti attraversamenti pedonali

- ho una strada
- ho una lista di posizioni di strisce pedonali
- ho la mia posizione

- FINCHE' la mia posizione NON è uguale alla posizione di un elemento nella lista delle strisce pedonali

  - SE NON avvisto nei dintorni della mia posizione delle strisce pedonali
    faccio 10 metri avanti
  - ALTRIMENTI
    mi posiziono sopra le strisce avvistate

- FINCHE' NON ho attraversato la strada
  - SE nella strada NON ci sono macchine a destra AND nella strada NON ci sono macchine a sinistra
    attraverso la strada
  - ALTRIMENTI
    attendo che le macchine passino
