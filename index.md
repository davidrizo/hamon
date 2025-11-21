# HAMON harmonic model
The following encoding formats will be considered:
* [MEI](mei.md)
* MusicXML
* MNX
* MSCZ
* **kern
* Lilypond
* ABC
* [MIDI metadata events](https://forums.steinberg.net/t/lyrics-and-chords-on-a-midi-file-as-metadata/832447)

## HAMON grammar
**TO-DO** Describir el significado del acrónimo
**TO-DO** Describir gramática

The [grammar in EBNF format](hamon.ebnf) is used to describe the model as a means of structuring the information while making it independent of formats (i.e. JSON, XML, etc...).

### Start
Using this `start` element is useful for representing whole harmonic sequences independent of notes.

### Chord sequences
This is a sequence of chords with, possibly, alternative sequences.

See this example:
**TODO Ejemplo musical**
```
A    B    C    D    F
     X  Y      Z
```
would be encoded as:
```
A, B | X, Y | **TODO**    
```

### Chord label
This can be notated as "American chord symbols TO-DO", roman-number, etc ....


#### Root
It's the root of the chord.




## Mapping between encodings
Rules and an illustrative example will be provided to describe the mappings.

### Root
#### MEI
#### MusicXML
