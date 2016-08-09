# Building ontology

This ontology describes buildings, usually structures which contain at least two rooms and a roof. We wanted to keep it simple, but the main focus lies on architectural facts.

## Acknowledgements

The building ontology is inspired and based on ideas of M. Goetz and A. Zipf (Related paper: [Extending OpenStreetMap to Indoor Environment: Bringing Volunteered Geographic Information to the Next Level](http://koenigstuhl.geog.uni-heidelberg.de/publications/2011/Goetz/Goetz-Zipf_2011_IndoorOSM.pdf))

## Illustration

![](https://rawgit.com/AKSW/leds-asp-f-ontologies/master/ontologies/building/diagram.svg)

## Main terms (TODO: check english translation for correctness, defining barrier)

### building (Gebäude)

(Eine Menge von physischen Räumen.)
A set of physical rooms.

### physical room (Physischer Raum)
("Physischer" Raum ist ein 3D-Bereich, welcher begrenzt wird durch Wände, Durchgänge und Barrieren.)
"physical" room is a 3D area that is limited by walls, passages and barriers.

### passage (Durchgang)

(Ein Durchgang ist eine Struktur, welche physische Räume bzw. Gebäude verbindet.)
A passage is a structure that connects physical room resp. buildings.

#### types (Typen)

- wall passage (Wanddurchgang) 
- building passage (Gebäudedurchgang) - (z.B. tech. Rathaus von Haus A zu Haus B) (e.g. tech. Rathaus transition between house A and B


### wall (Wand)

(Eine Wand eine vom Boden ausgehende größtenteils undurchlässige Struktur.)
A wall is a stracture that is going out from the ground and mostly impermeable.

### barrier
Barriere is a mostly impermeable structure that is preventing something from passing without separating a pyhsical room in multiple pyhsical rooms.
