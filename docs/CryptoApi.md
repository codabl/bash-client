# CryptoApi

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**exchanges.downloadCandles**](CryptoApi.md#exchanges.downloadCandles) | **POST** /download_candles | Downloads candle format market data
[**exchanges.list**](CryptoApi.md#exchanges.list) | **GET** /markets | The markets data structure supported by the Brainrex Market API
[**exchanges.marketmaker**](CryptoApi.md#exchanges.marketmaker) | **POST** /market_making | Market Making as a Service API.
[**exchanges.read**](CryptoApi.md#exchanges.read) | **GET** /exchanges | The exchanges data structure supported by the Brainrex API
[**exchanges.tickerDataDownload**](CryptoApi.md#exchanges.tickerDataDownload) | **POST** /download_ticker | Download raw ticker data from major crypto markets


## **exchanges.downloadCandles**

Downloads candle format market data

Returns a list of candle data from specified market and data range

### Example
```bash
 exchanges.downloadCandles
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**Request_2**](Request_2.md) | Person to create |

### Return type

[**Inline_response_201**](Inline_response_201.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **exchanges.list**

The markets data structure supported by the Brainrex Market API

Read the list of supported markets ( currency pairs ) in each exchange

### Example
```bash
 exchanges.list
```

### Parameters
This endpoint does not need any parameter.

### Return type

**array[map]**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **exchanges.marketmaker**

Market Making as a Service API.

Our AI will trade at the risk level you want, you need to provide your credential to the exchange you are trading at.

### Example
```bash
 exchanges.marketmaker
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**Request_3**](Request_3.md) | Name of exchange and currency pair you want to provide liquidity |

### Return type

[**Inline_response_201_1**](Inline_response_201_1.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **exchanges.read**

The exchanges data structure supported by the Brainrex API

Read the list of supported exchanges in the Market Data API

### Example
```bash
 exchanges.read
```

### Parameters
This endpoint does not need any parameter.

### Return type

**array[map]**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **exchanges.tickerDataDownload**

Download raw ticker data from major crypto markets

Downloads specified asset class and market and time frame. Of our raw ticker data format

### Example
```bash
 exchanges.tickerDataDownload
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**Request_1**](Request_1.md) | Person to create |

### Return type

[**Inline_response_201**](Inline_response_201.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

