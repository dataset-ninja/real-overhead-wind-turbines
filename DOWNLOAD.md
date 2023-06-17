Dataset **Wind Turbines 3** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/x/D/6p/4pZUeB8ruNTokW6cwidVED2449D1HMX91QoTJP4CiHgLoWzHKvZ2dn4rBEb8kmV3h2RCiwsF7YaWcKFryONbwJ8Ip9EU8tIbhyLXp6P0s8TJugrGnPQGru9L88Ct.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbines 3', dst_path='~/dtools/datasets/Wind Turbines 3.tar')
```
The data in original format can be 🔗[downloaded here](https://figshare.com/ndownloader/files/24121976)