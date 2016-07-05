# Febible

A collection of front-end examples using HTML/CSS/JavaScript for newbies  

To be intuitive every demo is Integrated with JSFiddle by organizing files in the given structure as follows:  
```
DemoDirectory
 - demo.html
 - demo.css
 - demo.js
 - demo.details  
```

demo.details is a description of the demo written in YAML, structure compatible with MooTools doc.

```
Everything before the line containing only '---' will not be parsed

---
 name: The Name of the Demo
 description: Some description, please keep it in one line
 authors:
   - John Doe
   - Jan Wisniewski
 resources:
   - http://some.url.com/some/file.js
   - http://other.url.com/other_filename.css
 normalize_css: no
 ...

Everything after the line containing only '...' will not be parsed
```

All above fields are optional.

#### Run in JSFiddle

One need to choose the framework and the GitHub path using the URL:  
URL:  `http://jsfiddle.net/gh/get/{framework}/{version}/{github_tree}/`  
Use `library/pure` for no framework:  
URL: `http://jsfiddle.net/gh/get/library/pure/{github_tree}/`  
There is an option to add dependencies as a comma separated list:  
URL: `http://jsfiddle.net/gh/get/{framework}/{version}/dependencies/{dependency_list}/{github_tree}/`


##### Example

Demo on the github: `http://github.com/yison-dripower/febible/tree/master/css/center-horizontally/`  
URL to jsFiddle: `http://jsfiddle.net/gh/get/mootools/1.2/yison-dripower/febible/tree/master/css/center-horizontally/`  
It will load the fiddle with MooTools framework in version 1.2.5
