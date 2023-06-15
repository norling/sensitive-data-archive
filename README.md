# sda

`SDA` contains all components of [NeIC Sensitive Data Archive](https://neic-sda.readthedocs.io/en/latest/) It can be used as part of a [Federated EGA](https://ega-archive.org/federated) or as a isolated Sensitive Data Archive.

For more information about the different components see the readme files in the respecive folders.

## Deployment

The sensitive data archive (sda) is most easily deployed with helm. To install
the system, install the dependencies, edit the values.yaml file, and run:
```bash
helm install <name> .
```

