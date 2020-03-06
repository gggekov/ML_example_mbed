# ArmMLHackathon-Mar2020

## Usage

To load the dependencies this code requires, run:

```
mbed config root .
mbed deploy
mbed compile -m auto -t GCC_ARM
```

If this works, it will give you a .bin file that you can flash onto the device
you're targeting. For example, using a Discovery STM3246G board, you can deploy
it by copying the bin to the volume mounted as a USB drive, just by dragging
over the file.

## Project Generation

See
[tensorflow/lite/micro](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/micro)
for details on how projects like this can be generated from the main source
tree.

## License

Code is covered by the Apache2 License included in the repository,
and third party dependencies are covered by their respective licenses, in the
third_party folder of this package.
