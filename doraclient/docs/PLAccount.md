# PLAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | Pointer to **string** | The ID of the account holding the position | [optional] 
**AccountName** | Pointer to **string** | The name of the account holding the position | [optional] 
**IsGlobal** | Pointer to **bool** | Whether the account is the global or an isolated account | [optional] 
**Rows** | Pointer to [**[]PLAsset**](PLAsset.md) |  | [optional] 
**Summary** | Pointer to [**PLSummary**](PLSummary.md) |  | [optional] 

## Methods

### NewPLAccount

`func NewPLAccount() *PLAccount`

NewPLAccount instantiates a new PLAccount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPLAccountWithDefaults

`func NewPLAccountWithDefaults() *PLAccount`

NewPLAccountWithDefaults instantiates a new PLAccount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *PLAccount) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *PLAccount) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *PLAccount) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *PLAccount) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountName

`func (o *PLAccount) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *PLAccount) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *PLAccount) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *PLAccount) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetIsGlobal

`func (o *PLAccount) GetIsGlobal() bool`

GetIsGlobal returns the IsGlobal field if non-nil, zero value otherwise.

### GetIsGlobalOk

`func (o *PLAccount) GetIsGlobalOk() (*bool, bool)`

GetIsGlobalOk returns a tuple with the IsGlobal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobal

`func (o *PLAccount) SetIsGlobal(v bool)`

SetIsGlobal sets IsGlobal field to given value.

### HasIsGlobal

`func (o *PLAccount) HasIsGlobal() bool`

HasIsGlobal returns a boolean if a field has been set.

### GetRows

`func (o *PLAccount) GetRows() []PLAsset`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *PLAccount) GetRowsOk() (*[]PLAsset, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *PLAccount) SetRows(v []PLAsset)`

SetRows sets Rows field to given value.

### HasRows

`func (o *PLAccount) HasRows() bool`

HasRows returns a boolean if a field has been set.

### GetSummary

`func (o *PLAccount) GetSummary() PLSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *PLAccount) GetSummaryOk() (*PLSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *PLAccount) SetSummary(v PLSummary)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *PLAccount) HasSummary() bool`

HasSummary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


