# DefaultApi

All URIs are relative to *https://internal.globalsearch.prod.aws.statista.com*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**apiKeysAssignApiKeysToMainKey**](DefaultApi.md#apiKeysAssignApiKeysToMainKey) | **POST** /v1/management/api-keys/{id}/assign-to-main-key |  |
| [**apiKeysCreateNewApiKey**](DefaultApi.md#apiKeysCreateNewApiKey) | **POST** /v1/management/api-keys/create |  |
| [**apiKeysGetApiKeysById**](DefaultApi.md#apiKeysGetApiKeysById) | **GET** /v1/management/api-keys/{id} |  |
| [**apiKeysListApiKeys**](DefaultApi.md#apiKeysListApiKeys) | **GET** /v1/management/api-keys |  |
| [**apiKeysUpdateApiKey**](DefaultApi.md#apiKeysUpdateApiKey) | **PUT** /v1/management/api-keys/update |  |
| [**scopesCreateNewScope**](DefaultApi.md#scopesCreateNewScope) | **POST** /v1/management/scopes/create |  |
| [**scopesGetScopeById**](DefaultApi.md#scopesGetScopeById) | **GET** /v1/management/scopes/{id} |  |
| [**scopesListScopes**](DefaultApi.md#scopesListScopes) | **GET** /v1/management/scopes |  |
| [**scopesUpdateScope**](DefaultApi.md#scopesUpdateScope) | **PUT** /v1/management/scopes/update |  |


<a name="apiKeysAssignApiKeysToMainKey"></a>
# **apiKeysAssignApiKeysToMainKey**
> String apiKeysAssignApiKeysToMainKey(id, Api.Internal.ApiKey.Request.AssignToMainKey)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **String**|  | [default to null] |
| **Api.Internal.ApiKey.Request.AssignToMainKey** | [**Api.Internal.ApiKey.Request.AssignToMainKey**](../Models/Api.Internal.ApiKey.Request.AssignToMainKey.md)|  | |

### Return type

**String**

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: text/plain

<a name="apiKeysCreateNewApiKey"></a>
# **apiKeysCreateNewApiKey**
> ApiKeys_createNewApiKey_201_response apiKeysCreateNewApiKey(ApiKeys\_createNewApiKey\_request)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **ApiKeys\_createNewApiKey\_request** | [**ApiKeys_createNewApiKey_request**](../Models/ApiKeys_createNewApiKey_request.md)|  | |

### Return type

[**ApiKeys_createNewApiKey_201_response**](../Models/ApiKeys_createNewApiKey_201_response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="apiKeysGetApiKeysById"></a>
# **apiKeysGetApiKeysById**
> Api.Internal.ApiKey.Response.ApiKey apiKeysGetApiKeysById(id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **String**|  | [default to null] |

### Return type

[**Api.Internal.ApiKey.Response.ApiKey**](../Models/Api.Internal.ApiKey.Response.ApiKey.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="apiKeysListApiKeys"></a>
# **apiKeysListApiKeys**
> List apiKeysListApiKeys(main\_id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **main\_id** | **UUID**| The main api key id used to display its members | [optional] [default to null] |

### Return type

[**List**](../Models/Api.Internal.ApiKey.Response.ApiKey.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="apiKeysUpdateApiKey"></a>
# **apiKeysUpdateApiKey**
> String apiKeysUpdateApiKey(ApiKeys\_updateApiKey\_request)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **ApiKeys\_updateApiKey\_request** | [**ApiKeys_updateApiKey_request**](../Models/ApiKeys_updateApiKey_request.md)|  | |

### Return type

**String**

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: text/plain

<a name="scopesCreateNewScope"></a>
# **scopesCreateNewScope**
> String scopesCreateNewScope(Api.Internal.KeyScopes.Request.WriteScopes)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Api.Internal.KeyScopes.Request.WriteScopes** | [**Api.Internal.KeyScopes.Request.WriteScopes**](../Models/Api.Internal.KeyScopes.Request.WriteScopes.md)|  | |

### Return type

**String**

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: text/plain

<a name="scopesGetScopeById"></a>
# **scopesGetScopeById**
> Api.Internal.KeyScopes.Response.Scopes scopesGetScopeById(id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **String**|  | [default to null] |

### Return type

[**Api.Internal.KeyScopes.Response.Scopes**](../Models/Api.Internal.KeyScopes.Response.Scopes.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="scopesListScopes"></a>
# **scopesListScopes**
> List scopesListScopes()



### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../Models/Api.Internal.KeyScopes.Response.Scopes.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="scopesUpdateScope"></a>
# **scopesUpdateScope**
> String scopesUpdateScope(Api.Internal.KeyScopes.Request.WriteScopes)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Api.Internal.KeyScopes.Request.WriteScopes** | [**Api.Internal.KeyScopes.Request.WriteScopes**](../Models/Api.Internal.KeyScopes.Request.WriteScopes.md)|  | |

### Return type

**String**

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: text/plain

