# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by a factor of three during the worst case
since the algorithm will have to check for a minimum in
the entire list.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by a factor of three since the algorithm is called
for every element in the array.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by a factor of 9 since the number of times the algorithm is called
grows by a factor of three and the number of times the algorithm takes to run
also grows by a factor of three. Thus the growth is quadratic (n^2) because there
are nested for loops present.
[Justify, in about 2 sentences.]
