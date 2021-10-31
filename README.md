# Elasticsearch Query Parser
Simple Elastic query parser using [Ohm](https://ohmlang.github.io/) grammar

## Install
```
npm install elastic-parser
```
### Example
```javascript
var parseQuery = require('elastic-parser');
var query = '(simple:foo~ OR some:"fox quick") AND meta.estimated_start_time:[now-1h TO now]'
console.log( parseQuery(query));
```

### Credit
Extracted and modified from [prettier-elastic-query](https://github.com/traut/prettier-elastic-query)
