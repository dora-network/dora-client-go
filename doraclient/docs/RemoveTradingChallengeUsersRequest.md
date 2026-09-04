# RemoveTradingChallengeUsersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TradingChallengeId** | **string** |  | 
**Users** | Pointer to **[]string** | List of user IDs to remove. Provide exactly one of users or emails. | [optional] 
**Emails** | Pointer to **[]string** | List of user emails to remove. Provide exactly one of users or emails. | [optional] 

## Methods

### NewRemoveTradingChallengeUsersRequest

`func NewRemoveTradingChallengeUsersRequest(tradingChallengeId string, ) *RemoveTradingChallengeUsersRequest`

NewRemoveTradingChallengeUsersRequest instantiates a new RemoveTradingChallengeUsersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRemoveTradingChallengeUsersRequestWithDefaults

`func NewRemoveTradingChallengeUsersRequestWithDefaults() *RemoveTradingChallengeUsersRequest`

NewRemoveTradingChallengeUsersRequestWithDefaults instantiates a new RemoveTradingChallengeUsersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTradingChallengeId

`func (o *RemoveTradingChallengeUsersRequest) GetTradingChallengeId() string`

GetTradingChallengeId returns the TradingChallengeId field if non-nil, zero value otherwise.

### GetTradingChallengeIdOk

`func (o *RemoveTradingChallengeUsersRequest) GetTradingChallengeIdOk() (*string, bool)`

GetTradingChallengeIdOk returns a tuple with the TradingChallengeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeId

`func (o *RemoveTradingChallengeUsersRequest) SetTradingChallengeId(v string)`

SetTradingChallengeId sets TradingChallengeId field to given value.


### GetUsers

`func (o *RemoveTradingChallengeUsersRequest) GetUsers() []string`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *RemoveTradingChallengeUsersRequest) GetUsersOk() (*[]string, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *RemoveTradingChallengeUsersRequest) SetUsers(v []string)`

SetUsers sets Users field to given value.

### HasUsers

`func (o *RemoveTradingChallengeUsersRequest) HasUsers() bool`

HasUsers returns a boolean if a field has been set.

### GetEmails

`func (o *RemoveTradingChallengeUsersRequest) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *RemoveTradingChallengeUsersRequest) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *RemoveTradingChallengeUsersRequest) SetEmails(v []string)`

SetEmails sets Emails field to given value.

### HasEmails

`func (o *RemoveTradingChallengeUsersRequest) HasEmails() bool`

HasEmails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


