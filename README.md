# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?

The first object created within main is the List of dogs in which future dogs can be added to by using the
.add method. The next three objects created are the dogs added to the list: Fido with 4 legs, Fido with 3 legs,
and Alfie with 4 legs. Each of those dogs is now in the ArrayList of dogs. The last object created is using the
new Comparator<Dog> within the Colelctions.sort call.


3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?

The Comparator class definition is found within the import statement of Comparator. The Comparator class is imported
using the java.util.Comparator statement in the beginning. The constructor call can be found within the
Collections.sort call, since we are using the new keyword to create a comparator for type <Animal>.
