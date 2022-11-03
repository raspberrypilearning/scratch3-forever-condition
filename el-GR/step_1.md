Στο Scratch είναι συχνά χρήσιμο να εκτελείς μπλοκ κώδικα κάθε φορά που μια συνθήκη γίνεται αληθής.

Για να το κάνεις αυτό τοποθέτησε ένα μπλοκ `εάν`{:class="block3control"} μέσα σε ένα μπλοκ `για πάντα`{:class="block3control"}. Θα χρειαστεί να ενεργοποιήσεις το script, για παράδειγμα με ένα μπλοκ `όταν γίνει κλικ στη σημαία`{:class="block3events"} ή με ένα μπλοκ `όταν λάβω`{:class="block3events"}.

Μπορείς να ελέγξεις για σημαντικές συνθήκες σε ένα παιχνίδι:

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
