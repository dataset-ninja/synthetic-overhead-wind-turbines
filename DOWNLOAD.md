Dataset **Wind Turbines (Synthetic Overhead Images by Duke Dataplus2020)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/l/T/fb/wtQUkb8Z7gNZ7a7HLoCRFFTSqybQJbRdyYWRhPZxagusxC1LCvI0cnk9ZbLSuEHaQKlqiU28WStzugU4ls2Y0ppDuUvqlBhM5adhrhaE4dAAtDkeuQ4GTO5griXv.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbines (Synthetic Overhead Images by Duke Dataplus2020)', dst_path='~/dtools/datasets/Wind Turbines (Synthetic Overhead Images by Duke Dataplus2020).tar')
```
The data in original format can be 🔗[downloaded here](https://figshare.com/ndownloader/files/24118271)