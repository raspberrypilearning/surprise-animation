--- question ---

---
legend: Question 2 of 3
---

In your project, you planned the animation with `timer`{:class="block3events"} or `wait`{:class="block3control"} blocks. 

In this dinosaur project, you want the little dinosaur to wait 6 seconds before it pops out of the egg and surprises the big dinosaur. 

![A dinosaur sprite and an egg sprite on the Stage.](images/quiz-q2.png)

Which script for the **little dinosaur** sprite would make this happen?

--- choices ---

- ( ) 
```blocks3
when [loudness v] > (6)
show
```

  --- feedback ---

 These are the right blocks to use, but you need to select `timer`{:class="block3events"} instead of `loudness`{:class="block3events"} in the drop-down menu.

  --- /feedback ---

- ( ) 
```blocks3
when this sprite clicked
show
```

  --- feedback ---

This script needs user interaction for the little dinosaur to show.

  --- /feedback ---

- ( ) 
```blocks3
when flag clicked
show
wait (6) seconds
```

  --- feedback ---

 Here, the little dinosaur surprises the big dinosaur and then waits 6 seconds.

  --- /feedback ---

- (x) 
```blocks3
when [timer v] > (6)
show
```

  --- feedback ---

 When the timer has waited 6 seconds, the little dinosaur appears and surprises the big dinosaur!

  --- /feedback ---

--- /choices ---

--- /question ---
