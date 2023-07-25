Dataset **Wind Turbines (Overhead Imagery by Duke Dataplus2020)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/9/6/td/DCkGLdf0QdTq5NBaOzvWmvtEXkcF1uIvHJ7mUB3FleXqEmLyuE6EZHqTAShjWAI1684Cbhcc03wvRfdWebenipNOb84sHwbzB7QLcqX9GCeiN5Ok4zRVEGZYolar.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbines (Overhead Imagery by Duke Dataplus2020)', dst_path='~/dtools/datasets/Wind Turbines (Overhead Imagery by Duke Dataplus2020).tar')
```
The data in original format can be 🔗[downloaded here](https://figshare.com/ndownloader/files/24121976)