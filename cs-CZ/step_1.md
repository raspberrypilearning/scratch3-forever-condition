Ve Scratchi je často užitečné spouštět bloky kódu pokaždé, když se podmínka stane pravdivou.

Můžete to udělat umístěním bloku `když`{:class="block3control"} do bloku `opakuj pořád`{:class="block3control"}. Budeš muset spustit skript, například `při kliknutí na vlajku`{:class="block3events"} nebo `když obdržím`{:class="block3events"} blok.

Můžete kontrolovat důležité podmínky ve hře:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Neeeee!] for [2] seconds
go to (Start v)
end
end
```

Nebo použít `operátor`{:class="block3variables"} s `Proměnnou`{:class="block3variables"}.

```blocks3
forever
if <(zdraví) < [5]> then
say [Varování! Nízké zdraví] for [2] seconds
end
end
```
