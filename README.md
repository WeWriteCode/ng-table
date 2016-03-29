ngTable for consumption through NPM
=================
## Installing
```
npm install -D ng-table
```

## Usage

```
var angular = require('angular'),
    ngTable = require ('ng-table'),
    otherDependency = require('some-other-thing'),
    anotherDependency = require('yet-another');

angular.module('blah', [ ngTable, otherDependency, anotherDependency ];
```

* [Configuring your table with NgTableParams](https://github.com/esvit/ng-table/wiki/Configuring-your-table-with-ngTableParams)
* [stackoverflow](http://stackoverflow.com/questions/tagged/ngtable?sort=newest&pageSize=30)

## Examples

* [Demo site](http://ng-table.com/)
* Codepen examples (**Tip**: fork these to create your own examples);
    * [`ngTable`: inmemory list](http://codepen.io/christianacca/pen/VLqVeo?editors=101)
    * [`ngTable`: server-side list](http://codepen.io/christianacca/pen/VLqqjP?editors=101)
    * [`ngTableDynamic`: inmemory list](http://codepen.io/christianacca/pen/jPxgzY?editors=101)
    * [`ngTableDynamic`: server-side list](http://codepen.io/christianacca/pen/JdwwrR/?editors=101)

## Plugins

* [Export to CSV](https://github.com/esvit/ng-table-export)