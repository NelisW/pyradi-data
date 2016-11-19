# pyradi Porting Status

pyradi was originally developed under Python 2.7.
This document summarises the conversion to support both 2.7 and 3.5 Python versions.

The work entails comparing the output files (text and images) of the various scripts under both Python versions. If the results compare favourably the task is considered complete.  Exact matches are not feasible, because of small differences in results. For example, Python 2.7 reports numpy shapes as Long integer, whereas Python 3.5 reports shapes as integers.  Also, sometimes the order of execution or plotting differ between the two versions.


## 201611 Porting programme


| File | Status |
|---|:---:|
|`ry3dnoise.py`|Complete|
|`rychroma.py`|Complete|
|`rydetector.py`|Complete|
|`ryfiles.py`|Complete|
|`rylookup.py`|Complete|
|`rymodtran.py`|Complete|
|`rypflux.py`|Complete|
|`ryplanck.py`|Complete|
|`ryplot.py`|Complete|
|`ryplotspherical.py`|Stay 2.7|
|`ryprob.py`|Complete|
|`ryptw.py`|Complete|
|`rystare.py`|Complete|
|`ryutils.py`|Complete|
|`_cleanClutter.py`|Complete|
|`__init__.py`|Complete|
