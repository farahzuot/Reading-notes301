# EJS Partials

## ejs partials make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in.

#### look how you may use it! 
* create a file called navbar.ejs : contain only the HTML for the navigation bar.
* create a file called footer.ejs in that same directory.

#### after defining your partials then you could use them in you home page (index.ejs).
#### in EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %>.
####  You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.
#### creating and including partials is very straightforward with EJS.
#### see this example:

![first](https://miro.medium.com/max/700/0*VngdKfkNNx5f2un0.png)
![second](https://miro.medium.com/max/700/0*oUmdAzjcwkQZb_AR.png)

