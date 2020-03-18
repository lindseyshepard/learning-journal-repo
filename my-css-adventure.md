[Return Home](https://lindseyshepard.github.io/learning-journal-repo/)   


# Cascading Style Sheets (CSS)

CSS is what makes web pages nice to look at. HTML is the structure of the page but the UX and UI design come from CSS.

A CSS rule will have two parts to it. the _selector_ and the _Declaration_. The declaration will sit inside curly brackets and that is made up of two parts, _property_ and _value_.
> P {
    background-color:blue; //Background-color is the property and blue is the value of the property
}

CSS in my opinion should be on its own page. I personally think that is cleaner but you can use CSS interally as well. If the CSS file is external then the link element can be used to tell the browser where to find the CSS file. CSS internally would be declared inside a style tag inside the head element. 
> Advantages to buidling a website and CSS having its own style sheet: The web pages can use a link tag for the browser to find the CSS. This is good if you don't want to have repeat css code through out your project. When the user downloads the css the rest of the pagewill load faster. If youhave all your CSS on one page then editing it will be easier in one location

> CSS on the same page: If you are creating a simple, single page website. If you have a few pages on your website but the styling is kept to a minimum and is simple then you can style the CSS on each page as needed. To do this use the head tag


## Selectors

CSS selectors allow you to target rules to a specific element in an HTML document  


CSS Selector | Example
-------------- | -----------------
Universal Selector | * {}  
Type selector | h1, h2, h3 {}  
Class selector | .note {},p.note {}  
ID selector | #id {}  
child selector | li>a{}  
descendant selector | p a {}  
Adjacent Sibling Selector | h1+p {}   
General Sibling selector | h1~p {}  

Similar to other languages CSS also has inheritance, meaning that the child elements unless specified will also follow the same rules as the parent element. Same applies to how CSS rules cascades. Precedence is a factor when writing this language. 

**Quick facts to take away from this CSS mini lesson:**

- CSS treats each HTML element as if it appears inside its own box  
- Rules are made up by selectors  
- Different types of selectors allow you to target your rules at different elements  
- Declarations are made up from 2 parts: the properties of the element you want to change and the value  
- CSS rules usually appear in a seperate document although they can appear within the HTML page