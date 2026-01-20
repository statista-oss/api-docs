# DefaultApi

All URIs are relative to *https://api.statista.ai*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**report**](DefaultApi.md#report) | **GET** /v1/data/report |  |
| [**reports**](DefaultApi.md#reports) | **GET** /v1/data/reports |  |
| [**statistic**](DefaultApi.md#statistic) | **GET** /v1/data/statistic |  |


<a name="report"></a>
# **report**
> report(t)



    Returns the Report file as binary data

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **t** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="reports"></a>
# **reports**
> ReportsResponse reports(id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| The unique identifier of a content information to be retrieved. | [default to null] |

### Return type

[**ReportsResponse**](../Models/ReportsResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="statistic"></a>
# **statistic**
> Api.Data.Response.Statistic statistic(id, format)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | **Integer**| The unique identifier of a content information to be retrieved. | [default to null] |
| **format** | **String**| The format of the data to be retrieved. Set &#39;format&#x3D;advanced&#39; to get the data in an advanced format. | [optional] [default to basic] [enum: basic, advanced] |

### Return type

[**Api.Data.Response.Statistic**](../Models/Api.Data.Response.Statistic.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

