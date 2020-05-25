# UserAllOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** | The account ID for the user. The format is a-zA-Z0-9_|-:{1,128} | 
**AccountType** | **string** | Valid values: &#x60;atlassian&#x60;, &#x60;customer&#x60;, &#x60;app&#x60;  | 
**AccountStatus** | **string** | The lifecycle status of the account  Valid values: &#x60;active&#x60;, &#x60;inactive, &#x60;closed&#x60;  | 
**Name** | **string** | The display name of the user. Should be used for contextual rendering of the authorship in content. If the user has restricted visibility of their name, their nickname will be displayed as a substitute value  | 
**Picture** | **string** | The absolute URI (RFC3986) to the avatar name of the user. Should be used for contextual rendering of the authorship in content. If the user has restricted visibility of their avatar, an alternative URI will be provided as a substitute value  | 
**Email** | **string** | The email address of the user. If the user has restricted visibility of the email address, the property will be absent  | [optional] 
**AccessBillable** | **bool** | Billable status of User in Atlassian Access | [optional] 
**LastActive** | **string** | Last active date for a user | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


