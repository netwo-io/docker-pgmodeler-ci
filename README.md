

# Usage

```bash
PG_MODELER_CLI=docker run -v $(pwd):/some/path netwo-io/pgmodeler-cli pgmodeler-cli -p 5432 -u $SUPER_USER --passwd $SUPER_USER_PASSWORD --host=localhost
$PG_MODELER_CLI --ignore-errors --input-db db0 --import-db -of /some/path/some.dbm
$PG_MODELER_CLI --input /some/path/some.dbm --export-to-png --output /some/path/some.png
```

# Inspiration

Largely inspired by https://github.com/GeertJohan/docker-pgmodeler-cli
