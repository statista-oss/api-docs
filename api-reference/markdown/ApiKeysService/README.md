# Documentation for Internal Statista API Key management

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *https://apiv2.globalsearch.prod.aws.statista.com*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *DefaultApi* | [**apiKeysAssignToMainKey**](Apis/DefaultApi.md#apiKeysAssignToMainKey) | **POST** /v1/management/api-keys/{id}/assign-to-main-key |  |
*DefaultApi* | [**apiKeysCreate**](Apis/DefaultApi.md#apiKeysCreate) | **POST** /v1/management/api-keys/create |  |
*DefaultApi* | [**apiKeysGet**](Apis/DefaultApi.md#apiKeysGet) | **GET** /v1/management/api-keys/{id} |  |
*DefaultApi* | [**apiKeysList**](Apis/DefaultApi.md#apiKeysList) | **GET** /v1/management/api-keys |  |
*DefaultApi* | [**apiKeysUpdate**](Apis/DefaultApi.md#apiKeysUpdate) | **PUT** /v1/management/api-keys/update |  |
*DefaultApi* | [**scopesCreate**](Apis/DefaultApi.md#scopesCreate) | **POST** /v1/management/scopes/create |  |
*DefaultApi* | [**scopesGet**](Apis/DefaultApi.md#scopesGet) | **GET** /v1/management/scopes/{id} |  |
*DefaultApi* | [**scopesList**](Apis/DefaultApi.md#scopesList) | **GET** /v1/management/scopes |  |
*DefaultApi* | [**scopesUpdate**](Apis/DefaultApi.md#scopesUpdate) | **PUT** /v1/management/scopes/update |  |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [Api.Internal.ApiKey.Common.Issuer](./Models/Api.Internal.ApiKey.Common.Issuer.md)
 - [Api.Internal.ApiKey.Common.Owner](./Models/Api.Internal.ApiKey.Common.Owner.md)
 - [Api.Internal.ApiKey.Common.Permissions](./Models/Api.Internal.ApiKey.Common.Permissions.md)
 - [Api.Internal.ApiKey.Common.QuotaLedger](./Models/Api.Internal.ApiKey.Common.QuotaLedger.md)
 - [Api.Internal.ApiKey.Request.AssignToMainKey](./Models/Api.Internal.ApiKey.Request.AssignToMainKey.md)
 - [Api.Internal.ApiKey.Request.CreateApiKey](./Models/Api.Internal.ApiKey.Request.CreateApiKey.md)
 - [Api.Internal.ApiKey.Request.UpdateApiKey](./Models/Api.Internal.ApiKey.Request.UpdateApiKey.md)
 - [Api.Internal.ApiKey.Response.ApiKey](./Models/Api.Internal.ApiKey.Response.ApiKey.md)
 - [Api.Internal.KeyScopes.Common.Endpoint](./Models/Api.Internal.KeyScopes.Common.Endpoint.md)
 - [Api.Internal.KeyScopes.Request.WriteScopes](./Models/Api.Internal.KeyScopes.Request.WriteScopes.md)
 - [Api.Internal.KeyScopes.Response.Scopes](./Models/Api.Internal.KeyScopes.Response.Scopes.md)
 - [ApiKeys_create_201_response](./Models/ApiKeys_create_201_response.md)
 - [ApiKeys_create_request](./Models/ApiKeys_create_request.md)
 - [ApiKeys_update_request](./Models/ApiKeys_update_request.md)
 - [Api_Internal_ApiKey_Common_QuotaLedger_day](./Models/Api_Internal_ApiKey_Common_QuotaLedger_day.md)
 - [Api_Internal_ApiKey_Common_QuotaLedger_total](./Models/Api_Internal_ApiKey_Common_QuotaLedger_total.md)
 - [Api_Internal_ApiKey_Common_QuotaLedger_year](./Models/Api_Internal_ApiKey_Common_QuotaLedger_year.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="ApiKeyAuth"></a>
### ApiKeyAuth

- **Type**: API key
- **API key parameter name**: x-api-key
- **Location**: HTTP header

