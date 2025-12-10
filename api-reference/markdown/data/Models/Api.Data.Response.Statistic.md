# Api.Data.Response.Statistic
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **teaser\_image\_urls** | [**List**](Api.Response.TeaserImage.md) | A list of preview images for this content. | [default to null] |
| **identifier** | **Integer** | A unique number for this content. It helps find or refer to this data. | [default to null] |
| **title** | **String** | The name of the content. It tells what the data is about. | [default to null] |
| **description** | **String** | Optional: A short text that explains the most important facts in the data. Available for Advanced API key | [optional] [default to null] |
| **link** | **String** | The website address (URL) where you can see the full content on the Statista platform. | [default to null] |
| **date** | **Date** | The date when the data was published. Format: YYYY-MM-DDTHH:mm:ssZ | [default to null] |
| **platform** | [**Type.LanguageLocale**](Type.LanguageLocale.md) | The language of the page or platform. | [default to null] |
| **subject** | **String** | A short summary of what the data shows. | [default to null] |
| **is\_premium** | **Boolean** | A true/false value. Indicates on paid and free content. | [default to null] |
| **industries** | [**List**](Api.Response.Industry.md) | Optional: A list of industries related to the data. | [optional] [default to null] |
| **geolocations** | [**List**](Api.Response.Region.md) | Optional: A list of regions related to the data. | [optional] [default to null] |
| **sources** | [**List**](Api.Data.Response.Source.md) |  | [optional] [default to null] |
| **chargers** | [**List**](Api.Data.Response.Source.md) |  | [optional] [default to null] |
| **publishers** | [**List**](Api.Data.Response.Source.md) |  | [optional] [default to null] |
| **chart** | [**Api.Data.Response.Chart**](Api.Data.Response.Chart.md) |  | [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

