# kProcessor

## Installation  

### Requirements

|Dependency|Installation |
|--|--|
| g++ | `sudo apt-get install g++` |
| cmake | `sudo apt-get install cmake` |
| zlip | `sudo apt install zlib1g-dev` |
| bzlip | `sudo apt-get install libghc-bzlib-dev` |
| python3-dev | `sudo apt-get install python3-dev` |
| distutils | `sudo apt-get install python3-distutils` |
| swig | `sudo apt-get install swig` |

### Clone

```bash
git clone --recursive --branch development https://github.com/dib-lab/kProcessor.git kProcessor
cd kProcessor
```

### Build kProcessorLib

```bash
mkdir build
cd build/
cmake ..
make
cd ..
```

### Install kProcessor Python Package

```bash
python3 setup.py install
```

### Optional (Build wheel package)

```bash
python3 setup.py bdist_wheel
```
