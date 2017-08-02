## Run

```
docker run -it -e "AWS_ACCESS_KEY_ID=[key]" -e "AWS_SECRET_ACCESS_KEY=[secret]" revenuewire/dynamodb-cross-region-replication:latest --sourceRegion [region] --sourceTable [table] --destinationRegion [region] --destinationTable [table]
```