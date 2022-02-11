## Έκπληξη

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Τώρα, πρέπει να προσθέσεις μια έκπληξη. Τι θα μπορούσε να συμβεί με το αντικείμενο; 
- Θα μπορούσε να μετατραπεί σε ένα άλλο αντικείμενο; 
- Θα μπορούσε να μετατραπεί σε έναν χαρακτήρα; 
- Θα μπορούσε να εξαφανιστεί και να εμφανίσει ένα άλλο αντικείμενο; 

Εσύ αποφασίζεις!
</div>
<div>

! [Το έργο "Μαγική γάτα" που δείχνει την έκπληξη.] (Images/cat-magic.png)

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Έχεις γράψει μια ιστορία με πλοκή ή μια έκπληξη; Έχεις παρακολουθήσει μια παράσταση ή έχεις διαβάσει ένα βιβλίο με απρόβλεπτο τέλος; Μπορείς να χρησιμοποιείς τις ίδιες μεθόδους όταν δημιουργείς μια ψηφιακή ιστορία ή κινούμενη εικόνα. 
</p>

### Πότε θα συμβεί η έκπληξη;

--- task ---

Επίλεξε το **αντικείμενο**. Πρόσθεσε ένα script για να ξεκινήσει η έκπληξη όταν το επιθυμήσεις.

Θα χρειαστεί να επιλέξεις μια χρονική καθυστέρηση που να λειτουργεί για το έργο σου. Εάν έχεις έναν χαρακτήρα που περνάει πολύ χρόνο ως περίεργος, θα χρειαστεί να επιλέξεις μεγαλύτερη καθυστέρηση.

[[[scratch3-time-delay]]]

--- /task ---

### Τώρα, δημιούργησε την έκπληξη!

--- task ---

Το αντικείμενο θα μπορούσε να `παίξει έναν ήχο`{: class = "block3sound"}, να `αλλάξει ενδυμασία `{: class = "block3looks"}, να `αλλάξει εφέ γραφικών`{: class = "block3looks"} ή να `αλλάξει μέγεθος`{: class = "block3looks"}.

Θα μπορούσες να προσθέσεις μια εκπληκτική ενδυμασία στο αντικείμενο, στη συνέχεια το αντικείμενο θα μπορούσε να `αλλάξει ενδυμασία `{: class = "block3looks"} για να την αποκαλύψει. Για παράδειγμα, μπορείς να κάνεις το **Apple** μετατραπεί σε **Ghost**.

[[[scratch3-add-costumes-to-a-sprite]]]

Θα μπορούσες να κάνεις το αντικείμενο να φαίνεται ότι μετατρέτρεπεται σε ένα διαφορετικό αντικείμενο - για να το κάνεις αυτό, `εξαφάνισε`{: class = «block3looks»} το **αντικείμενο** την ίδια στιγμή που `εμφανίζεις `{: class = «block3looks»} ένα άλλο αντικείμενο.

--- collapse ---
---
title: Εξαφάνιση και εμφάνιση αντικειμένων
---

Το **αντικείμενο**:
```blocks3
when [timer v] > (4) // set the delay
hide
```

Ένα αντικείμενο**έκπληξη**:
```blocks3
when [timer v] > (4) // same delay
show
```

**Υπόδειξη:** Μπορείς επίσης να χρησιμοποιήσεις τα μπλοκ `εμφανίσου`{: class = "block3looks"} και `εξαφανίσου`{: class = "block3looks"} για τα αντικείμενα`όταν γίνει κλικ στην πράσινη σημαία`{: class = "block3events"}.

--- /collapse ---

--- /task ---

--- task ---

**Δοκιμή:** Κάνε κλικ στην πράσινη σημαία. Συμβαίνει η έκπληξη την κατάλληλη στιγμή; Επαναφέρεται η κινούμενη εικόνα σωστά στην αρχική κατάσταση;

--- /task ---

--- task ---

**Εντοπισμός σφαλμάτων:**

Εάν χρειάζεσαι ένα αντικείμενο να βρίσκεται μπροστά ή πίσω από ένα άλλο αντικείμενο, μπορείτε να χρησιμοποιήσεις επίπεδα:

[[[scratch3-positioning-with-layers]]]

Εάν η έκπληξη συμβαίνει σε λάθος στιγμή, μπορείς να το διορθώσεις:

--- collapse ---
---
title: Ο χρονοδιακόπτης των scripts ξεκινάει την έκπληξη σε λάθος στιγμή
---

Βεβαιώσου ότι έχεις διαλέξει την επιλογή `χρονόμετρο`{:class="block3events"} στο μπλοκ `όταν ένταση`{:class="block3events"}:

```blocks3
when [timer v] > [5]
```

Εάν έχεις επιλέξει σωστά το`χρονόμετρο`{: class = "block3events"}, δοκίμασε να προσαρμόσεις το χρονικό διάστημα που θα περιμένει το χρονόμετρο.

--- /collapse ---

--- /task ---

--- save ---