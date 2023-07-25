Dataset **Overhead Imagery of Wind Turbines (by Duke Dataplus2020)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/R/j/KA/fkBUGCoQPjbxcqx9YwmmluhFczb1XjMrHmzyVBDfxcssrtsKNfCRdGZuV6t1ftyEGTmPuDPWLlDNOBdLOs8kLUKXLqdhUi0tyt9Hbkqq6E0LFW68x0fQg6VGxteh.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Overhead Imagery of Wind Turbines (by Duke Dataplus2020)', dst_path='~/dtools/datasets/Overhead Imagery of Wind Turbines (by Duke Dataplus2020).tar')
```
The data in original format can be 🔗[downloaded here](https://figshare.com/ndownloader/files/24121976)