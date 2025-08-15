Dataset **California and Arizona Wind Turbines (by Duke Dataplus2020)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMTA2M19DYWxpZm9ybmlhIGFuZCBBcml6b25hIFdpbmQgVHVyYmluZXMgKGJ5IER1a2UgRGF0YXBsdXMyMDIwKS9jYWxpZm9ybmlhLWFuZC1hcml6b25hLXdpbmQtdHVyYmluZXMtKGJ5LWR1a2UtZGF0YXBsdXMyMDIwKS1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICIzVGExTUJUOFFUdUxQeHQrWCs5SDlQVExSTWRGMEVmRjI2M3RXSXROU1JVPSJ9?response-content-disposition=attachment%3B%20filename%3D%22california-and-arizona-wind-turbines-%28by-duke-dataplus2020%29-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='California and Arizona Wind Turbines (by Duke Dataplus2020)', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://figshare.com/ndownloader/files/24118271).