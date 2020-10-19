# jQuery 
## jQuery is a file of JavaScript type that allows to perform a JS tasks and to select element in a simpler way. also jQuery could handle an events by a methods such as the event listener. 

### find elements : jQuery select the elements by using the naming of the CSS. for eaxample :

    $('img.first'); </br>

### perform tasks : as I said , there is many methods that jQuer could perform in a simpler way than regular JS. see this example :
    
    $('#data').addClass('single'); </br>

### Why use jQuery?
1. simple selectors
2. performing task in a simpler way
3. cross browser campatibility

#### finding elements : jQuery select HTML elements as the the way of CSS. by classes, IDs , global selector '*' , element name and etc ..  

### jQuery selection : you can select one element or more than one like a 'set of elements' for example you may select $('td') and it will select all the table data from the html.
### method of set and get data : as we said in the selcetion it may be one or more selected, so if there is more than orne element selected jQuery method will get only the first one using the html() method. using the same method you can update the content of the element for example .html('hello').
### when declaring a variable and set object in it, that will refrence to that object and it will not be a copy from it.

### the ready function :is a method to check if the page is loaded to work. example :
    
    $(document).ready(function() {
        code lines ..
    }) 
    // or there is a shortcut .. 
    $(function(){
        code lines ..
    }) </br>

#### there are some common method in the jQuery :
1. append : to add before closing tag
2. prepend : to add after opening tag
3. before : to add before the selected element
4. after : to add after the selected element
5. html : to add a new content , it could contains a mark up
6. text : to add a new content , only it shows a text without markup
7. remove : to remove the selected element
8. replaceWith , attr , addClass , removeClass .. etc.

#### jQuery also could set some properties in css , this is an example for it :
    
    $( ' h1 ') .css({ 'font-size' : '20px' , 'color': 'red'} ) ; </br>

### you can add the jQuery in many ways , you could make a script with src = ''.

## pair programming 
### pair programmin mainly consists from two roles: 
1. navigator : who is uses their words to guide the Driver but does not provide any direct input to the computer.
2. The Driver : who is typing and the only one whose hands are on the keyboard.

#### Why pair program?
* Greater efficiency
* Engaged collaboration
* Learning from fellow students
* Social skills
* Job interview readiness
* Work environment readiness