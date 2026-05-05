# AccountSummaryV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** | The ID of the account | 
**AccountName** | **string** | The name of the account | 
**IsGlobal** | **bool** | Whether the account is the global or an isolated account | 

## Methods

### NewAccountSummaryV2

`func NewAccountSummaryV2(accountId string, accountName string, isGlobal bool, ) *AccountSummaryV2`

NewAccountSummaryV2 instantiates a new AccountSummaryV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountSummaryV2WithDefaults

`func NewAccountSummaryV2WithDefaults() *AccountSummaryV2`

NewAccountSummaryV2WithDefaults instantiates a new AccountSummaryV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *AccountSummaryV2) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AccountSummaryV2) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AccountSummaryV2) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetAccountName

`func (o *AccountSummaryV2) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *AccountSummaryV2) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *AccountSummaryV2) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.


### GetIsGlobal

`func (o *AccountSummaryV2) GetIsGlobal() bool`

GetIsGlobal returns the IsGlobal field if non-nil, zero value otherwise.

### GetIsGlobalOk

`func (o *AccountSummaryV2) GetIsGlobalOk() (*bool, bool)`

GetIsGlobalOk returns a tuple with the IsGlobal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobal

`func (o *AccountSummaryV2) SetIsGlobal(v bool)`

SetIsGlobal sets IsGlobal field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


