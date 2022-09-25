# Silicon Notebooks

Build open silicon using [Jupyter](https://jupyter.org/) and [Colab](https://colab.research.google.com/) notebooks.

## Notebooks

### Digital Inverter with OpenLane [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chipsalliance/silicon-notebooks/blob/main/digital-inverter-openlane.ipynb)

[digital-inverter-openlane.ipynb](digital-inverter-openlane.ipynb)

Run a simple inverter design thru the [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane/) GDS to RTL flow targeting the [open source SKY130 PDK](https://github.com/google/skywater-pdk/).

![inverter layout](img/inverter.svg)

### Analog Inverter with Magic [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chipsalliance/silicon-notebooks/blob/main/analog-inverter-magic.ipynb)

[analog-inverter-magic.ipynb](analog-inverter-magic.ipynb)

Draw a simple mosfet for the [open source SKY130 PDK](https://github.com/google/skywater-pdk/) using [MAGIC](https://github.com/RTimothyEdwards/magic) and simulate it in an inverter circuit using [PySpice](https://pyspice.fabrice-salvaire.fr/).

![mosfet layout](img/mosfet.png)

### XLS adder with OpenLane [![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chipsalliance/silicon-notebooks/blob/main/xls-adder-openlane.ipynb)

[xls-adder-openlane.ipynb](xls-adder-openlane.ipynb)

Run a simple 1-bit adder design using the [XLS](https://google.github.io/xls/) high level synthesis toolkit thru the [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane/) GDS to RTL flow targeting the [open source SKY130 PDK](https://github.com/google/skywater-pdk/).

![adder synthesis](img/adder.jpg)
