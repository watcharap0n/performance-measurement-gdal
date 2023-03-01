# Perfomance Measurement GDAL 
### Convert TIF to MBTILES & VECTOR

You can follow installation below here.

## Installation dependencies (Ubuntu)

```bash
$ sudo apt-get update
$ sudo apt install -y python3-pip
$ sudo apt-get install -y build-essential gdal-bin libgdal-dev
 
```

## Set the GDAL configuration

```bash
$ export CPLUS_INCLUDE_PATH=/usr/include/gdal
$ export C_INCLUDE_PATH=/usr/include/gdal

```

## Installation package (Python)

```bash
$ pip install -r requirements.txt

# another way 
$ pip install GDAL
$ pip install jupyterlab

```

## Run jupyter lab on (Ubuntu)

```bash
$ jupyter lab --ip 0.0.0.0

```
you can access url your (public ip):8888?lab={token}


## Code python on jupyter

```python
from osgeo import gdal

gdal.__version__

```