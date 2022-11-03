У Scratch часто буває корисно запускати блоки коду щоразу, коли умова виконується.

Зробити це можна, розмістивши блок `якщо`{:class="block3control"} всередині блоку `завжди`{:class="block3control"}. Тобі потрібно буде запустити скрипт, наприклад, за допомогою блоків `коли прапорець натиснуто`{:class="block3events"} або `коли я отримую`{:class="block3events"}.

Ти можеш перевірити наявність важливих умов у грі:

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
