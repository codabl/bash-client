# SentimentAnalysisApi

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sentiment.getPriceSentiment**](SentimentAnalysisApi.md#sentiment.getPriceSentiment) | **POST** /get_buy_sentiment | Sentiment analysis score using a model trained for buy signals.
[**sentiment.getSentiment**](SentimentAnalysisApi.md#sentiment.getSentiment) | **POST** /get_sentiment | Sentiment analysis for any given blob of text


## **sentiment.getPriceSentiment**

Sentiment analysis score using a model trained for buy signals.

Gives a 0 to 1 score, depending on buy/sell sentiment

### Example
```bash
 sentiment.getPriceSentiment
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **text** | [**Text_1**](Text_1.md) | String of text to be analyzed. I can be in any language. |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **sentiment.getSentiment**

Sentiment analysis for any given blob of text

Gives a -1 to 1 score, depending on bearish/bullish sentiment

### Example
```bash
 sentiment.getSentiment
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **text** | [**Text**](Text.md) | String of text to be analyzed. I can be in any language. |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

