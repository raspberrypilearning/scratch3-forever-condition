In Scratch, spesso è utile eseguire blocchi di codice ogni volta che una condizione diventa vera.

Puoi farlo inserendo un blocco `se`{:class="block3control"} all'interno di un blocco `per sempre`{:class="block3control"}. Dovrai attivare lo script, ad esempio con un blocco `quando si clicca su ⚑`{:class="block3events"} o `quando ricevo`{:class="block3events"}.

Puoi verificare le condizioni importanti in un gioco:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Avvia v)
end
end
```

Oppure controllare utilizzando un `operatore`{:class="block3operators"} con un valore di `variabile`{:class="block3variables"}.

```blocks3
forever
if <(salute) < [5]> then
say [Attenzione! Salute bassa] for [2] seconds
end
end
```
