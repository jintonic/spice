# Peak Detector

## Input Signal
The input signal is the output of a pre-amp of a scintillation detector. It is approximated by an exponential rise + an exponential decay. Such a function is available in LTSpice as [EXP]:

![EXP in LTSpice](https://www.analog.com/en/_/media/analog/en/landing-pages/technical-articles/ltspice-using-time-dependent-exponential-sources-to-model-transients/expvoltagesourceparameters.png?la=en&w=900&rev=3282324d4d9d424ca7d8d475c2e09d86 "Parameters of EXP function in LTspice")

[EXP]: https://www.analog.com/en/resources/technical-articles/ltspice-using-time-dependent-exponential-sources-to-model-transients.html

## Components

The model of BAT85 diode is from <http://bordodynov.ltwiki.org/>. It is pasted as a line of SPICE code in the schematic file. The standard diode symbol in the schematics is associated with the model by renaming its value to be the model's name (BAT85).

The model of 2N7000 transistor is from <https://ltwiki.org/index.php?title=Standard.mos>.
