Dataset **Wind Turbines 2** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/m/V/HX/X0AtA4zUfwvDQ8dAjTA0wGtNhbYxykujC6uuN37Exp5t7hvzJ3LN2Zhk50JX8UQhCgRj8lrXSXvo9OltytS8bpnb9YlRORafzPfpGmIbyYKMWlBPfymp3HIt0U6h.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbines 2', dst_path='~/dtools/datasets/Wind Turbines 2.tar')
```
The data in original format can be 🔗[downloaded here](https://figshare.com/ndownloader/files/24118271)