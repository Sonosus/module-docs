# Introduction

# Building
# Testing
### Calibration of the module

There are three trimmers in the application circuit.They should be set up as follows:

- Firstly, centre the Frequency Control and the Fine Control, since these affect the tuning.The position you set now will become the “zero” position for these knobs.
- Plug a source of 1V/Oct control voltages (an analogue synth or MIDI-to-CV convertor) into the NOTE CV input and adjust RV6 until an octave on the keyboard gives an octave from the oscillator. Don’t worry about the pitch being wrong (C plays a D, for example).This control alters the octave range, so it’s fine if pressing C0 then C1 plays D1 to D2, since both are an octave.
- The offset adjust trimmer RV5 should be adjusted to give +5V at pin 8 of U1 with the NOTE CV input grounded, but the exact value is not crucial, since the voltage is quantized to semitones. If you find the oscillator is “skipping” between notes, tweak RV5 until it stops.
- Next, adjust RV4, the FREQ MOD CV Zero Trim. With the FM CV Amount control turned down to zero, RV4 should be adjusted to give 2.5V at pin 14 of U1. Alternatively, plug the oscillator output into an electronic tuner and adjust RV4 until the notes are well tuned. If the Fine control is set to the centre zero position, this should give 2.5V as before!

# Playing