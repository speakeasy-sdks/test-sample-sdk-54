# Workspace
(*workspace*)

### Available Operations

* [updateWorkspace](#updateworkspace) - update workspace

## updateWorkspace

update workspace

### Example Usage

```typescript
import { Telecon } from "telecon";

(async() => {
  const sdk = new Telecon();

  const res = await sdk.workspace.updateWorkspace({
    id: "<ID>",
    name: "up South",
  });

  if (res.statusCode == 200) {
    // handle response
  }
})();
```

### Parameters

| Parameter                                                                            | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `request`                                                                            | [shared.DtoUpdateWorkspaceRequest](../../models/shared/dtoupdateworkspacerequest.md) | :heavy_check_mark:                                                                   | The request object to use for the request.                                           |
| `config`                                                                             | [AxiosRequestConfig](https://axios-http.com/docs/req_config)                         | :heavy_minus_sign:                                                                   | Available config options for making requests.                                        |


### Response

**Promise<[operations.UpdateWorkspaceResponse](../../models/operations/updateworkspaceresponse.md)>**
