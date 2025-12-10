# DefaultApi

All URIs are relative to *https://api.statista.ai*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**statisticReport**](DefaultApi.md#statisticReport) | **GET** /v1/data/report |  |
| [**statisticReports**](DefaultApi.md#statisticReports) | **GET** /v1/data/reports |  |
| [**statisticStatistic**](DefaultApi.md#statisticStatistic) | **GET** /v1/data/statistic |  |


<a name="statisticReport"></a>
# **statisticReport**
> statisticReport(t)



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

<a name="statisticReports"></a>
# **statisticReports**
> ReportsResponse statisticReports(id)



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

<a name="statisticStatistic"></a>
# **statisticStatistic**
> Api.Data.Response.Statistic statisticStatistic(id, format)



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

