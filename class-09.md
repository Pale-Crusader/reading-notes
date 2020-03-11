# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)


##  Forms & Events

 ### JS
pages 243 -292 

* when browsing the web the browser registers different types of "events"
* detecting these events can cause script to run!
* Three types: 
    * Interaction: user clicks, hovers the mouse over something, presses a key, swipes over something
    * Event Triggered: events can trigger other events too
    * Code Responds to User Input: can detect changes in elements which can recieve user input 
* Event Types:
    * UI Events
        * load
        * unload
        * error
        * resize
        * scroll
    * Keyboard Events
        * keydown
        * keyup
        * krypress
    * Mouse Events
        * click
        * dblclick
        * mousedown
        * mouseup
        * mousemove
        * mouseover
        * mouseout
    * Focus Events
        * focus/focusin
        * blur/focusout
    * ## **Form Events**
        * input
        * change
        * submit
        * reset
        * cut
        * copy
        * paste
        * select
    * Mutation Events
        * DOMSubtreeModified 
        * DOMNodeInserted
        * DOMNodeRemoved
        * DOMNodeInsertedIntoDocument
        * DOMNodeRemovedFromDocume

* when events happen the terms are **fired** or **raised** 
* what events do when they have been fired or raised is **trigger** a ```function```

* METHOD TO TRIGGER CODES
    1. select the HTML _element_ upon which the event will respond to
    2. indicate what _event_ you'd like to happen, this is known by the term **binding**
    3. state what _code_ you'd like the event to trigger

* EXAMPLE PAGE 249

* do not use ~~HTML~~ ~~event~~ ~~handler~~ (this is considered bad practice) (page 251)
    * do use Traditional DOM Event Handler
    * use DOM level 2 Event Listeners



### HTML
pages 144 -175 & 330-357 
* used to get user imput without annoying prompts
* gives control to user via events above
* form has fields can be filled in, buttons to push, and even checkboxes and circles to select
* ```<form``` parent to below
    * ```<input>```
        * ```type=password```

        * ```type=checkbox```
        * ```type=radio```
        * ```name```
        * ```size.length```
    * ```<textarea>```
    * ```<selext>```
