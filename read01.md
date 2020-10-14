# Responsive web design

## responsive web design "RWD" developed to make an adaptive and responsive websites, to fit all sizes of the screens such as the mobile , desktop or a tablet.

* responsive : means that the website react quickly to any change. (that means the website is changes based on the different factors such as the size of screen)
* adaptive : to be easily modified for a new situation.
* mobile : a seperate website with a different domain

## RWD consists of : 
1. Flexible layouts
2. Media queries 
3. Flexible media

### Flexible layouts :
#### this component used to build a responsive layout which deal with a units like percentages or em to make a relative lengths which are capable to resizing based on the width of the viewport. ethan develp a formula to create these relative unit by deviding the target width on the parent element's width. there more than these two units! but these previous units still not common to use. such as vw, vh, vmin, vmax.

#### Flexible grids : Example : 
##### HTML : 
    
    <article id="test">
        <section></section>
        <form action=""></form>
    </article> </br>

##### CSS : 
    
    #test {
        width: 500px;
    }
    section{
        width: 20% ; /* 100%500 = .2 */
    }
    form{
        width: 76% ; /* 380%500 = .76 */
    }
    section,form {
        margin: 4%; /* 20%500 = .04 */
    } </br>


### Media queries :
#### "Media queries provide the ability to specify different styles for individual browser and device circumstances" , So, there is many ways to use the media queries : 
* @media rule : each media rule may include the media type fllowed with some expressions. common media types are : (all, screen, print, tv, and braille), the expressins cosists from one or more than one property and if this condition is true then the style will be applied and vise versa.
   
#### there are some logical operators that used in the media queries .. *and, not, only*.

    @media all and (min-width: 630px) and (max-width: 1024px) {...} </br>

#### Media Features : most common features used in the media queries are the width and height of the viewport , also the min-width, max-width are common too. these properties help to create a RWD. Orientation feature control the viewport if it is a landscape or a portrait.

#### Mobile first : its a style to target the small viewport as a default style then to use the media queries on the larger devices. for the mobile's style its a good practice to reduce the heavy and un necessaary styles such as animations and shadows.

#### using the meta device-height or device-width allows the website to be sized properly. the minimum-scale, maximum-scale, initial-scale, and user-scalable properties let you control how the website will be scaled on the mobiles. the initial scale should be integer number betweel 0 and 10. user-scalable turn on and off the zooming from the user side.


### Flexible media :
#### to make the videos, images and the other media type scalable. to do that you should use the max-width=100%; property. but it is not working well on some of media types like iframes and embeded media, so in this case you need to make the media absolute positioned within the parent element.


## Floats 

### float property in CSS used as a "positioning feture" , its allow the element to float left or right , so that the following element will be positioned mostly around or next to it. *"Floated elements remain a part of the flow of the web page.* , also the float property could be use for the whole layout of the website.

#### there is some unique advantage for using the float , although there is a flexbox and grid to make the layouts. for example when you resize the floated element the following element will reflow in the new position. there is also an important property called "clear:both;", it is used on the element that you want to remove the effect of the floating on it. both only is the most common use but there is clear left and right , none and inherit too.

#### there a interesting note about the parent element, when the parent element only contains a floated content thet it collapse to nothing.

#### Techniques for clearing floats :

1. clear:both; if you know what the succeeding element is going to be.
2. The Empty div method: empty div contains inline formatting using style tag and clear;both;. br maybe used.
3. The overflow method: using a overflow property on the parent element, then it will expand to contains the floats.
4. The easy clearing method: using the pseudo selector :after to clear floats with additional class  “clearfix”. then apply : 
    
    .clearfix:after { 
       content: "."; 
       visibility: hidden; 
       display: block; 
       height: 0; 
       clear: both;
    }</br>





