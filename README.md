# Pixy2 Driver Library

A Python driver library for the Pixy2

# Installation

You first have to install the I2C driver modules. For that, you have to run:
```bash
curl -kL dexterindustries.com/update_rfrtools | bash -s -- --install-python-package --use-python3-exe-too
```
Valid at the given time with this [commit hash](https://github.com/DexterInd/RFR_Tools/commit/2e47128a0ba9a3c36623492525099b52d14fb5b7) from RFR_Tools, which is the repo that goes at the center of the above command.

After having installed the dependencies, go on an install the actual pixy2 driver library.
```bash
pip install git+https://github.com/RobertLucian/pixy2.git
```

To run this in editable mode, clone the repo  and run the following sequence of commands.
```bash
virtualenv -p python .env
source .venv/bin/activate
pip install --editable .
```