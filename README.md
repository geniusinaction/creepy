# creepy 
creep inversion with Python

Uses two InSAR datasets from different viewing geometries, in ascending and descending mode, and solves for strike-perpendicular profile offsets and strike-parallel creep rate. Requires a kmz/kml file with the digitized fault strike, plus line-of-sight velocity, pointing azimuth and incidence angle information for both datasets in GMT grd format. Hopefully the notebook is somewhat self-explanatory.

Dependencies:
- pygmt
- matplotlib
- numpy
- [interparc.py](https://github.com/rsyi/python-lib/blob/master/interparc.py)
