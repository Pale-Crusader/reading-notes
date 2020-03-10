# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)

![Image of my CSS Practice from the 8th](https://pale-crusader.github.io/reading-notes/img/CSS-Selector-Practice.PNG "This is the screenshot of me successfully completing the CSS Selector task") 

## Domain Modeling
* is a process of creating a conceptual model in code for a specific problem
* it describes various entities, attributes, behaviors and  constrainsts of the [Problem Domain](https://pale-crusader.github.io/reading-notes/class-07)

* an **entity** that stores data in ```property``` and describes behavior is refered to as an **object-oriented** model

## HTML Tables
pages 126-146





## JS Functions Objects and Methods
pages 106-144


The ```new``` keyword can make a blank ```object```, then you can add ```property``` and ```methods


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

### creating objects using constructor syntax

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

The above shows creating an object with the constructor syntax, note the ```new Object();``` that makes the ```variable``` an empty ```object```

Below it is the of the adding ```property``` and ```method``` to the ```object```

example of using a ```function``` with ```parameters``` to use constructor to make multiple different objects easily

> ```function Hotel(name, rooms, booked, gym, roomtypes) {```  
> ```    this.name: name,```
> ```    this.rooms: rooms,```
> ```    this.gym: gym,```
> ```    this.roomtypes: roomtypes,```
> ```    checkAvailability: function() {```
> ```        return this.rooms - this.booked;```
> ```    }```
> ```};```

example of it making a couple hotel objects
> ```var quayHotel = Hotel('Quay', 40, 25, true, ['twin', 'double', 'suite'])```
> ```var parkHotel = Hotel('Park', 26, 25, false, ['twin', 'double'])```

### Arrays are Objects!
page 119

Built In Objects: 

Browser Window, Document, Hostory, Locatio

