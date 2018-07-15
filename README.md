## Background

The collection of data in the given JSON was too big to manually go through and find specific data. By creating a web page and using filters, we have the ability to sort through the data easier. 

Code was written that created a table dynamically based upon the dataset. Users also have the ability to search through the table for specific pieces of information. 

### Level 1: Automatic Table and Date Search

* Create a basic HTML web page.

* Using the ufo dataset provided in the form of a JavaScript object, write code that appends a table to your web page and then adds new rows of data for each UFO sighting.

  * Added a column for `date/time`, `city`, `state`, `country`, `shape`, and `comment`

* Added an `input` tag to the HTML document and write JavaScript code that will search through the `date/time` column to find rows that match user input.

### Level 2: Multiple Search Categories

* Complete all of Level 1 criteria.

* Used multiple `input` tags and/or select dropdowns, write JavaScript code so the user can to set multiple filters and search for UFO sightings using the following criteria based on the table columns: 

  1. `date/time`
  2. `city`
  3. `state`
  4. `country`
  5. `shape`

### Level 3: Paginated Table

* Complete all of Level 2 criteria.

* Wrote code that will paginate the table (client-side pagination) and only display a maximum set number of results at a time (e.g. 50 results per page). Used [Bootstrap's Pagination Components](http://getbootstrap.com/components/#pagination) and write code to handle page changes and calculate the number of results which should appear on each page. 
* These changes should happen in the DOM using JavaScript, therefore the user should never be directed to another web page as they paginate through the results.
