# Summary

This module allows for interacting with the HubSpot API (e.g. creating/listing/updating Deals) via native PowerShell cmdlets.

Please note that this module has limited functionality and does not implement all API functionality by design. It was designed with the intention of being able to automate basic CRUD operations for common objects.

Link to Powershell Gallery page for this module: https://www.powershellgallery.com/packages/HubSpotApi/

# Authentication

Before you can use any other cmdlets, you need to run the 'Connect-HubSpotApi' cmdlet to authenticate to your instance.

The API key is obtained from creating a [Private App](https://developers.hubspot.com/docs/guides/apps/private-apps/overview).

```
Connect-HubSpotApi -ApiKey "SuperSecretToken"
```

Once authenticated, you can run other cmdlets.

# Examples

This module includes [Comment-based help](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_comment_based_help?view=powershell-7.5)

To see examples and information about cmdlets, use ```Get-Help <cmdlet>```, for example ```Get-Help Get-HubSpotContact```

# License

See the [LICENSE.txt](https://github.com/mister-dj/HubSpotApi/blob/main/LICENSE) file in the root of this repository.