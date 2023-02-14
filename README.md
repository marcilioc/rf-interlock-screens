# RF Interlock Screens

## Description
These screens are for monitoring the interlock faults from RF System of Sirius Accelerator Booster and Storage Ring.

---

## Installation
For the installation, the only requirements are Anaconda, Python and the PyDM library, that can be installed running *`setup.sh`* on the terminal.

    $ ./setup.sh

If everything went right, the terminal will prompt **Finished Installation**.

---

## Usage
Firstly, the created environment must be activated

    $ conda activate rf-interlock-screens

There are two main screens that can lead to all others:
- `bo-screens/interlock_rf_booster.ui`
- `si-screens/interlock_rf_anel.ui`

To run any screen of this repository, type this on terminal:

    $ (rf-interlock-screens) pydm /screen_path/screen_name.ui
