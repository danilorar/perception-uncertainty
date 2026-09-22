#### Setup

1. Open a terminal and run:

```bash
git clone --recurse-submodules https://github.com/danilorar/perception-uncertainty.git
cd perception-uncertainty
```

2. Install Python dependencies:

**Windows:**
```bat
py -m venv .venv
.venv\Scripts\activate.bat
python -m pip install -r requirements.txt
```

**macOS/Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

3. Download the **demo package for Windows or macOS** from [esmini v3.8.1](https://github.com/esmini/esmini/releases/tag/v3.8.1). Extract it and copy `bin`, `resources`, and `config.yml` into the project's `esmini-demo` folder.
