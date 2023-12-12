<!-- Start SDK Example Usage [usage] -->
```typescript
import { Telecon } from "telecon";

async function run() {
    const sdk = new Telecon();

    const res = await sdk.workspace.updateWorkspace({
        id: "<ID>",
        name: "string",
    });

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->