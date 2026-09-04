# AddTradingChallengeUsersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TradingChallengeId** | **string** |  | 
**Users** | Pointer to **[]string** | List of user IDs to add. Provide exactly one of users or emails. | [optional] 
**Emails** | Pointer to **[]string** | List of user emails to add. Provide exactly one of users or emails. | [optional] 

## Methods

### NewAddTradingChallengeUsersRequest

`func NewAddTradingChallengeUsersRequest(tradingChallengeId string, ) *AddTradingChallengeUsersRequest`

NewAddTradingChallengeUsersRequest instantiates a new AddTradingChallengeUsersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddTradingChallengeUsersRequestWithDefaults

`func NewAddTradingChallengeUsersRequestWithDefaults() *AddTradingChallengeUsersRequest`

NewAddTradingChallengeUsersRequestWithDefaults instantiates a new AddTradingChallengeUsersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTradingChallengeId

`func (o *AddTradingChallengeUsersRequest) GetTradingChallengeId() string`

GetTradingChallengeId returns the TradingChallengeId field if non-nil, zero value otherwise.

### GetTradingChallengeIdOk

`func (o *AddTradingChallengeUsersRequest) GetTradingChallengeIdOk() (*string, bool)`

GetTradingChallengeIdOk returns a tuple with the TradingChallengeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeId

`func (o *AddTradingChallengeUsersRequest) SetTradingChallengeId(v string)`

SetTradingChallengeId sets TradingChallengeId field to given value.


### GetUsers

`func (o *AddTradingChallengeUsersRequest) GetUsers() []string`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *AddTradingChallengeUsersRequest) GetUsersOk() (*[]string, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *AddTradingChallengeUsersRequest) SetUsers(v []string)`

SetUsers sets Users field to given value.

### HasUsers

`func (o *AddTradingChallengeUsersRequest) HasUsers() bool`

HasUsers returns a boolean if a field has been set.

### GetEmails

`func (o *AddTradingChallengeUsersRequest) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *AddTradingChallengeUsersRequest) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *AddTradingChallengeUsersRequest) SetEmails(v []string)`

SetEmails sets Emails field to given value.

### HasEmails

`func (o *AddTradingChallengeUsersRequest) HasEmails() bool`

HasEmails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


