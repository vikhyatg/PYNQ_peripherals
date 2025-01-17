# Drivers and notebooks for PYNQ Grove peripheral modules

This repository contains drivers for Arduino, PMOD, Grove and Raspberry PI
peripherals connected to an IOP. Each peripheral driver comes with Jupyter
notebooks which show how to use it. To install the notebooks run

```sh
sudo pip install git+https://github.com/Xilinx/PYNQ_peripherals.git
sudo pynq get-notebooks pynq_peripherals -p $PYNQ_JUPYTER_NOTEBOOKS
```

in your jupyter-notebooks folder.

## Contributing

See the CONTRIBUTING file for details on how to contribute new peripheral
drivers. We are actively welcoming contributions.


Copyright (C) 2021 Xilinx, Inc

SPDX-License-Identifier: BSD-3-Clause
