# Building ontology

This ontology describes buildings, usually structures which contain at least two rooms and a roof. We wanted to keep it simple, but the main focus lies on architectural facts.

## Acknowledgements

The building ontology is inspired and based on ideas of M. Goetz and A. Zipf (Related paper: [Extending OpenStreetMap to Indoor Environment: Bringing Volunteered Geographic Information to the Next Level](http://koenigstuhl.geog.uni-heidelberg.de/publications/2011/Goetz/Goetz-Zipf_2011_IndoorOSM.pdf))

## Illustration

![](https://rawgit.com/AKSW/leds-asp-f-ontologies/master/ontologies/building/diagram.svg)

## Main terms

The following main terms are the basement for further concepts of the building ontology.

### Building (German: `Gebäude`)

* English: `A set which contains at least one physical room.`
* German: `Ein Gebäude ist eine Menge, welche mindestens einen physischen Raum enthält.`

### Physical room (German: `Physischer Raum`)

* English: `A physical room is an 3D area which is limited by one or more walls, passages and barriers.`
* German: `Ein physischer Raum ist ein 3D-Bereich, welcher begrenzt wird durch Wände, Durchgänge und Barrieren.`

### Passage (German: `Durchgang`)

* English: `A passage is a structure that connects physical room resp. buildings.`
* German: `Ein Durchgang ist eine Struktur, welche physische Räume bzw. Gebäude verbindet.`

#### Passage types

- Wall passage (German: `Wanddurchgang`)
- Building passage (German: `Gebäudedurchgang`) - E.g. the "Technisches Rauthaus" in Leipzig which contains of 3 buildings which are connected via a passage (Haus A => B and B => C).

### Wall (German: `Wand`)

* English: `A wall is a structure, which is going out from the ground and is mostly impermeable.`
* German: `Eine Wand eine vom Boden ausgehende größtenteils undurchlässige Struktur.`

### Barrier (German: `Barriere`)

* English: `A barrier is a mostly impermeable structure, which is preventing someone from passing, without separating a physical room in multiple physical rooms.`
* German: `Eine Barriere ist eine größtenteils undurchdringliche Struktur, welche jemanden am passieren hindert, ohne einen physischen Raum in mehrere physische Räume zu unterteilen.`


### wall (Wand)

(Eine Wand eine vom Boden ausgehende größtenteils undurchlässige Struktur.)

A wall is a stracture that is going out from the ground and mostly impermeable.

### barrier
Barriere is a mostly impermeable structure that is preventing something from passing without separating a pyhsical room in multiple pyhsical rooms.
