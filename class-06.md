# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)

## Javascript Objects

* **What is an ```Object```?**
    * > Objects group a set of variables and functions to create a model of somethingyou would want to recognize in the real world. In an ```Object``` , ```variable``` and ```function``` take on new names
    ~ Javascript & Jquery
* Within an Object a ```variable``` becomes a ```property```
* Within an object a ```function``` becomes a ```method```

### Example Object (the Object is a hotel)
> ```var hotel = {```
> ```    name: 'Quey',```
> ```    rooms: 40,```
> ```    gym: true,```
> ```    roomtypes: ['twin', 'double', 'suite'],```
> ```    checkAvailability: function() {```
> ```        return this.rooms - this.booked;```
> ```    }```
> ```};```

* above format is assigning the ```object``` as a ```variable``` then a codeblock with ```key``` colon ```value``` defining a differentn ```property``` or ```method``` on each row

Page 101 to see it on the page  
You can accessing properties and method with the dot method we've been using for .toUpperCase for example  

* Creating an Object using literal notation
    * ```hotel.checkAvailability();``` to use a ```method``` above
    * ```var elName``` 
    ```elName.textContext =hotel.name;``` refers to the name ```property``` within the object
    * created via making a row of a ```property``` or ```method``` as above

If you're creating another object with the same variable name make sure you keep all the ```key``` : ```value``` rows the same but you can change what the value is, if applicable

The ```new``` keyword can make a blank ```object```, then you can add ```property``` and ```methods

> ```var hotel = new Object();```  

> ```var hotel = {```
> ```    name: 'Quey',```
> ```    rooms: 40,```
> ```    gym: true,```
> ```    roomtypes: ['twin', 'double', 'suite'],```
> ```    checkAvailability: function() {```
> ```        return this.rooms - this.booked;```
> ```    }```
> ```};```

Updating an object
```hotel.name = 'Park';```
alternate version to do same thing, you can clear via setting to blank string
```hotel.['name'] = 'Park';```

Creating Many Objects

> ```function Htoel(name, rooms, booked) = {```
> ```    this.name: name,```
> ```    this.rooms: rooms,```
> ```    this.checkAvailability: function() {```
> ```        return this.rooms - this.booked;```
> ```    }```
> ```};```

### Document Object Model
When a browser looks at a page it creates a model of the page, and that is called DOM, it is stored in memory

Document Node  
Element Node 

Picture of Dom Tree page 187

This looks like a way to picture nestingS



## Understanding the Rpblem Domain is the hardest part of programing

#### The Problem Domain
* What is it?
    * Simply put the "Problem Domain" is what the code is trying to solve or the functionality it is produce. It is the domain of the problem being solved, like the territory which must be explored to discover what you're looking for
* **Definition:** 
    > A problem domain is the area of expertise or application that needs to be examined to solve a problem. Focusing on a problem Domain is simply looking at only the topis of an individual's interest, and excluding everything else.  
    ~ Wikipedia (06:43 Pacific Standard Time, the 9th of March, 2020, Anno Domini. )
* Without a defined Problem Domain coding can be like putting together a puzzle without knowing what the picture looks like. The Problem Domain is the picture in the analogy, it is what you're shooting for and without it, breaking down how to solve the puzzle into steps is near impossible
* The Problem Domain is bigger picture aimed at

#### Why this is hard
* The real world is a messy place
* What is wanted from us is not always communicated clearly by those that want it
* We often don't have complete information

#### Understanding the Problem Domain makes programming easy
* Once you have a picture to shoot towards it does two things that really helps
    * It makes breaking it down into smaller steps possible and easier
    * It makes looking up resources easier

#### What can be done about it?

1. Make the problem domain easier
    * Examine problem domain from different angles which may reveal easier approach
    * Break problem domain into smaller problem domains
2. Seek to get more information to fill in blanks in your problem domain or get clarifcation about the problem domain by either researching about the problem domain, or similar problem domains or actively communicating with those whom gave you the problem domain to solve to get a better understanding

###
