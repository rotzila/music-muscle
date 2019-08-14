# Music-Muscle
Music-Muscle is a dispositive that is responsive to muscular activity using electromyography (EMG). This dispositive have the main objective a responsive system to test patient’s strength and rehabilitation. There are two versions of the music-muscle, both react to the muscular activity, but have different responses.

## Tutorial (How to use)
### Calibration
This dispositive have a calibration mode, this is needed due to each human having different values in the same bio sensor. This calibration mode is activated by pressing the button for 2 seconds, the LED in the bottom will light up meaning the calibration mode is activated. During this period the user must be in a rest state for approximately 5 seconds, after this period the user must try to do the maximum strength possible. Pressing the button will deactivate the calibration mode, but, now with a new range adapted to the user in question. This range will give a range from 0 to 100 using the minimum and the maximum value gathered during the calibration mode.
## Music-Muscle-Frequency
In this version the audio will be a frequency that will start at a low frequency, with more "strength" the muscle is exercing, higher the frequency will be.
## Music-Muscle-Song
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
- µduino board
- [Groove Speaker](http://wiki.seeedstudio.com/Grove-Speaker/)
- [Potenciometer](https://www.sparkfun.com/products/9806?_ga=2.258241545.2017274394.1565780560-1270259391.1560514473)
- [Led](https://plux.info/barebone-actuators/19-light-emitting-diode-led.html?search_query=LED&results=32)
- [Button](http://bitalino.com/datasheets/REVOLUTION_BTN_Sensor_Datasheet.pdf)
- [EMG BITalino sensor](https://bitalino.com/datasheets/EMG_Sensor_Datasheet.pdf)
- [3-lead electrode cable](https://plux.info/cables/226-3-lead-electrode-cable.html)
- [Gelled Self-adhesive Disposable Ag/AgCl](https://plux.info/electrodes/59-pre-gelled-self-adhesive-disposable-agagcl-eletrodes.html)
### Algorithms
There are two algorithms, one for the [Frequency](https://github.com/rotzila/music-muscle/tree/master/music-muscle-freq) and other for the [Song](https://github.com/rotzila/music-muscle/tree/master/music-muscle-song) version
