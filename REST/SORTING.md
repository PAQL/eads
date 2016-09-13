# REST API Sorting

## Summary


## Sorting



### Parameters

Name | Type | Description
---- | ---- | -----------
sort | string | Specifies that the query results should be sorted by the attribute value.

> The sort parameter will not be supported for POST, PUT, DELETE operations. Only GET list resources will support sort

### Example

```
https://[BASE_URL]/api/v1/[RESOURCE]?sort=createdAt,-name
```

### Default Assumptions

* Strings are sorted in ascending alphabetical order in en-US locale.
* Numbers are sorted in ascending numeric order.
* Dates are sorted in ascending order by date.