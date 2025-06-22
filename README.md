# Lab Instructions: Object Oriented Programming
 
> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
> - Questions about using VSCode? Please see our support resources here:  
> [Visual Studio Code on Coursera](https://www.coursera.org/learn/programming-with-javascript/supplement/roMvE/visual-studio-code-on-coursera)
> #### **To run your JavaScript code**
> - Select your JavaScript file
> - Select the "Run Code" button in the upper right hand toolbar of VSCode.  
> Ex: It looks like a triangular "Play" button. <br><br>

## Task 1: Code a Person class

Code a Person class, with three parameters in the constructor: name, age, and energy.

Set the default parameters in the Person class as follows:

```
name = "Tom"

age = 20

energy = 100
```

Code two methods in the `Person` class. Name those methods `sleep()` and `doSomethingFun()`.

The `sleep()` method should take the existing energy level and increase it by 10.

The doSomethingFun() method should take the existing energy level and decrease it by 10.
<br><br>

## Task 2: Code a Worker class

Code a sub-class, inheriting from the `Person` class, and name it `Worker`.

The `Worker` class has two additional parameters in the constructor: 
- xp (for "experience points")
- hourlyWage.

These properties are set to the following default values:
```
xp = 0

hourlyWage = 10
```
The `Worker` class has all the paramerters and methods of its super-class.

Additionally, it has the `goToWork()` method, which, whenever it's run, increases the value of the `xp` property by 10.
<br><br>

## Task 3: Code a intern object

Inside the intern function instantiate the `Worker` class to code a new intern object.

The intern should have the following characteristics:
```
name: Bob

age: 21

energy: 110

xp: 0

hourlyWage: 10
```

Run the `goToWork()` method on the intern object. Then `return` the intern object.

<br><br>


## Task 4: Code a manager object

Inside the manager function instantiate the `Worker` class to code a new `manager` object.

The manager object should have the following characteristics:
```
name: Alice

age: 30

energy: 120

xp: 100

hourlyWage: 30
```

Run the `doSomethingFun()` method on the manager object. Then `return` the manager object.

<br><br>

### Nice work! 



# Lab Instructions: Advanced JS Features
 
> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
> - Questions about using VSCode? Please see our support resources here:  
> [Visual Studio Code on Coursera](https://www.coursera.org/learn/programming-with-javascript/supplement/roMvE/visual-studio-code-on-coursera)
> #### **To run your JavaScript code**
> - Select your JavaScript file
> - Select the "Run Code" button in the upper right hand toolbar of VSCode.  
> Ex: It looks like a triangular "Play" button. <br><br>

<br>


## Task: Iterate Over an Array

In this exercise, you'll use the for....of loop to iterate over an array and to iterate over an object's own properties.  
<br><br>
**Step 1.** You are given an array of dairy products:  

    
    var dairy = ['cheese', 'sour cream', 'milk', 'yogurt', 'ice cream', 'milkshake']
    


Create a function called `logDairy`. Within it, console log each of the items in the dairy array, using the for...of loop.   
The expected output should be:

```
cheese
sour cream
milk
yogurt
ice cream
milkshake
```

<br>
<b>Step 2.</b> You are given the following starter code:  

```
const animal = {

canJump: true

};

const bird = Object.create(animal);

bird.canFly = true;

bird.hasFeathers = true;
```

Create a function called `birdCan`, within it, loop over the bird object's properties and console log each one, using the for...of loop.
Remember, you need to console log both the key and the value of each of the bird object's properties.

<br>
<b>Step 3.</b> 
    Using the same starter code as in task 2, create a function called `animalCan` and within it, loop over all the properties in both the bird object and its prototype - the animal object - using the for...in loop. 
  
<br><br>
## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 

