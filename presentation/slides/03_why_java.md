### Why immutability (Java) ?

<p style="text-align: left;">https://docs.oracle.com/javase/tutorial/essential/concurrency/immutable.html</p>
>Maximum reliance on immutable objects is widely accepted as a sound strategy for creating simple, reliable code.<!-- .element: style="text-align: left; margin-top: 0; font-size: 30px;" -->

>Immutable objects are particularly useful in concurrent applications.  
>Since they cannot change state, they cannot be corrupted by thread interference or observed in an inconsistent state.<!-- .element: style="text-align: justify; margin-top: 0; font-size: 30px;" -->

>Programmers are often reluctant to employ immutable objects, because they worry about the cost of creating a new object as opposed to updating an object in place.  
>The impact of object creation is often overestimated, and can be offset by some of the efficiencies associated with immutable objects.  
>These include decreased overhead due to garbage collection, and the elimination of code needed to protect mutable objects from corruption.<!-- .element: style="text-align: justify; margin-top: 0; font-size: 30px;" -->
