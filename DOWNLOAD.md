Dataset **California and Arizona Wind Turbines (by Duke Dataplus2020)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/p/2/jp/s833fT1GhP7xdkJ0lQk5ZVicAqDQCG2OhlgwYTlAkoom1Xi6DjOxOdGYNPaBUPFnTUtOiqYM2NiyGeKfjjVl8dhq9Dwpk9Uu6rscilLoGF3vN0CcR6fTkFfA02NU.tar)

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