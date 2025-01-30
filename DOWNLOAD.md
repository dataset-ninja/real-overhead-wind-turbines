Dataset **Overhead Imagery of Wind Turbines (by Duke Dataplus2020)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzEwNjRfT3ZlcmhlYWQgSW1hZ2VyeSBvZiBXaW5kIFR1cmJpbmVzIChieSBEdWtlIERhdGFwbHVzMjAyMCkvb3ZlcmhlYWQtaW1hZ2VyeS1vZi13aW5kLXR1cmJpbmVzLShieS1kdWtlLWRhdGFwbHVzMjAyMCktRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiQklDMEVBQkViRU0yUWhjdUVSb0NNUE8ydVRraDNGM1VZWEszZ1lNQnU2VT0ifQ==)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Overhead Imagery of Wind Turbines (by Duke Dataplus2020)', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://figshare.com/ndownloader/files/24121976).