# Random Number Addition using OPTIGA™ Board

This project demonstrates how to generate random numbers using the
OPTIGA™ hardware true random number generator (TRNG) and perform
addition on the host microcontroller.

## Hardware Requirements

- Infineon OPTIGA™ Trust M / OPTIGA™ TPM
- Supported MCU evaluation board
- I2C interface enabled

## Software Requirements

- OPTIGA™ Host Library
- C compiler (ARM-GCC / GCC)
- UART or debugger console for output

## Project Overview

The OPTIGA™ device is used to securely generate random numbers.
The host MCU:
1. Requests random data from OPTIGA™
2. Converts random bytes into integers
3. Adds the generated numbers
4. Prints the result

## File Structure

