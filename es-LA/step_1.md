En Scratch, a menudo es útil ejecutar bloques de código cada vez que se cumple una condición.

Puedes hacer esto colocando un bloque `si`{:class="block3control"} dentro de un bloque `por siempre`{:class="block3control"}. Tendrás que activar el script, por ejemplo, con un bloque `al presionar bandera verde ⚑`{:class="block3events"} o un bloque `al recibir`{:class="block3events"}.

Puedes comprobar si se cumplen condiciones importantes en un juego:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Start v)
end
end
```

Or check use an `operator`{:class="block3operators"} with a `variable`{:class="block3variables"} value.

```blocks3
forever
if <(health) < [5]> then
say [Warning! Low health] for [2] seconds
end
end
```
