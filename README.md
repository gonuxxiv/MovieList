Q2: No, there are also several other keywords that can accomplish the same thing. 
    For instance, there are "close", "closes", "closed", "resolve", "resolves", and "resolved".

Q3: You don't necessarily have to create a new PR everything for each issue to close 
    them. Instead, in the comment section, you could type multiple issue numbers with the keywords for each to close multiple issues.

Q4: 
    Anonymous function - let name = ["John", "Alex", "Smith"];
                         let intro = name.map(function (name) {
                            return `Hello, my name is ${name}.`
                         });
                         console.log(intro);
    Explanation - The map in the example code above call each element in the array 
                  and inserted into the sentence, which gets returned to the variable
                  'intro'.
    
    Named function declaration - let arr = [1, 2, 3, 4, 5];

                                 function lst(value) {
                                 let map = value.map(i => i * 2);
                                 console.log(map);
                                 }

                                 lst(arr);
    
    Explanation - The example code above has a method (.map) inside a function called
                  lst. When the function gets called, the elements in the array gets
                  called by the map method and the changes get stored into the new array. 
    
    Lastly, transformation function is sometimes referred to as a callback function,
    because it takes each element from the array and makes a new array that contains the elements which have been transformed from the original elements. 