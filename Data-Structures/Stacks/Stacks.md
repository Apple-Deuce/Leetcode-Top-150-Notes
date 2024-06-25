# Stacks

## Explanation

- Last in, first out
- Think about a stack of books or a browser's back button
- Array can be used as a stack, alternatively you can create a **Stack** class but is not useful

### Examples

```
var letters = [];
var word = "racecar";
var reverseWord = "";

// Put letters of word into stack
for (var i = 0; i < word.length; i++) {
  letters.push(word[i]);
}

console.log("Stack after pushing letters:", letters);

// Pop off the stack in reverse order
for (var i = 0; i < word.length; i++) {
  reverseWord += letters.pop();
}

console.log("Reversed word:", reverseWord);

if (reverseWord === word) {
  console.log(word + " is a palindrome.");
} else {
  console.log(word + " is not a palindrome.");
}
```


## Functions

- **Push** : Add an element to the top of the stack.
- **Pop** : Removes the last element from the top of the stack.
- **Peek** : Displays the last element in the stack.
- **Length** : Displays the length of elements in the stack.


