In Scratch it's often useful to run code blocks every time a condition becomes true.

You can do this by placing an `if`{:class="block3control"} block inside a `forever`{:class="block3control"} block. You will need to trigger the script, for example with a `when flag clicked`{:class="block3events"} or `when I receieve`{:class="block3events"} block.

You can check for important conditions in a game:

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
