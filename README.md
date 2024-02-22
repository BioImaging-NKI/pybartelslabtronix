# Python automation for the Bartels Mikrotechnik labtronix micropump driver
## List of commands
| Command     | Description |
|-------------| -------------------------------------------------- |
| bon         | turns the micropump on |
| boff        | turns the micropump off |
| F(1-300)    | sets the required frequency between 1 and 300 Hz |
| F100        | here as an example 100 Hz. |
| A(1-250)    | sets the required frequency between 1 and 250 Vpp |
| A100        | here as an example 100 Vpp |
| MS          | sets signal form modus (S)ine |
| MR          | sets signal form modus (R)ectangular |
| MC          | sets signal form modus SRS |
| (enter key) | displays present settings of the control unit |

## COM settings
* Bits per second: 9600
* Data bits: 8
* Parity: none
* Stop bits: 1
* Flow control: none

## Installation
`pip install pybartelslabtronix`

## Usage
[See Jupyter Notebook for example usage.](notebooks/Test_Bartels_Labtronix.ipynb)