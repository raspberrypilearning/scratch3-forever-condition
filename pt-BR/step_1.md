No Scratch, geralmente é útil executar blocos de código toda vez que uma condição se torna verdadeira.

Você pode fazer isso colocando um `if`{:class="block3control"} dentro de um bloco `sempre`{:class="block3control"}. Você precisará acionar o script, por exemplo, com um `quando a bandeira for clicada`{:class="block3events"} ou bloco `quando eu receber`{:class="block3events"}.

Você pode verificar condições importantes em um jogo:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Start v)
end
end
```

Ou use um `operador`{:class="block3operators"} com um valor `variável`{:class="block3variables"}.

```blocks3
forever
if <(health) < [5]> then
say [Warning! Low health] for [2] seconds
end
end
```
