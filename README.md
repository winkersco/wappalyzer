# Wappalyzer

Wappalyzer is a Python script for generating Wappalyzer results to file.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install dependencies.

```bash
pip3 install -r requirements.txt
```

## Usage

```
usage: wappalyzer.py [-h] -t TARGET [-o OUTPUT_FILEPATH]

Wappalyzer

optional arguments:
  -h, --help            show this help message and exit
  -t TARGET, --target TARGET
                        target that wappalyzer scan technologies on it.
  -o OUTPUT_FILEPATH, --output OUTPUT_FILEPATH
                        file to save results. default:"wappalyzer.json"
```

## Example
```bash
python3 wappalyzer.py -t https://example.com output.json
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU](https://choosealicense.com/licenses/gpl-3.0/)