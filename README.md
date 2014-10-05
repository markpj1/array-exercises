## Arrays
[Back to Home](https://github.com/bgando/JS102)

Create an array.

- Create a variable called `noiseArray` and assign it to an array literal. Place at least one element in the array.

Using a native array method…

- Add a noise to the beginning of the `noiseArray`.
- Add another noise to the end of the `noiseArray`.


Using Bracket Notation…

- add another noise to the end.

Inspect the `noiseArray`

- What is the length?
- What is the last index? How is it different than the length?
- Inspect your handiwork! What does it look like?


##### Step 1C - Nest the Array in the Object
Put the `noiseArray` inside the animal object

- Create a variable called noizes and assign it the string 'noises'.
- Use the noizes variable to access the value 'null' on your animal object.
- Now use the noizes variable with the `noiseArray` to replace the value null with your `noiseArray`.
- Inspect your data structure, it should look something like this:

  `{ username: 'duck', tagline: 'Afflack', noises: ['quack', 'honk', 'sneeze'] }`
  
- Congrats! You just made a nested data structure :)  


##### Review
Let's go over some concepts:

- What are the different ways you can add properties and values to objects? 
- What about arrays?
- What if you wanted to add a property to an object that had a weird symbol?
- What about if it is a variable, how does that change the syntax?

---


### [Step 2: Animal Collection](id:collection)
A collection is an array of objects. 

- Create a variable called animals and set it equal to an empty array
  - Note that this variable is animals (plural) while the variable in step 1 is animal (singular)
- Using any method you prefer, add your animal from step 1 to the animals array.
- Create a variable called quackers and assign it to the example object that I created above:
  - `{ username: 'duck', tagline: 'Afflack', noises: ['quack', 'honk', 'sneeze', 'growl'] }`
  
- Add quackers to the animal array using a different method than before.
- Inspect your animals array to ensure you have two objects inside.
- Create two more animal objects with these properties and your choice of values: 
  - username (with a string value) 
  - tagline (with a string value)
  - noises (with an array of values)
- Check the length property of your array. It should give you 4.
