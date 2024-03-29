# Workspace
(*workspace*)

### Available Operations

* [updateWorkspace](#updateworkspace) - update workspace

## updateWorkspace

update workspace

### Example Usage

```typescript
import { Telecon } from "telecon";

async function run() {
  const sdk = new Telecon();

  const res = await sdk.workspace.updateWorkspace({
    id: "<id>",
    name: "<value>",
  });

  if (res.statusCode == 200) {
    // handle response
  }
}

run();
```

### Parameters

| Parameter                                                                                | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `request`                                                                                | [shared.DtoUpdateWorkspaceRequest](../../sdk/models/shared/dtoupdateworkspacerequest.md) | :heavy_check_mark:                                                                       | The request object to use for the request.                                               |
| `config`                                                                                 | [AxiosRequestConfig](https://axios-http.com/docs/req_config)                             | :heavy_minus_sign:                                                                       | Available config options for making requests.                                            |


### Response

**Promise<[operations.UpdateWorkspaceResponse](../../sdk/models/operations/updateworkspaceresponse.md)>**
### Errors

| Error Object    | Status Code     | Content Type    |
| --------------- | --------------- | --------------- |
| errors.SDKError | 4xx-5xx         | */*             |
