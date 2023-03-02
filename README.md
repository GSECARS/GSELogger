<h1 align="center">GSELogger</h1>

GSELogger is a package that simplifies application logging to a file. Additional ways for logging will be added in
the future (console logging, log streaming to a PyQt widget etc.)

## Installation

GSELogger is tested only using Python 3.10 and higher. In some cases, lower versions are also accepted, but
version 3.10 or higher is recommended for best compatibility. See the full [requirements list]
for the GSELogger package.

<br />

#### <u>PyPI</u>
To install from PyPI use:
````
pip install gselogger
````
<br />

#### <u>Source</u>
To install from source first download the project from the package 
[releases](https://github.com/GSECARS/GSELogger/releases) 
or use: 
````
git clone https://github.com/GSECARS/GSELogger.git
````
Move into the project directory: 
````
cd GSELogger
````
Install using pip: 
````
pip install .
````

<br />

#### <u>Requirements</u>
1. Python >= 3.10

<br />

## Example usage
```
from gselogger import LoggerModel

logger = LoggerModel(app_name="MyApp")
logger.info(message="Information Message")
logger.warning(message="Warning Message", exception_type="Warning Exception Name")
logger.warning(message="Error Message", exception_type="Error Exception Name")
logger.warning(message="Critical Message", exception_type="Critical Exception Name")
```

<br />

## License

GSELogger is part of the GSECARS organization and is distributed under the GNU General Public License version 3. 
You should have received a copy of the GNU General Public License along with this program.  If not, see 
<https://www.gnu.org/licenses/>.

<br />

[Christofanis Skordas](mailto:skordasc@uchicago.edu) - Last updated: 02-Mar-2023