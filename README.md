This example demonstrates you can see how to construct and add a mapping to Elasticsearch by:

- JSON file
- XContent

The mapping itself is quite simplistic:

```
{
    "user": {
        "properties": {
            "name": {
                "type": "string",
                "index": "not_analyzed"
            },
            "age": {
                "type": "long"
            },
            "address": {
                "type": "string",
                "index": "not_analyzed"
            }
        }
    }
}
```