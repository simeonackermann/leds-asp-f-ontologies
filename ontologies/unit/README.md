# Unit ontology

This ontology is based on [http://www.w3.org/2007/ont/unit](http://www.w3.org/2007/ont/unit) (creator Tim Berners-Lee) and was adapted by us. We fixed small stuff, e.g. labeling errors. Read this [paper](http://www.semantic-web-journal.net/sites/default/files/swj177_7.pdf) for a detailed overview about the purpose of the ontology.

In a nutshell: You can use this ontology to express values with their according unit. E.g. you want to express the width of a door, you can use the following triples:

```
:door   :width   _:w.
_w:     unit:m   0.9.
```

## Changes in comparison to the original version

* Changed label of unit:W from `N` to `W`
* Removed lines breaks and obsolete whitespaces from descriptions

## Illustration

The following diagram illustrates the structure of classes and related properties.

![](https://rawgit.com/AKSW/leds-asp-f-ontologies/master/ontologies/unit/diagram.svg)
