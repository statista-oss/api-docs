# Documentation for Internal Statista API Key management

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *https://internal.globalsearch.prod.aws.statista.com*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *DefaultApi* | [**apiKeysAssignApiKeysToMainKey**](Apis/DefaultApi.md#apiKeysAssignApiKeysToMainKey) | **POST** /v1/management/api-keys/{id}/assign-to-main-key |  |
*DefaultApi* | [**apiKeysCreateNewApiKey**](Apis/DefaultApi.md#apiKeysCreateNewApiKey) | **POST** /v1/management/api-keys/create |  |
*DefaultApi* | [**apiKeysGetApiKeysById**](Apis/DefaultApi.md#apiKeysGetApiKeysById) | **GET** /v1/management/api-keys/{id} |  |
*DefaultApi* | [**apiKeysListApiKeys**](Apis/DefaultApi.md#apiKeysListApiKeys) | **GET** /v1/management/api-keys |  |
*DefaultApi* | [**apiKeysUpdateApiKey**](Apis/DefaultApi.md#apiKeysUpdateApiKey) | **PUT** /v1/management/api-keys/update |  |
*DefaultApi* | [**scopesCreateNewScope**](Apis/DefaultApi.md#scopesCreateNewScope) | **POST** /v1/management/scopes/create |  |
*DefaultApi* | [**scopesGetScopeById**](Apis/DefaultApi.md#scopesGetScopeById) | **GET** /v1/management/scopes/{id} |  |
*DefaultApi* | [**scopesListScopes**](Apis/DefaultApi.md#scopesListScopes) | **GET** /v1/management/scopes |  |
*DefaultApi* | [**scopesUpdateScope**](Apis/DefaultApi.md#scopesUpdateScope) | **PUT** /v1/management/scopes/update |  |


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
 - [ApiKeys_createNewApiKey_201_response](./Models/ApiKeys_createNewApiKey_201_response.md)
 - [ApiKeys_createNewApiKey_request](./Models/ApiKeys_createNewApiKey_request.md)
 - [ApiKeys_updateApiKey_request](./Models/ApiKeys_updateApiKey_request.md)
 - [Api_Internal_ApiKey_Common_QuotaLedger_day](./Models/Api_Internal_ApiKey_Common_QuotaLedger_day.md)
 - [Api_Internal_ApiKey_Common_QuotaLedger_total](./Models/Api_Internal_ApiKey_Common_QuotaLedger_total.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="ApiKeyAuth"></a>
### ApiKeyAuth

- **Type**: API key
- **API key parameter name**: x-api-key
- **Location**: HTTP header

