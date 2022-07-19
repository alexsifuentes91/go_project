# \SimpleMessagingAPIApi

All URIs are relative to *https://simple_messaging.swagger.io/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddMessage**](SimpleMessagingAPIApi.md#AddMessage) | **Post** / | Create a new message
[**GetMessage**](SimpleMessagingAPIApi.md#GetMessage) | **Get** / | Get all the messages
[**GetMessageByNumber**](SimpleMessagingAPIApi.md#GetMessageByNumber) | **Get** /{index} | Find message by message number
[**UpdateMessage**](SimpleMessagingAPIApi.md#UpdateMessage) | **Put** / | Update an existing message


# **AddMessage**
> AddMessage(ctx, body)
Create a new message



### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**Message**](Message.md)| Message object needing to be recorded | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/xml
 - **Accept**: application/json, application/xml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetMessage**
> []Message GetMessage(ctx, )
Get all the messages

Returns all messages

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**[]Message**](Message.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, application/xml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetMessageByNumber**
> Message GetMessageByNumber(ctx, index)
Find message by message number

Returns a single message

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **index** | **int64**| ID of message | 

### Return type

[**Message**](Message.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, application/xml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateMessage**
> UpdateMessage(ctx, body)
Update an existing message



### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**Message**](Message.md)| Message that needs to be updated | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/xml
 - **Accept**: application/json, application/xml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

