# 201 Course reading 03

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)

#### From the Duckett HTML book:
###### Chapter 3: “Lists” (pp.62-73)
###### Chapter 13: “Boxes” (pp.300-329)

##### From the Duckett JS book:
###### Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

```<jokememe>```**So I heard you like lists, so I made you a list with lists inside.**```</jokememe>```  
* ordered list
    * ```<ol>
	    	<li>item1</li>
	    	<li>item2</li>
	    </ol>```
* unordered list
    * ```<ul>
		    <li>itemWithoutNumber<</li>
		    <li>itemWithoutNumber</li>
	    </ul>```
* Definition List
    * ```<dl>
	    	<dt>dataterm<</dt>
	    	<dt>dataterm</dt>
	    	<dd>defintionofaboveterm</dd>
    	</dl>```
*lists can be nested just like word docs

### Box model of HTML
From outside in the boxes are like this and block elements are a straight stack of boxes by default without css: Margin, border, padding, content 

Width and height can be control a large number of ways from minimum to maximum and making them absolute pixel or percentages

Overflow tells browser what to do with content larger than its container box scroll is a value for this, since text size is often adjustable having a plan for this is hand

Margin and padding controls how far things are away from the brder from the outside for margin and how much space is between the contents and the border for the padding  
these help with white space and readability

Border is something which isn't empty space (though it taakes up no space and is invisible by defautlt) and can be styled

centering a box in a page means centering the right and left margins to auto and a set width, in older borwsers this is also done via text align:center;

inline makes block level items act like an inline element

block is opposite of above

is like inline but they retain some block like features

visibility can change if something can be seen

border-image makes awesome fancy stuff re-read page 319

border radius has elipse functions!! it basically allos organic curves


## Javascript


### Conditional logic
* Checking whether a condition has been met, if so then it run

* **example** ```if () {}```
* **syntax:** keyword parentheses code block
* **meaning:** keyword parameter 
* ```if``` checks for match 
* ```else``` is the keyword for inverse of previous keyword
* ```else if``` is the keyword helps act as a bridge from first if to the end
* ```switch () {}``` allows cases as different conditions known as cases, which compares to each, it does EVERYTHING after the first truthy statement, can add ```break;``` to prevent it from continue (if you want only one to use) or return while within function. useful for checking a single parameter


### truthy and falsy

so if variable that can be interpreted as true or false boolean values

#### Truthy
* String with content
* non-zero number
* true
* empty object/array
falsy
* empty string
* the number zero
* false

Javascript is dynamic type language

* Strings characters within quotes or single quotes
* number numerical value
* Boolean true or false
* null is set to nothing specifically
* undefined means something was overlooked

coercion!!

they work top to bottom left to right and stop *(short curiut)* when they return a result 

```==``` does not compare type

```===```  does compare type


### **LOOPS**

#### For Loops
* begin counting at 0 in computing
* ```for (var i = 0; i < surveyAnswers.length(); i++)```
* keyword (variable indexNumber isAssigned toZero; indexNumber isLessThan theArrayNamedsurveyAnswers.modifiedByLengthMethod(); interateIndexNumber)
* the array above could be a predefined number or other variable

#### While Loops
* keeps in loop until condition is met
* code block isn't run until condition is met

#### Do While Loops
* main difference is that code block is being run before the condition is met


