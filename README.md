# Fork version to be used for updating Terabee **"follow me 2"** devices

## Installation
**Note:** Do not use the `--user` parameter when running `setup.py` script on Windows.
```bash
pip install -r requirements-dev.txt
python setup.py install --user
```

## Usage
```bash
nrfutil dfu usb-serial -pkg <firmware.zip> -p <COM_PORT>
```
### Example linux
```bash
nrfutil dfu usb-serial -pkg firmware.zip -p /dev/ttyUSB0
```

___
___
___
# nRF Util

[![Latest version](https://img.shields.io/pypi/v/nrfutil.svg)](https://pypi.python.org/pypi/nrfutil)
[![License](https://img.shields.io/pypi/l/nrfutil.svg)](https://pypi.python.org/pypi/nrfutil)
[![Build Status](https://dev.azure.com/NordicSemiconductor/Wayland/_apis/build/status/pc-nrfutil?branchName=master)](https://dev.azure.com/NordicSemiconductor/Wayland/_build?definitionId=30)

nRF Util is a Python package and command-line utility that supports Device Firmware Updates (DFU) and cryptographic functionality.

![screenshot](screenshot.gif)

## Documentation

See the [InfoCenter](https://infocenter.nordicsemi.com/topic/ug_nrfutil/UG/nrfutil/nrfutil_intro.html) pages for information on how to install and use nRF Util.

## Feedback

Please report issues on the [DevZone](https://devzone.nordicsemi.com) portal.

## Contributing

Feel free to propose changes by creating a pull request.

If you plan to make any non-trivial changes, please start out small and ask seek an agreement before putting too much work in it. A pull request can be declined if it does not fit well within the current product roadmap.

In order to accept your pull request, we need you to sign our Contributor License Agreement (CLA). You will see instructions for doing this after having submitted your first pull request.

## License

See the [LICENSE](LICENSE) file for details.
