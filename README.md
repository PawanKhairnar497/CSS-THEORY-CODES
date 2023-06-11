# CSS-THEORY
   ## CSS means Cascading Style Sheets. CSS was first proposed by Hakon Wium Lie on 10 October 1994.At time,Lie was working with Tim Berners-Lee at CERN research institute of Switzerland.Stylesheet language used to describe the look & formating of a document written in HTML.It is used to define the styles of elements on a web page,such as the font,color,size & layout of text and other elements.
   ### Importance of CSS: 1)Styling & Responsive design , 2)Seperation  of concern & appearnace , 3)Reusability & animation.
   ### Reasons to learn CSS: 1)Fast page speed , 2)Better UX & quick dev time , 3)Easy formating changes & compatibility across devices.
   ### 🦖CSS is a skin on skeleton of website.
   
# STARTING WITH CSS

### INLINE CSS: Inline css takes precedance over all other styles, and styles defined in the internal & external css are overridden by the inline css. There is no need to create an additional file, Because It Is defined in body section of HTML page. Pseudo-codes & pseudo-classes cannot be styled with inline css. 🦖Inline CSS in not for BIG PROJECTS. give everytime style , font size ,border is the disadvantage of INLINE CSS. 🦖inline css.html 
### INTERNAL CSS: The Internal CSS is used to add a unique sytle for a single document.It is defined in head section of HTML page inside the style tag. ID's & classes can be used in internal CSS you do not need to numerous file.The might take precedance over EXTERNAL CSS. Internal CSS increases page load times.They are useful for only the page they are specified on. 🦖internal css.html
### EXTERNAL CSS: When you need to make chages to several pages,you often use the external CSS.It is perfect in this situation because it enables you to alter just one file to after the appearance of the complete website. It uses the "link" tag on every page & the link tag should be put inside the head section. 🦖external css.html   
### PRIORITY IN CSS:The Priority of CSS rule is important because it determines which styles are applied to an element when these are conflicting rules or multiple CSS applied to a single element .CSS order of priority 1)Inline css , 2)Internal css , 3)External css. Inline css has a higher priority than the internal css .Internal css has a higher priority than the External CSS.
### SELECTORS IN CSS: CSS selectors are used for selecting the HTML elements that you want to style & they are a fundamental part of working with CSS.In theory,Selectors are patterns used to select the elements to which a set of styles will be applied.CSS selectors can be used to select elements based on their type,class,ID,attributes or dynamic state or position.
### TYPES OF CLASS SELECTORS: 1)Simple Selectors , 2)Combinators , 3)Attribute Selectors , 4)Pseudo-class selectors , 5)Pseudo-element selectors .
### 1)SIMPLE SELECTOR: A simple selector is either a type selector or a universal selector. Simple selector are pretty straight forward & used most of the time in developement. i)Universal Selector * , ii)Element Selector , iii)Class Selector , iv)ID Selector , v)Selector list . 
### 2)COMBINATORS:  i)Descendent selector , ii)Child selector , iii)Adjacent sibling selector , iv)General sibling selector .
### 3)ATTRIBUTE SELECTOR: The [attribute="value"] selector is used to select elements with a specified attribute & value. i) [ attribute ~ ="value" ] selector, iii) [ attribute | = "value"] selector , iii) [ attribute ^ = "value"] selector , iv) [ attribute $ = "value" ] selector .
### 4)PSEUDO-CLASS SELECTOR: Pseudo-class are used to select elements based on their state, such as when the element is hovered over, when it has focus, or when it is the first  or last child of its parent element. i):hover , ii):focus , iii):link , iv):visited , v):active , vi):first-child , vii):lang , viii):nth-child().
### 5)PSEUDO-ELEMENT SELECTOR: CSS allows developers to create special types of selecotrs called pseudo-elements,which can be used to style specific parts of an HTML element . i)::first-line , ii)::first-letter , iii)::after , iv)::before , v)::marker , vi)selection .
### 🦖DIFFERENCE BETWEEN PSEUDO-CLASS & PSEUDO-ELEMENTS: Pseudo-classes select elements based on their state or characterstics, while Pseudo-elements select specific parts of an element. Pseuso-classes are defined by adding a colon (:) & Pseudo-elements are defined by adding two colon (::) .
   
   
