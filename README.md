# Simple Interest Calculator

A simple interest calculator that computes simple interest from user input. It is available as a Python program (`interest.py`) and a Bash script (`simple-interest.sh`).

## Overview

Simple interest is interest calculated only on the original principal amount. This project asks the user for the principal, the rate of interest and the time period, then prints the simple interest.

## Features

- Takes user input for principal, rate of interest and time period
- Calculates simple interest using the standard formula
- Available as a Python program and a Bash script
- Easy to run with no extra dependencies for the Python version

## Input Fields

| Field | Description |
|-------|-------------|
| Principal (P) | The initial amount of money |
| Rate of interest (R) | Annual rate of interest in percent |
| Time period (T) | Time in years |

## Formula

```
Simple Interest (SI) = (P x R x T) / 100
```

## Example

For P = 1000, R = 5 and T = 2:

```
SI = (1000 x 5 x 2) / 100 = 100
```

## Requirements

- Python 3 for `interest.py`
- Bash and `bc` for `simple-interest.sh`

## Installation

```
git clone https://github.com/Lancheba/simple-interest-calculator.git
cd simple-interest-calculator
```

## Usage

Python:

```
python interest.py
```

Bash:

```
bash simple-interest.sh
```

Sample run:

```
Enter principal amount: 1000
Enter rate of interest (%): 5
Enter time period (years): 2
Simple Interest = 100.00
```

## Project Structure

- `README.md` - project details
- `interest.py` - Python simple interest calculator
- `simple-interest.sh` - Bash simple interest calculator
- `LICENSE` - Apache 2.0 license
- `CODE_OF_CONDUCT.md` - community code of conduct
- `CONTRIBUTING.md` - how to contribute

## Contributing

All contributions are welcome. See `CONTRIBUTING.md` for details.

## License

This project is licensed under the Apache License 2.0. See the `LICENSE` file for details.
