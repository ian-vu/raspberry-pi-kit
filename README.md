## Setup

0. Create a virtual environment

```bash
python3 -m venv .venv
```

1. Activate the virtual environment

```bash
source .venv/bin/activate
```

2. Install the required packages

```bash
pip install -r requirements.txt
```

## How to run python files

```bash
sudo python <path_to_python_file>
```

_sudo is required for the library gpiozero to be able to access the GPIO pins with default pin factory_
