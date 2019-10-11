Datadog Logs CLI
=================


### Prerequisite

```
pipenv install
```

### Usage

```
export DD_API_KEY=xxxxx
export DD_APP_KEY=xxxxx
```

```
pipenv run python -m datadog_logs \
    --query 'service:my-service' \
    --start 2019-10-10T00:00:00 \
    --end 2019-10-11T00:00:00
```
