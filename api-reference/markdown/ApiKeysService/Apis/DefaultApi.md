# DefaultApi

All URIs are relative to *https://apiv2.globalsearch.prod.aws.statista.com*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**apiKeysAssignToMainKey**](DefaultApi.md#apiKeysAssignToMainKey) | **POST** /v1/management/api-keys/{id}/assign-to-main-key |  |
| [**apiKeysCreate**](DefaultApi.md#apiKeysCreate) | **POST** /v1/management/api-keys/create |  |
| [**apiKeysGet**](DefaultApi.md#apiKeysGet) | **GET** /v1/management/api-keys/{id} |  |
| [**apiKeysList**](DefaultApi.md#apiKeysList) | **GET** /v1/management/api-keys |  |
| [**apiKeysUpdate**](DefaultApi.md#apiKeysUpdate) | **PUT** /v1/management/api-keys/update |  |
| [**scopesCreate**](DefaultApi.md#scopesCreate) | **POST** /v1/management/scopes/create |  |
| [**scopesGet**](DefaultApi.md#scopesGet) | **GET** /v1/management/scopes/{id} |  |
| [**scopesList**](DefaultApi.md#scopesList) | **GET** /v1/management/scopes |  |
| [**scopesUpdate**](DefaultApi.md#scopesUpdate) | **PUT** /v1/management/scopes/update |  |


<a name="apiKeysAssignToMainKey"></a>
# **apiKeysAssignToMainKey**
> apiKeysAssignToMainKey(id, Api.Internal.ApiKey.Request.AssignToMainKey)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **String**|  | [default to null] |
| **Api.Internal.ApiKey.Request.AssignToMainKey** | [**Api.Internal.ApiKey.Request.AssignToMainKey**](../Models/Api.Internal.ApiKey.Request.AssignToMainKey.md)|  | |

### Return type

null (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

<a name="apiKeysCreate"></a>
# **apiKeysCreate**
> ApiKeys_create_201_response apiKeysCreate(ApiKeys\_create\_request)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **ApiKeys\_create\_request** | [**ApiKeys_create_request**](../Models/ApiKeys_create_request.md)|  | |

### Return type

[**ApiKeys_create_201_response**](../Models/ApiKeys_create_201_response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="apiKeysGet"></a>
# **apiKeysGet**
> Api.Internal.ApiKey.Response.ApiKey apiKeysGet(id)



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

<a name="apiKeysList"></a>
# **apiKeysList**
> List apiKeysList(main\_id)



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

<a name="apiKeysUpdate"></a>
# **apiKeysUpdate**
> apiKeysUpdate(ApiKeys\_update\_request)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **ApiKeys\_update\_request** | [**ApiKeys_update_request**](../Models/ApiKeys_update_request.md)|  | |

### Return type

null (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

<a name="scopesCreate"></a>
# **scopesCreate**
> scopesCreate(Api.Internal.KeyScopes.Request.WriteScopes)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Api.Internal.KeyScopes.Request.WriteScopes** | [**Api.Internal.KeyScopes.Request.WriteScopes**](../Models/Api.Internal.KeyScopes.Request.WriteScopes.md)|  | |

### Return type

null (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

<a name="scopesGet"></a>
# **scopesGet**
> Api.Internal.KeyScopes.Response.Scopes scopesGet(id)



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

<a name="scopesList"></a>
# **scopesList**
> List scopesList()



### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../Models/Api.Internal.KeyScopes.Response.Scopes.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="scopesUpdate"></a>
# **scopesUpdate**
> scopesUpdate(Api.Internal.KeyScopes.Request.WriteScopes)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Api.Internal.KeyScopes.Request.WriteScopes** | [**Api.Internal.KeyScopes.Request.WriteScopes**](../Models/Api.Internal.KeyScopes.Request.WriteScopes.md)|  | |

### Return type

null (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

