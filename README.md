# Music-Muscle

Music-Muscle is a dispositive that is responsive to muscular activity using electromyography (EMG). This dispositive have the main objective a responsive system to test patient’s strength and possibilitate rehabilitation. There are two versions of the music-muscle, both react to the muscular activity, but have different responses.

## Tutorial (How to use)

The next images show each part of the prototype and a further explanation for each one.

<h3>Top</h3>
<img src="https://github.com/rotzila/music-muscle/blob/master/images/prototype_image.jpg">

- 1-Micro USB connection to BITalino

This connection will provide the power needed to the prototype have energy and allow the visualization and a possibility to store       the values in the Open Signals for further analysis.

- 2-Volume potentiometer

With a screwdriver it is possible to regulate the volume produced by the speaker.

- 3-Threshold potentiometer

This potentiometer will delimit the value needed to be surpassed by the user. Usually a user in a rest state (after the calibration)   will have a value around 2/3, the threshold can be set from 0 to 50. However, bellow 2 the speaker will be offline, this is implemented to have a way to shutoff the speaker without turning off the device.

- 4-Sensor cables

Where the coming out, the cables are represented by red (+), black (-) and white(0) as a way to facilitate the colocation of each       electrode in the muscle.

<h3>Bottom</h3>
<img src="https://github.com/rotzila/music-muscle/blob/master/images/prototype_image_2.jpg">

- 5-Calibration button

This button being pressed for 2 seconds will activate the Calibration mode. When There are 2 modes in this device, the Calibration mode and the Standart mode. After the calibration, the button need to be activated just with a click and the program will exit Calibration mode.

### Calibration

This dispositive have a calibration mode, this is needed due to each human having different values in the same bio sensor. This calibration mode is activated by pressing the button (5) for 2 seconds, the LED in the bottom will light up meaning the calibration mode is activated. During this period the user must be in a rest state for approximately 3 seconds, after this period the user must try to do the maximum strength possible. Pressing the button (5) will deactivate the calibration mode, but, now with a new range adapted to the user in question. This range will give a range from 0 to 100 using the minimum and the maximum value gathered during the calibration mode.

### Music-Muscle-Frequency

In this version the audio will be a frequency that will start at a low frequency, with more "strength" the muscle is exercing, higher the frequency will be.

### Music-Muscle-Song

This version will have a default song at a low speed, that will speed up with the muscular activity.

## What was used

### Tools

- 3D printer
- Glue
- Soldering iron
- Solder

### 3D printed parts

- Bottom part
- Top part
- Button

### Hardware

- [µduino board](https://www.crowdsupply.com/uduino/uduino/updates/update-on-production-and-delivery)
- [Groove Speaker](http://wiki.seeedstudio.com/Grove-Speaker/)
- [Potenciometer](https://www.sparkfun.com/products/9806?_ga=2.258241545.2017274394.1565780560-1270259391.1560514473)
- [Led](https://plux.info/barebone-actuators/19-light-emitting-diode-led.html?search_query=LED&results=32)
- [Button](https://plux.info/barebone-sensors/15-pushbutton-btn.html?search_query=button&results=7)
- [EMG BITalino sensor](https://plux.info/barebone-sensors/10-electrocardiography-ecg-sensor.html?search_query=emg+sensor&results=155)
- [3-lead electrode cable](https://plux.info/cables/226-3-lead-electrode-cable.html)
- [Gelled Self-adhesive Disposable Ag/AgCl](https://plux.info/electrodes/59-pre-gelled-self-adhesive-disposable-agagcl-eletrodes.html)


### Schematic

Here is the schematic used in this prototype. Instead of a arduino UNO it was used the µduino, the smallest version of arduinos. It is the same connections. [This link](https://www.crowdsupply.com/uduino/uduino/updates/pinout-and-more) will help you know where to connect each cable in the µduino board.
<img src="https://github.com/rotzila/music-muscle/blob/master/images/prototype_schematic.png">

### Algorithms

There are two algorithms, one for the [Frequency](https://github.com/rotzila/music-muscle/tree/master/music-muscle-freq) and other for the [Song](https://github.com/rotzila/music-muscle/tree/master/music-muscle-song) version.

### 3D printed parts

It was designed 3 parts, [top](https://github.com/rotzila/music-muscle/blob/master/box/top.stl), [bottom](https://github.com/rotzila/music-muscle/blob/master/box/bottom.stl) and a [button](https://github.com/rotzila/music-muscle/blob/master/box/button.stl), to encapsulate all the Hardware used in this prototype.
