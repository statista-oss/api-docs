# Api.Internal.ApiKey.Response.ApiKey
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **id** | **UUID** | Unique identifier for the API key. | [default to null] |
| **value** | **UUID** | The actual value of the API key. | [default to null] |
| **description** | **String** | A description for the API key to help identify it. | [default to null] |
| **owner** | [**Api.Internal.ApiKey.Common.Owner**](Api.Internal.ApiKey.Common.Owner.md) |  | [default to null] |
| **issuer** | [**Api.Internal.ApiKey.Common.Issuer**](Api.Internal.ApiKey.Common.Issuer.md) |  | [default to null] |
| **created\_at** | **Long** | The date and time when the API key was created, in timestamp format. | [default to null] |
| **valid\_at** | **Long** | The date and time when the API key starts being valid, in timestamp format. | [default to null] |
| **last\_used\_at** | **Long** | The date and time when the API key was last used, in timestamp format. | [default to null] |
| **expires\_at** | **Long** | The date and time when the API key expires, in timestamp format. | [default to null] |
| **disabled\_at** | **Long** | The date and time when the API key was disabled, in timestamp format. Null if the key is still active. | [optional] [default to null] |
| **ttl** | **Long** | The date and time when the API key will be automatically disabled, in timestamp format. Null if the key does not have an automatic disable date. | [default to null] |
| **enabled** | **Boolean** | A true/false value indicating whether the API key is enabled. | [default to null] |
| **permissions** | [**Api.Internal.ApiKey.Common.Permissions**](Api.Internal.ApiKey.Common.Permissions.md) |  | [default to null] |
| **scopes** | **List** | Scopes associated with the API key. | [default to null] |
| **quota** | [**Api.Internal.ApiKey.Common.QuotaLedger**](Api.Internal.ApiKey.Common.QuotaLedger.md) |  | [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

