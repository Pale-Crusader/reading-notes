# Code 201 Reading Notes

# Reading 2!

## Text

**Structural markup:** elements that can be used to describe headings and paragraphs  
**Semantic markup:** provides extra information; such as where the emphesis is placed within a sentence or that something written is a quotation, the meaning of acronyms and such  

*Note all of the below have the / in front of the denoted text within the angle brackets for the closing tag*  
* headings (Up to 6 levels, just like word docs, denoted via letter h and number plus any attributes within angle brackets)
	* ```<h1>```  
	* ```<h2>```  
	* ```<h3>```  
	* ```<h4>```  
	* ```<h5>```  
	* ```<h6>```  
* paragraph (denoted via letter p plus any attributes within angle brackets) by default each is shown as a new line, also don't forget box/container with margin border, padding, contents as block elements are like a stack of boxes by default (analogy)
	* ```<p>```  
* bold is an inline tag (denoted via the letter b within angle brackets) 
	* ```<b>```  
* italics is an inline tag (denoted via the letter i within angle brackets)
	* ```<i>```  
* superscript is an inline tag (denoted via the letters sup within angle brackets), because less common than previous inlines this is making it smaller and above, like a exponent
	* ```<sup>```  
* subscript is an inline tag (denoted via the letter sub within angle brackets), because less common than previous inlines this is making it smaller and below, like the 2 in H2O
	* ```<sub>```  
* When attempting to add extra space for ease of reading, remember that, like two spaces next to each other the browser only show one, known as **"white space collapsing** some web authors take advantage of this to indent thier code for their ability to follow without making it appear to the standard user
* line breaks allow you to make a break of text within a paragraph, and unlike other tags it does not have an opening and closing tag (it is denoted via the letters br followed by a space and then a / within angle brackets all by itself where you want the break.) Because it is by itself it is known as an **empty element**.  
	* ~~~<br />```
* horizontal rules allow you to make a break between elements, which appeared as a line between sections in the example and unlike other tags it does not have an opening and closing tag (it is denoted via the letters br followed by a space and then a / within angle brackets all by itself where you want the break.) Because it is by itself it is known as an **empty element**.  
	* ~~~<hr />```
	
### Visual Editors & their Code views

* HTML editors, like dream weaver can give you two views of what your editing, on one side showing the raw code and the other what it would appear like on the page
* they have awesome drop down options to get formating and click a button solutions for horizontal rules
* copy pasting from such things may add extra markup, this can be detrimental
* it is good to use note pad or other such non-formated text editor for copy pasting raw code to prevent the above
* It is **VITAL** to be literate in the code and not just trust the editor to do it for you

### Semantic markup
**Semantic markup:** provides extra information; such as where the emphesis is placed within a sentence or that something written is a quotation, the meaning of acronyms and such


* strong is an inline element tag (denoted via the word within angle brackets), show strong emphasis, often shown as bold
	* ```<strong>```  
* em is an inline element tag (denoted via the letters em within angle brackets), used for emphasis often shown as italics
	* ```<em>```  
* blockquote is an inline element tag (denoted via the word blockquote within angle brackets), used to make quotes
	* ```<blockquote>```  
* abbr is an inline element tag (denoted via the letters abbr within angle brackets), used for abbreviation, attributes allow to open to show full meaning page 53
	* ```<abbr>```  
* cite is an inline element tag (denoted via the word cite within angle brackets), used for citation used around publications, not really people
	* ```<cite>```  
* dfn is an inline element tag (denoted via the letters dfn within angle brackets), used for defining a term for the first time on a page and often shows as italics
	* ```<dfn>```  
* address is an inline element tag (denoted via the word address within angle brackets), used for defining a term for the first time on a page and often shows as italics
	* ```<address>```  
* ins is an inline element tag (denoted via the letters ins within angle brackets), used for showing an item has been inserted
	* ```<ins>```  
* del is an inline element tag (denoted via the letters del within angle brackets), used for showing that an item was deleted 
	* ```<del>```
* s is an inline element tag (denoted via the letters dfn within angle brackets), used for showing something is inaccurate or no longer relevant
	* ```<s>```
	
## Javascript

* functions do stuff by taking parameters
