# Api.Internal.ApiKey.Request.CreateApiKey
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **description** | **String** | A description for the API key to help identify it. | [default to null] |
| **owner** | [**Api.Internal.ApiKey.Common.Owner**](Api.Internal.ApiKey.Common.Owner.md) |  | [default to null] |
| **issuer** | [**Api.Internal.ApiKey.Common.Issuer**](Api.Internal.ApiKey.Common.Issuer.md) |  | [default to null] |
| **valid\_at** | **Long** | The date and time when the API key starts being valid, in timestamp format. | [default to null] |
| **expires\_at** | **Long** | The date and time when the API key expires, in timestamp format. | [default to null] |
| **permissions** | [**Api.Internal.ApiKey.Common.Permissions**](Api.Internal.ApiKey.Common.Permissions.md) |  | [default to null] |
| **scopes** | **List** | Scopes associated with the API key. | [default to null] |
| **parent** | **String** | When specified, this Key will be a member key and inherit the quota from its parent | [optional] [default to null] |
| **quota** | [**Api.Internal.ApiKey.Common.QuotaLedger**](Api.Internal.ApiKey.Common.QuotaLedger.md) | When NOT specified, this Key will be a member key and inherit the quota from its parent. See: parent | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

