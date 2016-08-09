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
  - English: `A wall passage is located inside a wall and connects two physical rooms or a physical room with the outerworld.`
  - German: `Ein Wanddurchgang befindet sich in einer Wand und verbindet entweder zwei physische Räume oder einen physischen Raum mit der Außenwelt.`
- Building passage (German: `Gebäudedurchgang`)
  - *E.g. the "Technisches Rauthaus" in Leipzig which consists of 3 buildings, which are connected to each other via a building passage (Haus A => B and B => C).*
  - English: `A building passage connects two buildings or a building with the outerworld.`
  - German: `Ein Gebäudedurchgang verbindet ein Gebäude mit einem anderen oder ein Gebäude mit der Außenwelt.`

### Wall (German: `Wand`)

* English: `A wall is a structure which starts from the floor and is mostly impermeable.`
* German: `Eine Wand ist eine vom Boden ausgehende, größtenteils undurchlässige, Struktur.`

### Barrier (German: `Barriere`)

* English: `Barrier is a mostly impermeable structure that is preventing someone from passing without separating a physical room in multiple physical rooms.`
* German: `Eine Barriere ist eine größtenteils undurchlässige Struktur, welche jemanden am passieren hindert, ohne dabei einen physischen Raum in mehrere physische Räume zu unterteilen.`
