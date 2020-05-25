# \DefaultApi

All URIs are relative to *https://api.atlassian.com/admin/v1/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OrgIdUsersGet**](DefaultApi.md#OrgIdUsersGet) | **Get** /{orgId}/users | 



## OrgIdUsersGet

> UserPageResponse OrgIdUsersGet(ctx, orgId, optional)



Returns a list of users in an organization. 

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string**| ID of the organization to query | 
 **optional** | ***OrgIdUsersGetOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a OrgIdUsersGetOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cursor** | **optional.String**| Sets the starting point for the page of results to return. | 

### Return type

[**UserPageResponse**](UserPageResponse.md)

### Authorization

[basicAuth](../README.md#basicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

