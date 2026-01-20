# DefaultApi

All URIs are relative to *https://api.statista.ai*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**infographicsFindInfographics**](DefaultApi.md#infographicsFindInfographics) | **GET** /v1/infographics |  |
| [**marketInsightsFindMarketInsights**](DefaultApi.md#marketInsightsFindMarketInsights) | **GET** /v1/marketInsights |  |
| [**statisticsFindStatistics**](DefaultApi.md#statisticsFindStatistics) | **GET** /v1/statistics |  |
| [**statisticsResearchAiSearchSearchStatistics**](DefaultApi.md#statisticsResearchAiSearchSearchStatistics) | **GET** /v1/search/statistics |  |
| [**studiesFindStudies**](DefaultApi.md#studiesFindStudies) | **GET** /v1/studies |  |


<a name="infographicsFindInfographics"></a>
# **infographicsFindInfographics**
> Infographics_findInfographics_200_response infographicsFindInfographics(q, platform, offset, size, page, date\_from, date\_to, industry, geolocation, sort)



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
| **industry** | [**Api.Request.Industry**](../Models/.md)| It helps to find content related to a specific industry. The value is a number that can be found in the URL. | [optional] [default to null] [enum: https://www.statista.com/api/v2/industries_de.json, https://www.statista.com/api/v2/industries_en.json] |
| **geolocation** | [**Infographics_findInfographics_geolocation_parameter**](../Models/.md)| Filters content based on a specific geographic location. Defaults to &#x60;Worldwide&#x60; which means all content. Use geolocation codes provided by the API documentation. For example, &#x60;1&#x60; for Worldwide, &#x60;2&#x60; for Africa, etc. Note: only one geolocation can be used at a time. | [optional] [default to null] |
| **sort** | [**Type.SortBy**](../Models/.md)| Choose how you want the results to be ordered: 0 – Best match first (sorted by relevance) 1 – Most recent first (sorted by publication date) Defaults to &#x60;0&#x60;. | [optional] [default to null] [enum: 0, 1] |

### Return type

[**Infographics_findInfographics_200_response**](../Models/Infographics_findInfographics_200_response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="marketInsightsFindMarketInsights"></a>
# **marketInsightsFindMarketInsights**
> MarketInsights_findMarketInsights_200_response marketInsightsFindMarketInsights(q, platform, offset, size, page, date\_from, date\_to, geolocation, sort)



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
| **geolocation** | [**Infographics_findInfographics_geolocation_parameter**](../Models/.md)| Filters content based on a specific geographic location. Defaults to &#x60;Worldwide&#x60; which means all content. Use geolocation codes provided by the API documentation. For example, &#x60;1&#x60; for Worldwide, &#x60;2&#x60; for Africa, etc. Note: only one geolocation can be used at a time. | [optional] [default to null] |
| **sort** | [**Type.SortBy**](../Models/.md)| Choose how you want the results to be ordered: 0 – Best match first (sorted by relevance) 1 – Most recent first (sorted by publication date) Defaults to &#x60;0&#x60;. | [optional] [default to null] [enum: 0, 1] |

### Return type

[**MarketInsights_findMarketInsights_200_response**](../Models/MarketInsights_findMarketInsights_200_response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="statisticsFindStatistics"></a>
# **statisticsFindStatistics**
> StatisticsResearchAiSearch_searchStatistics_200_response statisticsFindStatistics(q, platform, offset, size, page, date\_from, date\_to, premium, sort)



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

[**StatisticsResearchAiSearch_searchStatistics_200_response**](../Models/StatisticsResearchAiSearch_searchStatistics_200_response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="statisticsResearchAiSearchSearchStatistics"></a>
# **statisticsResearchAiSearchSearchStatistics**
> StatisticsResearchAiSearch_searchStatistics_200_response statisticsResearchAiSearchSearchStatistics(q, offset, size, date\_from, date\_to, geolocation, premium)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **q** | **String**| The query string to search for content. This parameter is multi-lingual. | [default to null] |
| **offset** | **Integer**| The number of items will be skipped before the first result. The default value for &#x60;offset&#x60; is 0. This is useful for pagination. Could be used in combination with &#x60;size&#x60;. | [optional] [default to 0] |
| **size** | **Integer**| The max. value depends on which API Package you are using. The default value for &#x60;size&#x60; is 10. See API-Packages for more information.  An alias for &#x60;size&#x60; is &#x60;limit&#x60; | [optional] [default to 10] |
| **date\_from** | **Date**| The start date to search for content. | [optional] [default to null] |
| **date\_to** | **Date**| The end date to search for content. If not set, the current date is used. | [optional] [default to null] |
| **geolocation** | [**Infographics_findInfographics_geolocation_parameter**](../Models/.md)| Filters content based on a specific geographic location. Defaults to &#x60;Worldwide&#x60; which means all content. Use geolocation codes provided by the API documentation. For example, &#x60;1&#x60; for Worldwide, &#x60;2&#x60; for Africa, etc. Note: only one geolocation can be used at a time. | [optional] [default to null] |
| **premium** | **Boolean**| Filters content based on its premium status. If set to &#x60;true&#x60;, only premium content is returned. If set to &#x60;false&#x60;, only free content is returned. If not set, both free and premium content is returned. | [optional] [default to null] |

### Return type

[**StatisticsResearchAiSearch_searchStatistics_200_response**](../Models/StatisticsResearchAiSearch_searchStatistics_200_response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="studiesFindStudies"></a>
# **studiesFindStudies**
> Studies_findStudies_200_response studiesFindStudies(q, platform, offset, size, page, date\_from, date\_to, industry, geolocation, premium, sort)



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
| **industry** | [**Api.Request.Industry**](../Models/.md)| It helps to find content related to a specific industry. The value is a number that can be found in the URL. | [optional] [default to null] [enum: https://www.statista.com/api/v2/industries_de.json, https://www.statista.com/api/v2/industries_en.json] |
| **geolocation** | [**Infographics_findInfographics_geolocation_parameter**](../Models/.md)| Filters content based on a specific geographic location. Defaults to &#x60;Worldwide&#x60; which means all content. Use geolocation codes provided by the API documentation. For example, &#x60;1&#x60; for Worldwide, &#x60;2&#x60; for Africa, etc. Note: only one geolocation can be used at a time. | [optional] [default to null] |
| **premium** | **Boolean**| Filters content based on its premium status. If set to &#x60;true&#x60;, only premium content is returned. If set to &#x60;false&#x60;, only free content is returned. If not set, both free and premium content is returned. | [optional] [default to null] |
| **sort** | [**Type.SortBy**](../Models/.md)| Choose how you want the results to be ordered: 0 – Best match first (sorted by relevance) 1 – Most recent first (sorted by publication date) Defaults to &#x60;0&#x60;. | [optional] [default to null] [enum: 0, 1] |

### Return type

[**Studies_findStudies_200_response**](../Models/Studies_findStudies_200_response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

