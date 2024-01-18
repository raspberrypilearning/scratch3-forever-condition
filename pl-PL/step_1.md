W Scratchu często przydatne jest uruchamianie bloków kodu za każdym razem, gdy warunek stanie się prawdziwy.

Możesz to wykonać umieszczając blok warunkowy `if` wewnątrz bloku pętli `forever`{:class="block3control"}. Będziesz musiał uruchomić skrypt, na przykład warunkiem `po kliknięciu flagi`{:class="block3events"} lub blokiem `gdy otrzymam`{:class="block3events"}.

Możesz sprawdzić ważne warunki w grze:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Start v)
end
end
```

Lub sprawdzić używając `operatora`{:class="block3operators"} z wartością `zmiennych`{:class="block3variables"}.

```blocks3
forever
if <(health) < [5]> then
say [Warning! Low health] for [2] seconds
end
end
```
