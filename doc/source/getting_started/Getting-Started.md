Getting Started
===============

1. [Register at NASA Earthdata and add NSIDC applications](./NASA-Earthdata.md)
2. Retrieve `ATL03_20191115042423_07520512_002_01.h5` from NSIDC   
```bash
python nsidc_icesat2_sync.py --user=<username> --directory=<path_to_directory> \
    --subdirectory=2019.11.15 --release=002 --version=01 --track=752 \
    --granule=12 --flatten --mode=0o775 ATL03
```
3. Run Jupyter notebook `Read ICESat-2 ATL03.ipynb` to learn about ICESat-2 and ATL03  