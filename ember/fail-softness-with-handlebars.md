# Fail softness with handlebars

A helpful feature in Handlebars is _fail-softness_. When a property is either nul, or undefined, instead of throwing an error, Handlebars will instead ignore the property and move on. 
(The drawback to this feature is that it can make it difficult to debug without any warnings)

**example -** 

_If the producer does not have a street listed, then the iteroplation will not display anything._
```
{{film.producer.address.street}}
```