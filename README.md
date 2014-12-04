# csv-table

A Polymer web component that parses a CSV file, expands the data to URIs using a JSON-LD context file, then displays it as an HTML table.

## Usage

```bash
bower install hubgit/csv-table --save
```

```html
<link rel="import" href="../bower_components/csv-table/elements/csv-table.html">
```

```html
<table is="csv-table" 
    data="your-data.csv" 
    descriptionURL="your-description.json"></table>
```

[Demo](http://git.macropus.org/csv-table/demo/index-dev.html)
