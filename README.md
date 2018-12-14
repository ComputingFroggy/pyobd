# pyobd

## Presentation
pyOBD (aka pyOBD-II or pyOBD2) is an OBD-II compliant car diagnostic tool. It is designed to interface with low-cost ELM 32x OBD-II diagnostic interfaces such as ELM-USB. It will basically allow you to talk to your car's ECU,... display fault codes, display measured values, read status tests, etc. All cars made since 1996 (in the US) or 2001 (in the EU) must be OBD-II compliant, i.e. they should work with pyOBD. 

## Prerequisite
This has been tested on _Ubuntu 18.04_, you will need to install the following packages (assuming python is already installed):
- python-serial
- python-wxgtk3.0

For more instructions see the [installation instructions](http://htmlpreview.github.com/?https://github.com/ComputingFroggy/pyobd/blob/master/doc/install.html).

## Fork
This project is a fork from the pyobd software written by [Donour Sizemore](http://www.cs.unm.edu/~donour/), then maintained and improved by [SECONS Ltd](http://www.obd-ii.biz/contact). 

However, no new version has been released since April 2015. And the SECONS Ltd is not compatible with the latest stable Ubuntu version (18.04).

There are a few versions on github, but they have not been maintained and are not compatible with Ubuntu 18.04.

So I have decided to merge [roflson](https://github.com/roflson/pyobd) and [peterh](https://github.com/peterh/pyobd) versions and to make it work in on **Ubuntu 18.04**.
