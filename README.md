Bootstrap Collapse Sidebar
===================
100% CSS plugin that turns the navbar collapse dropdown into a sidebar. 

:+1: Sass/Scss support

:+1: Less support

Demo
-------------
[here](http://lucavandro.github.io/bootstrap-collapse-sidebar/)

Installation
-------------
Bower
```sh
bower install bootstrap-collapse-sidebar
```

or click [here](https://github.com/lucavandro/bootstrap-collapse-sidebar/archive/master.zip)


Then simply import bootstrap-collapse-sidebar.css in your html

```html
 <link href="css/bootstrap-collapse-sidebar.min.css" rel="stylesheet">
```

Usage
-------------
Bootstrap collapse sidebar doesn't require any extra markup.
Only if you wish to place the sidebar on the right,  add the class ```collapse-right``` along with the class ```collapse```, like in the example below:
```html
<nav class="navbar navbar-inverse navbar-fixed-top">
  ...
  <div id="navbar" class="collapse navbar-collapse collapse-right">
      <ul class="nav navbar-nav">...</ul>
  </div>
      
</nav>
``` 

Note
-------------
Only usage with ```navbar-fixed-top``` is supported.


