# Api.Response.MarketInsight
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **identifier** | **Integer** | A unique number for this content. It helps find or refer to this data. | [default to null] |
| **title** | **String** | The name of the content. It tells what the data is about. | [default to null] |
| **description** | **String** | Optional: A short text that explains the most important facts in the data. Available for Advanced API key | [optional] [default to null] |
| **link** | **String** | The website address (URL) where you can see the full content on the Statista platform. | [default to null] |
| **date** | **Date** | The date when the data was published. Format: YYYY-MM-DDTHH:mm:ssZ | [default to null] |
| **platform** | [**Type.LanguageLocale**](Type.LanguageLocale.md) | The language of the page or platform. | [default to null] |
| **sub\_title** | **String** | A short explanation of the content&#39;s focus. | [optional] [default to null] |
| **children** | [**List**](Insights.Market.md) | A list of sub-markets related to the data. | [optional] [default to null] |
| **path** | [**List**](Insights.Market.md) | A list of parent markets showing where this report belongs in the overall market structure. | [default to null] |
| **geolocations** | [**List**](Api.Response.Region.md) | A list of regions related to the data. | [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

