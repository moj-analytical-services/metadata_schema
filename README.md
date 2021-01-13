# metadata_schema

JSON schema for the data engineering team's metadata format.

## Url format

```
https://moj-analytical-services.github.io/metadata_schema/[schema_name]/[version].json
```

* `[schema_name]` the name of the schema you want to reference.
* `[version]` defines the version the schema.

## Schemas

Each sub-heading below is the `schema_name` of a particular schema we curate.

### mojap_metadata

Latest metadata schema for the MoJ's data schemas (using the `mojap-metadata` [package](https://github.com/moj-analytical-services/mojap-metadata)).

### table

The metadata schema for the MoJ's old database tables schemas (using the `etl-manager` [package](https://github.com/moj-analytical-services/etl_manager/)).
