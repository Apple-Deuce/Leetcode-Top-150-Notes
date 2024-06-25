# Sets

## Explanation

- Like an array, but no duplicate items
- Values are in no particular order
- Typical use is to check for presence of an item
- ES6 has a built in Set object, but it doesn't contain all common Set methods
- May need to implement additional needed methods

### Examples

Examples of usage are found in Sets.js


## Functions

- **Values** : Returns elements in the set. In ES6, values will return an iterator.
- **Add** : Adds unique elements to the set while (ignores duplicate values). Does not return true or false, when console logged, it returns the full set after operations.
- **Remove** : Removes elements from the set (This is used as **Delete** in ES6).
- **Size** : Displays the length of elements in the stack (in ES6, size is a prop instead of a method, so no parens should be added when calling it. e.g. mySet.size instead of mySet.size()).

### Additional Methods not in ES6

- **Union** : Combines two sets while removing duplicates (Call the method on the first set while passing in the second set. e.g. this.union = function(secondSet)).
- **Intersection** : Returns common values from two sets as a new set.
- **Difference** : Returns new set with values found in the first set, but not the second.
- **Subset** : Tests if first set is contained in the second set. Returns true or false.



