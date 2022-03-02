Στο Scratch είναι συχνά χρήσιμο να εκτελείς μπλοκ κώδικα κάθε φορά που μια συνθήκη γίνεται αληθής.

Για να το κάνεις αυτό τοποθέτησε ένα μπλοκ `εάν`{:class="block3control"} μέσα σε ένα μπλοκ `για πάντα`{:class="block3control"}. Θα χρειαστεί να ενεργοποιήσεις το script, για παράδειγμα με ένα μπλοκ `όταν γίνει κλικ στη σημαία`{:class="block3events"} ή με ένα μπλοκ `όταν λάβω`{:class="block3events"}.

Μπορείς να ελέγξεις για σημαντικές συνθήκες σε ένα παιχνίδι:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Όχιιιι!] for [2] seconds
go to (Έναρξη v)
end
end
```

Εναλλακτικά, χρησιμοποίησε έναν `τελεστή`{:class="block3variables"} με μια τιμή `μεταβλητής`{:class="block3operators"}.

```blocks3
forever
if <(υγεία) < [5]> then
say [Προειδοποίηση! Χαμηλή υγεία] for [2] seconds
end
end
```

