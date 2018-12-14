# AudioToaster

AudioToaster is a tool for processing audio in emulations of circuits loaded from schematics and layouts designed using [DIY Layout Creator](http://diy-fever.com/software/diylc/) [(source code)](https://github.com/bancika/diy-layout-creator). In other words, you design a guitar pedal circuit and then you can run audio through it to hear what it would sound like through the pedal.

### Feature Roadmap

- [x] Load .diy files and generate netlist for ACME.jl circuits
 - [x] Passive components and component schematics
 - [x] Wires, traces, jumpers, schematic lines
 - [x] Diodes
   - [x] Default diode
   - [ ] Specific diodes, e.g. `1N4004`, `1N4148`
 - [ ] BJTs
   - [ ] Schematic BJT
   - [ ] TO92 package
   - [ ] Other packages
   - [ ] Load data from Name element, e.g. `Q1_NPN_CBE`
   - [ ] Load full presets from component values, e.g. `2N3904`
 - [ ] Opamps
   - [ ] Default single opamp on IC
   - [ ] Single and dual opamps
   - [ ] Specific opamps from value, `TL071`, `NE5534`, etc.
 - [ ] Potentiometers
   - [ ] Default pots to 50% of maximum
   - [ ] Load pot rotation from Name, `VR1_throw=0.5`
 - [ ] Boards
   - [ ] Vero
   - [ ] Triboard
   - [ ] Breadboard
   - [ ] Trace cuts
- [x] Audio Processing
  - [ ] Stereo support
    - [ ] Stereo input
    - [ ] Stereo output
  - [ ] Support for multiple audio formats
    - [x] .wav
    - [ ] .flac
- [ ] Documentation
  - [ ] User Guide and examples
  - [ ] Developer docs
- [ ] GUI
- [ ] Explore possibility of real time audio processing
