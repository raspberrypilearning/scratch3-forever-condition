Dans Scratch, il est souvent utile d'exécuter des blocs de code chaque fois qu'une condition devient vraie.

Tu peux le faire en plaçant un bloc `si`{:class="block3control"} dans un bloc `répéter indéfiniment`{:class="block3control"}. Tu devras déclencher le script, par exemple avec un bloc `quand le drapeau est cliqué`{:class="block3events"} ou un bloc `quand je reçois`{:class="block3events"}.

Tu peux vérifier des conditions importantes dans un jeu :

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Noooon !] for [2] seconds
go to (Départ v)
end
end
```

Ou vérifier l'utilisation d'un `opérateur`{:class="block3operators"} avec une valeur `variable`{:class="block3variables"}.

```blocks3
forever
if <(santé) < [5]> then
say [Attention ! Santé faible] for [2] seconds
end
end
```

