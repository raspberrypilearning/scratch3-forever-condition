W Scratchu często przydatne jest uruchamianie bloków kodu za każdym razem, gdy warunek stanie się prawdziwy.

Możesz to wykonać umieszczając blok warunkowy `jeżeli`{:class="block3control"} wewnątrz bloku pętli `zawsze`{:class="block3control"}. Będziesz musiał uruchomić skrypt, na przykład warunkiem `kiedy kliknięto flagę`{:class="block3events"} lub blokiem `kiedy otrzymam`{:class="block3events"}.

Możesz sprawdzić ważne warunki w grze:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nieeeee!] for [2] seconds
go to (Start v)
end
end
```

Lub sprawdzić używając `wyrażenie`{:class="block3operators"} z wartością `zmiennych`{:class="block3variables"}.

```blocks3
forever
if <(zdrowie) < [5]> then
say [Uwaga! Niskie zdrowie] for [2] seconds
end
end
```
