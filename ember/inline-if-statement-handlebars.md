# Inline if statement handlebars

The following syntax is similiar to a Javascript ternary operator. It will evaluate the expression, returning the second parameter if true, otherwise the second parameter if false.

**example -** 

_If the below expression evaluates as true, then it will return Teal._
```
{{#each this.colours as |colour|}}
  {{if colour.favourite "Teal" "Wrong colour!"}}
{{/each}}
```