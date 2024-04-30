# Pendot A

Pendot A is a prototype font for writing education in the Arabic script. It is incomplete and will change considerably. Please do not use this as a source of derivatives. A much more useful font will eventually be released that will be a better source. Thank you!

## Minimal setup for the build

On Ubuntu/macOS/WSL2 you need:

- a recent version of python3 to handle the virtual environment (3.10+)
- other python3 dependencies will be installed via the Makefile calling the requirements.txt
- GNU make to run the Makefile
- ``sudo apt install make automake``  for Ubuntu
- ``brew install make`` for macOS

## Build steps

``make build`` : Builds the fonts and places them in the fonts/ directory

``make test`` : Runs Fontbakery tests and generates reports in md and html in out/fontbakery

``make clean`` : Removes generated files from the build, including the virtual environment folder(s)

``make images`` : Generates Drawbot proof image(s)


## Pendot Design Glyphs plugin setup

Until the Pendot Designer is available directly inside the Glyphs plugin manager, the installation steps are described in the Dotter repository: https://github.com/simoncozens/Dotter
