In Scratch is het vaak handig om codeblokken uit te voeren telkens wanneer een voorwaarde waar wordt.

Je kunt dit doen door een `als`{:class="block3control"}-blok in een `herhaal`{:class="block3control"}-blok te plaatsen. Je moet het script activeren, bijvoorbeeld met een `wanneer op de vlag wordt geklikt`{:class="block3events"} of `wanneer ik signaal ontvang`{:class="block3events"}-blok.

Je kunt controleren op belangrijke voorwaarden in een spel:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Start v)
end
end
```

Of gebruik een `functie`{:class="block3variables"} met de waarde van een `variabele`{:class="block3operators"}.

```blocks3
forever
if <(health) < [5]> then
say [Warning! Low health] for [2] seconds
end
end
```
