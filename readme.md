Data Types:
Methods of primitives
java sript allows us to work with primitives string.numbers etc.
there are 7 primitives types : String,numbers,booleans.null,undifined,symbols,bigint.
An Object:- is a capable of storing multiple values as properties.
Can be create with Objects{name: "Rahul", age:28}.there are other kinds of object in javascript.

Array methods:-
array provide a lot of methods.
arr.push(.items) – adds items to the end,
arr.pop()- remove item from the end.
arr.shift() – remove an item from the beginning,
arr.unshift()- ad item to the beginning. 

Number

The number type represent both integer and floating point numbers.

`1 let a = 123
a = 234.5;`
An object

    Is capable of storing multiple values as properties.
    Can be created with {}, for instance:

    "{name: "John", age: 30}"
    
     There are other kinds of objects in JavaScript: functions, for example, are objects.
     Numbers:-
     There are two types Number- "regular number, biglnt number".
     Regular numbers in javascript store in 64-bit format.
     BigInt numbers, to represent integers of arbitrary length.  



    To add/remove elements:
        push(...items) – adds items to the end,
        pop() – extracts an item from the end,
        shift() – extracts an item from the beginning,
        unshift(...items) – adds items to the beginning.
        splice(pos, deleteCount, ...items) – at index pos deletes deleteCount elements and inserts items.
        slice(start, end) – creates a new array, copies elements from index start till end (not inclusive) into it.
        concat(...items) – returns a new array: copies all members of the current one and adds items to it. If any of items is an array, then its elements are taken.

    To search among elements:
        indexOf/lastIndexOf(item, pos) – look for item starting from position pos, return the index or -1 if not found.
        includes(value) – returns true if the array has value, otherwise false.
        find/filter(func) – filter elements through the function, return first/all values that make it return true.
        findIndex is like find, but returns the index instead of a value.

    To iterate over elements:
        forEach(func) – calls func for every element, does not return anything.

    To transform the array:
        map(func) – creates a new array from results of calling func for every element.
        sort(func) – sorts the array in-place, then returns it.
        reverse() – reverses the array in-place, then returns it.
        split/join – convert a string to array and back.
        reduce/reduceRight(func, initial) – calculate a single value over the array by calling func for each element and passing an intermediate result between the calls.

    Additionally:
        Array.isArray(arr) checks arr for being an array.






