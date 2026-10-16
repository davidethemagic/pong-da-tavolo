# Pong da tavolo

Pong contro il computer, in un solo file HTML. Il campo è un tavolo da ping pong visto dall'alto: tu giochi a sinistra, il computer a destra.

## Come si gioca

Vince chi arriva a 7 punti con almeno 2 punti di scarto. Dopo ogni punto la pallina riparte dopo meno di un secondo, verso chi ha segnato.

- Mouse o dito: la racchetta segue il puntatore.
- Tastiera: `W` e `S`, oppure le frecce su e giù.
- `Spazio`: pausa e ripresa.
- `M`: audio acceso o spento.

## Livelli

Il menu iniziale ha tre livelli. Quello scelto viene ricordato dal browser.

| Livello | Racchetta del computer | Pallina al servizio |
| --- | --- | --- |
| Facile | lenta, sbaglia spesso | lenta |
| Normale | veloce, sbaglia ogni tanto | media |
| Difficile | molto veloce, quasi mai fuori | veloce |

## Come funziona

- La pallina rimbalza sulla racchetta con un angolo che dipende da dove la colpisci: al centro va dritta, sui bordi parte inclinata.
- A ogni colpo la pallina accelera di circa il 4,5%, fino a un massimo. Dopo sei scambi di fila compare il contatore degli scambi.
- Il computer calcola dove la pallina arriverà sulla sua linea, rimbalzi compresi, e ci aggiunge un errore che dipende dal livello.
- Il movimento della pallina è calcolato a piccoli passi, così a velocità alta non passa attraverso le racchette.
- I suoni sono generati dal browser, non ci sono file audio.

## Provarlo

È un solo file, `index.html`. Scaricalo e aprilo nel browser: non serve installare niente. L'unica cosa che scarica dalla rete sono i caratteri di Google Fonts; se è offline il gioco funziona lo stesso con quelli di sistema.

Funziona su computer e su telefono.

## Licenza

MIT. Puoi usarlo, copiarlo e modificarlo come vuoi.
