<!-- Start SDK Example Usage -->
```typescript
import { Telecon } from "telecon";

(async () => {
    const sdk = new Telecon();

    const res = await sdk.workspace.updateWorkspace({
        id: "<ID>",
        name: "string",
    });

    if (res.statusCode == 200) {
        // handle response
    }
})();

```
<!-- End SDK Example Usage -->