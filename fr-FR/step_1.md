Dans Scratch, il est souvent utile d'exécuter des blocs de code chaque fois qu'une condition devient vraie.

Tu peux le faire en plaçant un bloc `si`{:class="block3control"} dans un bloc `répéter indéfiniment`{:class="block3control"}. Tu devras déclencher le script, par exemple avec un bloc `quand le drapeau est cliqué`{:class="block3events"} ou un bloc `quand je reçois`{:class="block3events"}.

Tu peux vérifier des conditions importantes dans un jeu :

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Start v)
end
end
```

Ou vérifier l'utilisation d'un `opérateur`{:class="block3variables"} avec une valeur `variable`{:class="block3operators"}.

```blocks3
forever
if <(health) < [5]> then
say [Warning! Low health] for [2] seconds
end
end
```
