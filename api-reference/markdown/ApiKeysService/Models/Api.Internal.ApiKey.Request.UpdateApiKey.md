# Api.Internal.ApiKey.Request.UpdateApiKey
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **id** | **UUID** | Unique identifier for the API key. | [default to null] |
| **value** | **UUID** | The actual value of the API key. | [default to null] |
| **description** | **String** | A description for the API key to help identify it. | [default to null] |
| **owner** | [**Api.Internal.ApiKey.Common.Owner**](Api.Internal.ApiKey.Common.Owner.md) |  | [default to null] |
| **issuer** | [**Api.Internal.ApiKey.Common.Issuer**](Api.Internal.ApiKey.Common.Issuer.md) |  | [default to null] |
| **expires\_at** | **Long** | The date and time when the API key expires, in timestamp format. | [default to null] |
| **enabled** | **Boolean** | A true/false value indicating whether the API key is enabled. | [default to null] |
| **permissions** | [**Api.Internal.ApiKey.Common.Permissions**](Api.Internal.ApiKey.Common.Permissions.md) |  | [default to null] |
| **scopes** | **List** | Scopes associated with the API key. | [optional] [default to null] |
| **quota** | [**Api.Internal.ApiKey.Common.QuotaLedger**](Api.Internal.ApiKey.Common.QuotaLedger.md) | Only when this is a main key | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

