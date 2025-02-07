# Keyban Library of Earthfile

## Earthfiles

### Velero

Run the target

```bash
earthly ./velero+release --version v1.15.2
```

Import the earthfile

```bash
IMPORT https://github.com/keyban-io/velero/Earthfile AS velero
```

Copy the binary

```bash
COPY velero+release /path/to/velero --version v1.15.2
```
