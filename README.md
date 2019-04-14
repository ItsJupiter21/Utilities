# Utilities

This is a collection of useful functions for the Arduino Framework. All the functions are quite simple, you can see them in the [header](Utilities.h).

Upload the [example](/examples/basic/basic.ino) to see how to use them 🔥

# Functions

#### doEvery()
Run a task every given time without blocking the rest of the code

#### pinModeGroup()
Change the state of a group of pins

#### digitalWriteGroup()
Write the state of a group of pins

#### digitalToggle()
Toggle the state of a pin

#### digitalToggleGroup()
Toggle the state of a group of pins

#### echo()
Echo between two serial ports, bi or mono directional

#### printArray()
Print an array of any kind

#### splitString()
Split a cstring into token and get one of them

# Macros

#### LEN
Get the exact size of any array

#### TO_FAHRENHEIT
Convert Celsius to Fahrenheit

#### TO_CELSIUS
Convert Fahrenheit to Celsius

# Extras

in the [extras](/extras) folder there are two useful python scripts:

### keywords
Automatically generate the keywords.txt from a header file or make an existing keywords.txt with a uniform indentation

### wrap
Wrap a word around any symbol for documentation of source code