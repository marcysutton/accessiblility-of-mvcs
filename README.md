#Accessibility of JavaScript MVCs
[http://marcysutton.github.io/accessibility-of-mvcs/](http://marcysutton.github.io/accessibility-of-mvcs/)

By [Marcy Sutton](http://marcysutton.com)<br>
Developer at [Substantial](http://substantial.com)<br>
twitter: [@marcysutton](http://twitter.com/marcysutton)

##Presented at:
* CascadiaJS, July 31-Aug 1 2014
* JSConf EU, Sept 13-14, 2014

## Installation

Should you want to run this presentation from source for some reason, the **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Building from source locally
Some reveal.js features require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the reveal.js repository
```
$ git clone git@github.com:hakimel/reveal.js.git
```

5. Navigate to the reveal.js folder
```
$ cd reveal.js
```

6. Install dependencies
```
$ npm install
```

7. Serve the presentation and monitor source files for changes
```
$ grunt serve
```

8. Open <http://localhost:8000> to view your presentation

You can change the port by using `grunt serve --port 8001`.
