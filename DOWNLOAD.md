Dataset **California and Arizona Wind Turbines (by Duke Dataplus2020)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/a/B/Ql/beg1ZldD5epeCJnIdUhEj8RoiAO7ZV9o1ilGdSnU38KqzrWOvpoxtL3ZN7e4uGmq6NGshQmaOtnrSGjN7hRRkKk1egFFRWP3z5Fm09LkXZkkWu2RoCzrKQOGlANe.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='California and Arizona Wind Turbines (by Duke Dataplus2020)', dst_path='~/dtools/datasets/California and Arizona Wind Turbines (by Duke Dataplus2020).tar')
```
The data in original format can be 🔗[downloaded here](https://figshare.com/ndownloader/files/24118271)