# ai.thirdwatch.Model.Login
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**userId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] 
**sessionId** | **string** | The user&#39;s current session ID, used to tie a user&#39;s action before and after login or account creation. Required if no user_id values is provided. | [optional] 
**deviceIp** | **string** | IP address of the request made by the user. Recommended for historical backfills and customers with mobile apps. | [optional] 
**originTimestamp** | **string** | Represents the time the event occured in your system. Send as a UNIX timestamp in milliseconds in string. | [optional] 
**loginStatus** | **string** | Use _loginStatus to represent the success or failure of the login attempt. e.g. _success, _failure | [optional] 
**customInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

