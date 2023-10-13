# telecon

<div align="left">
    <a href="https://speakeasyapi.dev/"><img src="https://custom-icon-badges.demolab.com/badge/-Built%20By%20Speakeasy-212015?style=for-the-badge&logoColor=FBE331&logo=speakeasy&labelColor=545454" /></a>
    <a href="https://github.com/speakeasy-sdks/test-sample-sdk-54.git/actions"><img src="https://img.shields.io/github/actions/workflow/status/speakeasy-sdks/test-sample-sdk-54/speakeasy_sdk_generation.yml?style=for-the-badge" /></a>
    
</div>

<!-- Start SDK Installation -->
# SDK Installation

## NPM

```bash
npm add https://github.com/speakeasy-sdks/test-sample-sdk-54
```

## Yarn

```bash
yarn add https://github.com/speakeasy-sdks/test-sample-sdk-54
```
<!-- End SDK Installation -->

## SDK Example Usage
<!-- Start SDK Example Usage -->


```typescript
import { Telecon } from "telecon";

(async () => {
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
<!-- End SDK Example Usage -->

<!-- Start SDK Available Operations -->
# Available Resources and Operations


## [workspace](docs/sdks/workspace/README.md)

* [updateWorkspace](docs/sdks/workspace/README.md#updateworkspace) - update workspace
<!-- End SDK Available Operations -->

<!-- Start Dev Containers -->



<!-- End Dev Containers -->

<!-- Placeholder for Future Speakeasy SDK Sections -->

# Development

## Maturity

This SDK is in beta, and there may be breaking changes between versions without a major version update. Therefore, we recommend pinning usage
to a specific package version. This way, you can install the same version each time without breaking changes unless you are intentionally
looking for the latest version.

## Contributions

While we value open-source contributions to this SDK, this library is generated programmatically.
Feel free to open a PR or a Github issue as a proof of concept and we'll do our best to include it in a future release!

### SDK Created by [Speakeasy](https://docs.speakeasyapi.dev/docs/using-speakeasy/client-sdks)
