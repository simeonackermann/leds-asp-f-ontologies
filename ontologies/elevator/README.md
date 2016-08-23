# Elevator ontology

It describes elevators inside or outside a building. Used classes and properties are very small in number to describe only neccessary facts.

The purpose of this ontology is to act as basement for further ontology developments, such as Saxonoy building regulation ontology.

## Illustration

The following diagram illustrates the structure of classes and related properties.

![](https://rawgit.com/AKSW/leds-asp-f-ontologies/master/ontologies/elevator/diagram.svg)

## Parts of the elevator structure

- control panel
- position display
- well
    + walls 
        * guide rails
    + headroom (ceiling)
        * machine room
    + pit (floor)
        * buffer
    + lighting, emergency lighting
    + doors
        * protection device (light barries)
    + car
        * max. load control
        * walls
        * ceiling
        * floor
        * doors
            - protection device (light barries)
        * lighting, emergency lighting
        * air control
        * control panel
            - buttons for each level
            - emergency call
        * position display

Sources: DIN EN 81-20 and DIN EN 81-70