# Setup Instruction for Linux
*Note: These steps are not proven to work because my teensy 2.0++ hasn't arrived yet*

## Getting Started
Here are the tools you will need. You will find download links below
 - A computer running Linux, I use Ubuntu 19.10
 - C Compilers
 - GNU Make


## Install `avr-gcc`
Open your terminal and execute

	sudo apt-get install gcc-avr binutils-avr avr-libc

## Install `make` and other things
If you have a develop environment, you can probably skip this step.

If you don't, you can install the build-essential package with

	sudo apt-get install build-essential

This also includes useful stuff like `gcc` that you may or may not need :)

Now you can verify that you got everything by running `make` in the project root directory.

## Next Step
*To be completed*