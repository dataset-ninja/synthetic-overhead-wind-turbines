Dataset **Wind Turbines (by Duke Dataplus2020)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/j/J/4g/J6YMj0ULCgNCKI7LCc6KrcSm7c6I6vVIkb1RulygM1rq9XV5kKbCaQ8aD98J9r7pnkm1JDO9mctmpfqlQkjUe3T5d1P1fjN2Nmgnc0w9gZ2gZEMvnVk8WRsCBOUO.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbines (by Duke Dataplus2020)', dst_path='~/dtools/datasets/Wind Turbines (by Duke Dataplus2020).tar')
```
The data in original format can be 🔗[downloaded here](https://figshare.com/ndownloader/files/24118271)