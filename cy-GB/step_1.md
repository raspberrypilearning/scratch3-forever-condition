Yn Scratch, mae'n aml yn syniad da rhedeg blociau cod bob tro mae amod yn gywir.

Galli di wneud hyn drwy roi bloc `os`{:class="block3control"} mewn bloc `am byth`{:class="block3control"}. Bydd angen i ti roi'r sgript ar waith, er enghraifft gyda bloc `pan fydd fflag wedi'i glicio`{:class="block3events"} neu `pan rwy'n derbyn`{:class="block3events"}.

Galli di chwilio am amodau pwysig mewn gêm:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Start v)
end
end
```

Neu brofi drwy ddefnyddio `gweithredwr`{:class="block3variables"} gyda `newidyn`{:class="block3operators"}.

```blocks3
forever
if <(health) < [5]> then
say [Warning! Low health] for [2] seconds
end
end
```
