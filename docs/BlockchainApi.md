# BlockchainApi

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**blockchain.averageTx**](BlockchainApi.md#blockchain.averageTx) | **POST** /average_tx_fee | Calculate average transccion fee of a given blockchain
[**blockchain.list**](BlockchainApi.md#blockchain.list) | **GET** /list_blockchain | The blockchains data structure supported by the Brainrex API


## **blockchain.averageTx**

Calculate average transccion fee of a given blockchain

Calculates the average trasnsaction fee of a given

### Example
```bash
 blockchain.averageTx
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**Request**](Request.md) | Name of the blockchain and date range. |

### Return type

[**Inline_response_201**](Inline_response_201.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **blockchain.list**

The blockchains data structure supported by the Brainrex API

List of supported blockchains networks for analysis. The full history of the networks are available.

### Example
```bash
 blockchain.list
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

