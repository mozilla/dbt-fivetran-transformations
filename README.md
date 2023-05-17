# dbt-fivetran-transformations

Project used to perform support dbt transformations using Fivetran. See the [official Fivetran docs](https://fivetran.com/docs/transformations/dbt) for more information.

## Transformations

### apple_search_ads (package)

We use existing DBT model definitions for apple_search_ads found inside [this](https://github.com/fivetran/dbt_apple_search_ads/tree/main) package.

This enables us to shape the data in more analysis friendly way as we ingest it, prior to it becoming available inside BigQuery to avoid us to have to define and schedule these transformations downstream.