# Silicon Notebooks

Build open silicon using [Jupyter](https://jupyter.org/) and [Colab](https://colab.research.google.com/) notebooks.

## Notebooks

### Digital Inverter with OpenLane and SKY130 PDK [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chipsalliance/silicon-notebooks/blob/main/digital-inverter-openlane.ipynb)

[digital-inverter-openlane.ipynb](digital-inverter-openlane.ipynb)

Run a simple inverter design thru the [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane/) GDS to RTL flow targeting the [open source SKY130 PDK](https://github.com/google/skywater-pdk/).

![inverter layout](img/inverter.svg)

### Digital Inverter with OpenLane and GF180MCU PDK [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chipsalliance/silicon-notebooks/blob/main/digital-inverter-openlane-gf180mcu.ipynb)

[digital-inverter-openlane-gf180mcu.ipynb](digital-inverter-openlane-gf180mcu.ipynb)

Run a simple inverter design thru the [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane/) GDS to RTL flow targeting the [open source GF180MCU PDK](https://github.com/google/gf180mcu-pdk/).

![inverter layout](img/inverter-gf180mcu.svg)

### Analog Inverter with Magic [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chipsalliance/silicon-notebooks/blob/main/analog-inverter-magic.ipynb)

[analog-inverter-magic.ipynb](analog-inverter-magic.ipynb)

Draw a simple mosfet for the [open source SKY130 PDK](https://github.com/google/skywater-pdk/) using [MAGIC](https://github.com/RTimothyEdwards/magic) and simulate it in an inverter circuit using [PySpice](https://pyspice.fabrice-salvaire.fr/).

![mosfet layout](img/mosfet.png)

### XLS adder with OpenLane [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chipsalliance/silicon-notebooks/blob/main/xls-adder-openlane.ipynb)

[xls-adder-openlane.ipynb](xls-adder-openlane.ipynb)

Run a simple 1-bit adder design using the [XLS](https://google.github.io/xls/) high level synthesis toolkit thru the [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane/) GDS to RTL flow targeting the [open source SKY130 PDK](https://github.com/google/skywater-pdk/).

![adder layout](img/adder.svg)

### XLS workshop with OpenLane [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chipsalliance/silicon-notebooks/blob/main/xls-workshop-openlane.ipynb)

[xls-workshop-openlane.ipynb](xls-workshop-openlane.ipynb)

#### From code to silicon using XLS and OpenLane

- Design your hardware with code using [XLS](https://google.github.io/xls/) high-level synthesis toolkit.
- Run your design thru the [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane/) RTL to GDS toolchain.
- Target the open source [SKY130](https://github.com/google/skywater-pdk/) PDK to manufacture your design using Google's sponsored [OpenMPW shuttle](https://developers.google.com/silicon) program.

![xls layout](img/xls.png)

### Different adder architecture with OpenLane [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/heyshakya/silicon-notebooks/blob/main/adder_implementation.ipynb)

[adder_implementation.ipynb](adder_implementation.ipynb)

Design and Run a **32-bit Sklansky and Han-Carlson adder architecture** through the [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane/) GDS to RTL flow targeting the [open source SKY130 PDK](https://github.com/google/skywater-pdk/).

Reference: This version of the notebook is implemented originally from this [Tweet](https://twitter.com/td_ene/status/1512590193596973062).

![32adder layout](img/32adder_layout.jpg)
