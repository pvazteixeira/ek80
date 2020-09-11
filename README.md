# EK15/60/80 and SN90 client

Simrad EK15/60/80 and SN90 echosounder python interface module. The t9ek80.py should normally not be modified, 
as it contains the generic interface. The biomass and singletargetchirp are example user files. The xml files are configuration files. 

## Setup

Clone the repository locally 

```sh
git clone https://github.com/The1only/ek80.git
```

or install via pip (not recommended at the moment):

```sh
    pip install t9ek80
```
 

## Getting started

Run the examples in the `examples` directory:

```
cd examples
python3 biomass.py biomass.xml 
```

## Notes

All testing has been done using python3

The Simrad EK80 user manual can be found [here](https://www.simrad.online/ek80/ref_en/default.htm)

To run the noise examples, or to plot results you need an X-Server running. Microsoft running Ubuntu does NOT provide this, use Xming.
