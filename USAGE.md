<!-- Start SDK Example Usage [usage] -->
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
<!-- End SDK Example Usage [usage] -->