# csv-table

A Polymer web component that parses a CSV file (using a description file to specify the CSV dialect and other parsing options), expands the data to URIs and typed data (using a JSON-LD context file), then displays it as an HTML table.

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

## Demo

[Demo](http://git.macropus.org/csv-table/demo/index-dev.html)

## Formats

* The description is a JSON file in [CSV Dialect Description Format (CSVDDF)](http://dataprotocols.org/csv-dialect/).
* The description should have a "context" property, which links to a [JSON-LD context document](http://www.w3.org/TR/json-ld/#the-context).
