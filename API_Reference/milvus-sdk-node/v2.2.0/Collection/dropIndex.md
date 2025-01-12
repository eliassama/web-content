# dropIndex()

This method drops the index and its corresponding index file in the collection.

## Invocation

```javascript
new milvusClient(MILUVS_ADDRESS).indexManager.dropIndex(DropIndexReq);
```

## Parameter

### DropIndexReq

| Parameter       | Description                                                                            | Type   | Required |
| --------------- | -------------------------------------------------------------------------------------- | ------ | -------- |
| collection_name | Collection name                                                                        | String | True     |
| field_name      | Field name                                                                             | String | True     |
| index_name      | Index name                                                                             | String | False    |
| timeout         | An optional duration of time in millisecond to allow for the RPC. Default is undefined | Number | False    |

## Example

```javascript
new milvusClient(MILUVS_ADDRESS).indexManager.dropIndex({
  collection_name: "my_collection",
});
```

## Return

```javascript
// dropIndex return
```
