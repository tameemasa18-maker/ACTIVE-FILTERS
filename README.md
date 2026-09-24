# Active Pass Filter

## Aim

To design and set up **active first-order filters using an op-amp**.

## Apparatus Required

* Op-Amp
* Resistors
* Capacitors
* Breadboard
* CRO / DSO
* Function Generator
* Power Supply

These are the apparatus specified in the practical record.

## Filter Types

The experiment deals with **first-order active filters**, including:

* First Order Low Pass Filter (LPF)
* First Order High Pass Filter (HPF)

## Design Equation

The cut-off frequency is calculated using:

```text
Fc = 1 / (2πRC)
```

## Circuit

### First Order Low Pass Filter

The circuit is designed using an op-amp along with the required resistor and capacitor components.

### First Order High Pass Filter

The first-order HPF circuit is also implemented using an op-amp, resistor, and capacitor.

The practical file provides circuit diagrams for both the **First Order LPF and First Order HPF**.

## Procedure

1. Assemble the first-order active filter circuit on the breadboard.
2. Connect IC 741 to a **±15 V DC supply**.
3. Connect the function generator to the input of the filter.
4. Apply a sinusoidal input signal, such as **1 V**.
5. Initially set the input frequency below the calculated cut-off frequency.
6. Observe **Vin and Vout** on the CRO/DSO.
7. Measure the output voltage at different input frequencies.
8. Calculate the voltage gain in decibels.
9. Gradually increase the frequency through and beyond the expected cut-off frequency.
10. Record the output voltage for each frequency.
11. Identify the frequency at which the gain becomes approximately **−3 dB** from the passband gain.
12. Plot the frequency-response curve of **Gain (dB) versus Frequency**.
13. Compare the experimentally obtained cut-off frequency with the theoretical value.

## Observation Table

| S.No | Frequency | Vin |   Vout | Gain | Gain (dB) |
| ---: | --------: | --: | -----: | ---: | --------: |
|    1 |     30 Hz | 1 V |    1 V |    1 |         0 |
|    2 |     50 Hz | 1 V |    1 V |    1 |         0 |
|    3 |     80 Hz | 1 V |    1 V |    1 |         0 |
|    4 |    100 Hz | 1 V |    1 V |    1 |         0 |
|    5 |    150 Hz | 1 V |    1 V |    1 |         0 |
|    6 |    500 Hz | 1 V | 500 mV |  500 |     -6.02 |
|    7 |     1 kHz | 1 V | 400 mV |  400 |      -7.9 |
|    8 |     2 kHz | 1 V | 200 mV |  200 |     -13.9 |
|    9 |     3 kHz | 1 V | 100 mV |  100 |       -20 |

The values above reproduce the observation table from the practical file.

## Frequency Response

A frequency-response graph is plotted with:

* **X-axis:** Frequency (Hz)
* **Y-axis:** Gain (dB)

The practical procedure specifies plotting **Gain (dB) versus Frequency** and identifying the approximate −3 dB cut-off point.

## Result

The first-order filters were designed using an op-amp and the experimental results were obtained.

The practical record states the **cut-off frequency of the low-pass filter as approximately 600 Hz**.

## Key Components

| Component          | Purpose                             |
| ------------------ | ----------------------------------- |
| IC 741             | Operational amplifier               |
| Resistor           | Determines filter characteristics   |
| Capacitor          | Determines filter characteristics   |
| Function Generator | Provides sinusoidal input           |
| CRO / DSO          | Observes input and output waveforms |
| Power Supply       | Provides operating voltage          |

## Conclusion

The **first-order active filter** was successfully designed and tested using an op-amp. The output response was measured for different input frequencies, and the frequency-response characteristics were studied.
