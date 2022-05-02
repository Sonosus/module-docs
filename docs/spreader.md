# Introduction

This is a CV-controlled 'spread' module for providing evenly offset control voltages, perfect for detuning oscillators or equally varying filter cutoffs.

It takes a CV input. A 'spread' value is then:
- added to the CV input and sent to the + output
- subtracted from the CV input and sent to the - output

The CV input is also buffered and sent to the Buffer output.

The spread value is determined by adding together the value of the Spread knob (ranging from 0 to 12V) and the value of the Spread CV input (attenuated by the CV ATT knob).
 | _ | _ |
 | --- | --- |
 | Size | 5cm |
 | Cost | £15 |
 | Power draw | ? |
 | Experience | Beginner |

 | Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |

- Images
# Design
- Description of circuit
- Full explanation of circuit
- Schematic

# Building
- BOM ( Component specific advice (matching, tempco)), IC SOCKEtS!
- PCB availability, Gerbers
- General overview/component type
- Panel wiring
- PCB mistakes/modifications
- PCB renderings

# Testing
- continuity test
- chipless power up
- Calibration

# Playing
- patch notes/audio demos
- patch ideas
- alternative uses

# License
- CC-BY-SA-4.0
- OSHWA cert