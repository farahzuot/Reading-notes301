# Javascript Templating

## javascript templating is a way to render the website by using a 'json data file'.

### Mustache : ' logic-less template syntax' , and it can be used for many type of files : 
1. HTML
2. config files
3. source code
#### the mustache does not have loops , if statements or clauses, it only deals with tags. mustache.js usually considered as the base of the javascript templating. the mustache syntax is a double curly braces like {{age}}.

#### Mustache-Express : this allows to use mustache and express together easily. it should be installed using the command '$ npm install mustache --save' , see this example : 

* create html page for example 'page1.html'
    <p>lorem ipsun ontso {{age}}</p>
    // then use the res.render
    res.render('your age : ', {"age": 40})
    </br>



# Flexbox

## you can acces flexbox layout from a set of CSS properties like 'display' which applies to the container or the children.

### there is two axis to determin the dimension of the flex container, the main axis "primary axis along which flex items are laid out" which have a main-start and main-end, also there is a cross axis "The axis perpendicular to the main axis" which have a cross-start and end-start. So, the main size is a width or height property depend on the main axis. and the cross size is either width or height property too depend on the cross axis.

#### * order : is a property for the children items , the default value of it is zero and it is controls the order in which they appear in the flex container.
#### * flex-direction : the default value is row from the left to right, and it controls antother options like row-reverse which is a row from the right to the left, column from top to bottom and column-reverse which is from bottom to top.
#### * flex-grow : this property allows the item to be set unitless so it is dictates the content depending of the flex container, the default value is zero.
#### * flex-wrap : is has a three options which are nowrap which is the default value, wrap, wrap-reverse.
#### * flex-shrink : the ability for a flex item to shrink if necessary.
#### * flex-flow :  shorthand for the flex-direction and flex-wrap properties.
#### * flex-basis :  defines the default size of an element before the remaining space is distributed.
#### * align-self :  allows the default alignment to be overridden for individual flex items.
#### * justify-content :  helps distribute extra free space leftover when either all the flex items on a line are inflexible.
#### * align-items : defines the default behavior for how flex items are laid out along the cross axis on the current line.
#### * align-content : aligns a flex container’s lines within when there is extra space in the cross-axis.

