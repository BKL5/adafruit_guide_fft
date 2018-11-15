# FFT: Fun with Fourier Transforms

Code in support of the ['FFT: Fun with Fourier Transforms' guide](http://learn.adafruit.com/fft-fun-with-fourier-transforms) on the [Adafruit learning system](http://learn.adafruit.com/).

martin-ger:
- Added sampling code for the ESP8266 and the ESP32. Connect e.g. a MAX4466 to the A0 ADC.
- Changed serial baudrate to 115200
- Max. sampling rate now 40000Hz (ESP8266 hardly manages 10000Hz, ESP32 is better)

Requires Python 2.7 with:
- cmake
- matplotlib, a library for plotting data.
- NumPy, a library for numeric computing.
- PySide, a python binding to the Qt user interface library.
- pySerial, a library for serial code IO.


## License

The MIT License (MIT)

Copyright (c) 2013 Tony DiCola

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
