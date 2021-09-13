# Lists and Keys

## Importance of Keys

Keys are used to uniquely identify elements in a list and it helps react to identify what is added, updated and changed. Apart from that it helps react to efficiently update the DOM.

- Keys must be unique.

![key](https://miro.medium.com/max/1400/1*jXcxoFPC8h7XewhXm9V7Sg.png)

## Basic List Component

We can refactor the previous example into
a component that accepts an array of numbers and outputs a list of elements.

## Keys

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity, The best way to pick a key is to use a string that uniquely identifies a list item among its siblings

## Extracting Components with Keys

Keys only make sense in the context of the surrounding array.
