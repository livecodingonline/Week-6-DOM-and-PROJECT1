
## Custom DOM manipulation

**_Deadline Wednesday evening_**

1. Make an app.js and start by declaring an array that contains 10 strings. These strings should be book titles of you have read (or made up) and be lowercase without spaces so that you can use these later as HTML id attributes. (Example: Jose Saramago - Seeing -> ose-saramago-seeing). Add a console.log statement to output this array to console. (This is for debugging and making sure everything is in order.

2. Make an index.html and add the required HTML to load the app.js file. Open index.html in the browser and confirm that the console.log statement shows the array. (Open the Chrome Developer Tools and inspect the console.)

3. Make a function (or functions) that generate a ul with li elements for each book title in the array. Make sure that the function names you choose are an accurate reflection of what they do. As a reminder, here are the recommended [Naming Conventions](https://hackernoon.com/the-art-of-naming-variables-52f44de00aad "The art of naming variables").

4. Make an object (not an array!) containing information for each book. Each property of this object should be another (i.e., nested) object with the book title you thought up in step 1.1 as a key, and at least the following properties: title, language and author.

5. Now change the function from step 1.3 that you used to display the book title in a list to take the actual information about the book from the object and display that. Make sure you choose the correct HTML elements for each piece of info, for instance, a heading for the title.

6. Beautify your html page with css (use the style.css file for that), add sources and alts to each of the images.

7. Find and download book covers for each book and construct a new object which has as keys the book titles again, and as value the path to the image source (e.g. { harry_potter_blabla: './img/harry_potter_blabla.jpg', ... }).

8. Loop over these entries (hint: Object.keys(objectName) gives you an array containing the keys). Then write a function which places an image at the corresponding li element. Remember that objects are not ordered, so you cannot guarantee that the first key is the first li element. (Hint: you could give each li item an id tag by modifying the function you made before.)


##  Bonus homework:

* [Build JavaScript Objects](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/build-javascript-objects/)

* [Define a Constructor Function](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/object-oriented-programming/define-a-constructor-function/)

* [Extend Constructors to Receive Argument](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/object-oriented-programming/extend-constructors-to-receive-arguments/)

* And just for fun ... [Sum All Numbers in a Range](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting/sum-all-numbers-in-a-range/)
