En Scratch, a menudo es útil ejecutar bloques de código cada vez que se cumple una condición.

Puedes hacer esto colocando un bloque `si`{:class="block3control"} dentro de un bloque `por siempre`{:class="block3control"}. Tendrás que activar el script, por ejemplo, con un bloque `al presionar bandera verde ⚑`{:class="block3events"} o un bloque `al recibir`{:class="block3events"}.

Puedes comprobar si se cumplen condiciones importantes en un juego:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [¡Nooooo!] for [2] seconds
go to (Inicio v)
end
end
```

O comprobar si se cumple con el uso de un `operador`{:class="block3operators"} con un valor para la `variable`{:class="block3variables"}.

```blocks3
forever
if <(salud) < [5]> then
say [¡Advertencia! Baja salud] for [2] seconds
end
end
```

