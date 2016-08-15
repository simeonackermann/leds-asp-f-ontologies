# Unit ontology

This ontology is based on [http://www.w3.org/2007/ont/unit](http://www.w3.org/2007/ont/unit) (creator Tim Berners-Lee) and was adapted by us. We fixed small stuff, e.g. labeling errors.

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
