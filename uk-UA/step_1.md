У Scratch часто буває корисно запускати блоки коду щоразу, коли умова виконується.

Зробити це можна, розмістивши блок `якщо`{:class="block3control"} всередині блоку `завжди`{:class="block3control"}. Тобі потрібно буде запустити скрипт, наприклад, за допомогою блоків `коли прапорець натиснуто`{:class="block3events"} або `коли я отримую`{:class="block3events"}.

Ти можеш перевірити наявність важливих умов у грі:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Ніііі!] for [2] seconds
go to (Старт v)
end
end
```

Або перевірити за допомогою `оператора`{:class="block3variables"} зі значенням величини `змінної`{:class="block3operators"}.

```blocks3
forever
if <(здоров'я) < [5]> then
say [Увага! Низький рівень здоров'я] for [2] seconds
end
end
```
