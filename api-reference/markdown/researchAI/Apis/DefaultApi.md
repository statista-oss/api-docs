# DefaultApi

All URIs are relative to *https://api.statista.ai*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**answer**](DefaultApi.md#answer) | **GET** /v1/research-ai/answer |  |
| [**ask**](DefaultApi.md#ask) | **POST** /v1/research-ai/ask |  |


<a name="answer"></a>
# **answer**
> Api.Research.Response.Answer answer(research\_token)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **research\_token** | **String**| The research token to identify the question. This token is returned by the &#x60;ask&#x60; endpoint. | [default to null] |

### Return type

[**Api.Research.Response.Answer**](../Models/Api.Research.Response.Answer.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="ask"></a>
# **ask**
> QuestionResponse ask(Api.Research.Request.Ask)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Api.Research.Request.Ask** | [**Api.Research.Request.Ask**](../Models/Api.Research.Request.Ask.md)|  | |

### Return type

[**QuestionResponse**](../Models/QuestionResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

