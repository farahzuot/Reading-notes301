# Regex tutorial

## rejext is used to extract a data from the texts by searching or matching or matching and replacing. the serching is may be applied using the test() function in js, it will give a truthy or falsy result! , in the other hand match() function will put the matches into array.

#### rejext actually could be used in most of the programming language so its not particular for the javascript, so let's dig in deep in this amazing tool.

#### well, rejext is a really wide to learn but there is some categories which could grouping the topics of it:
1. Anchors

* ^ :  matches any string that starts with "could be anything" example : ^Hi >> will match any string start with Hi.
* $ : matches a string that ends with "could be anything" example : Hi$ >> will match any string end with Hi.

2. Quantifiers : * , + , ? , {}.
3. OR operator : | , [].
4. Character classes : \d , \w , \s , '.'

### Flags : 
1. g : global
2. m : multi-line
3. i : insensitive

#### so this tool could be really useful while coding to find or to replace any part of a text by using the validoter 'test()' or the match or the replace. example : 
     let string = "Hi there!"
     function find(str){
         let capitalized = /[A-Z][a-z]*/;
         return capitalized.test(str); 
     }
     find(string); // this should return true!


          let string = "Hi there!"
     function matchin(str){
         let capitalized = /[A-Z][a-z]*/;
         return str.match(capitalized); 
     }
     find(string); // this should return ['Hi'].
     </br>


## Grid layout 

### grid system is used to make the layout of our content, to make it displayed in a better way without cluttered , although there is another ways that grid such as floating and flexbox, it still has it's own advantage.

#### first of all after selecting the container you should use the display property, it has a two options which are grid and inline grid. and there is a set of propery that are using with the grid system to create it in a good way. in the cildren side you need some properties such as : 

1. grid-column-start
2. grid-column-end
3. grid-row-start
4. grid-row-end

#### there some short hand to right these for properties , the grid-column and the grid-row. also there is another great shorthand for these too ! it called the grid-area which accept a four values which are the above.
#### also, there some other properties for the container such as :

* grid-template-columns
* grid-template-rows 

#### these two properties are using to detemine the number of rows and columns also the width or height of them. we didn't forget about the order ! this is a property for the children to determin the order of each element.
