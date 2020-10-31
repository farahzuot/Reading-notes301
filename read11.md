# EJS 

### Installations: 
    
    $ npm install ejs </br>

### usage:
    
    let ejs = require('ejs');
    let people = ['geddy', 'neil', 'alex'];
    let html = ejs.render('<%= people.join(", "); %>', {people: people}); </br>

### CLI:

    ejs ./template_file.ejs -f data_file.json -o ./output.html </br>

### Browser support:
    
    <script src="ejs.js"></script>
    <script>
    let people = ['geddy', 'neil', 'alex'];
    let html = ejs.render('<%= people.join(", "); %>', {people: people});
    </script> </br>



#### Query parameter reference



#### API-specific query parameters : Request parameters that apply only to specific operations in the Books API are summarized in the following table.



#### There are special (case-sensitive) keywords you can specify in the search terms to search in particular fields, such as: 

* intitle: Returns results where the text following this keyword is found in the title.

* inauthor: Returns results where the text following this keyword is found in the author.

* inpublisher: Returns results where the text following this keyword is found in the publisher.

* subject: Returns results where the text following this keyword is listed in the category list of the volume.

* isbn: Returns results where the text following this keyword is the ISBN number.

* lccn: Returns results where the text following this keyword is the Library of Congress Control Number.

* oclc: Returns results where the text following this keyword is the Online Computer Library Center number.