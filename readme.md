# d3.js Boilerplate

d3.js Boilerplate is a template designed to help you build a
sophisticated data driven document as fast as possible. By providing a
full featured template and encouraging 
the use of coffeescript and various other javascript libraries, this
project hopes to cut down on development time. 

## Quick start

### Get the template
* Clone - `git clone git@github.com:zmaril/d3.js-boilerplate.git`
* Rename - `mv d3.js-boilerplate my-ballin-document`

### Develop locally
* Move `cd my-ballin-document`
* Host `python -m SimpleHTTPServer`
* Navigate to localhost:8000

### Deploy Globally 
* Host - `heroku create my-ballin-document --stack cedar`
* Commit - `git commit -am "Totes my goats"`
* Push - `git push heroku master`

## Features

* Based on [HTML5 boilerplate](http://github.com/h5bp/html5-boilerplate). 
* Comes with d3, underscore, jquery-ui and MathJax already loaded in. 
* MathJax allows you to use latex to create your labels (via
  foreignObjects). 
* Includes useful datasets, such as polygons for the world-countries
  and United States. 
* rm is your friend. Show no mercy.

## Contributing

Anyone and everyone is welcome to contribute. 

### Current TODOS
* Find more useful datasets to include. Zip codes? Time zones? 
* Try to scale MathJax down some. It's huge. Only the SVG components are used, so
  everything else can fall away. 
* Create a better example for the index graph.

## License

### Major components:

* jQuery/jQuery-ui: MIT/GPL license
* Modernizr: MIT/BSD license
* Normalize.css: Public Domain
* d3.js: [License](https://github.com/mbostock/d3/blob/master/LICENSE)
* underscore: [License](https://github.com/documentcloud/underscore/blob/master/LICENSE)
* MathJax: Apache 2.0 License

### Everything else:

Public domain. If you [sent me](https://twitter.com/#!/ZackMaril) a
tweet if you cloned this, I would be all warm and fuzzy for a few
minutes.
