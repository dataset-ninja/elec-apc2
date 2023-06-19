Please visit dataset [homepage](https://universe.roboflow.com/gvt/elec-apc2) to download the data. 

Afterward, you have the option to download it in the universal supervisely format by utilizing the *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Elec APC2', dst_path='~/dtools/datasets/Elec APC2.tar')
```
