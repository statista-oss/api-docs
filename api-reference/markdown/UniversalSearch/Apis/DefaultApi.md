# DefaultApi

All URIs are relative to *https://api.statista.ai*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**search**](DefaultApi.md#search) | **GET** /v1/search |  |


<a name="search"></a>
# **search**
> search_200_response search(q, platform, offset, size, page, date\_from, date\_to, premium, sort)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **q** | **String**| The query string to search for content. Defaults to &#39;*&#39; which means all content. | [optional] [default to *] |
| **platform** | [**Type.LanguageLocale**](../Models/.md)| The platform to search for content. Defaults to &#x60;en&#x60; which means English. | [optional] [default to null] [enum: de, en, fr, es] |
| **offset** | **Integer**| The number of items will be skipped before the first result. The default value for &#x60;offset&#x60; is 0. This is useful for pagination. Could be used in combination with &#x60;size&#x60;. | [optional] [default to 0] |
| **size** | **Integer**| The max. value depends on which API Package you are using. The default value for &#x60;size&#x60; is 10. See API-Packages for more information.  An alias for &#x60;size&#x60; is &#x60;limit&#x60; | [optional] [default to 10] |
| **page** | **Integer**| The page number to return. The default value for &#x60;page&#x60; is 1. This is useful for pagination. Could be used in combination with &#x60;size&#x60;. | [optional] [default to 1] |
| **date\_from** | **Date**| The start date to search for content. All content published after this date will be returned. We accept a variety of date formats, e.g. &#x60;YYYY-MM-DD&#x60;. For example, &#x60;2023-01-01&#x60; will return all content published after or on the January 1st, 2023. If not set, we will use 3 months into the past as the default value. | [optional] [default to null] |
| **date\_to** | **Date**| The end date to search for content. All content published before this date will be returned. We accept a variety of date formats, e.g. &#x60;YYYY-MM-DD&#x60;. For example, &#x60;2023-01-01&#x60; will return all content published before or on the January 1st, 2023. If not set, the current date is used. | [optional] [default to null] |
| **premium** | **Boolean**| Filters content based on its premium status. If set to &#x60;true&#x60;, only premium content is returned. If set to &#x60;false&#x60;, only free content is returned. If not set, both free and premium content is returned. | [optional] [default to null] |
| **sort** | [**Type.SortBy**](../Models/.md)| Choose how you want the results to be ordered: 0 – Best match first (sorted by relevance) 1 – Most recent first (sorted by publication date) Defaults to &#x60;0&#x60;. | [optional] [default to null] [enum: 0, 1] |

### Return type

[**search_200_response**](../Models/search_200_response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

