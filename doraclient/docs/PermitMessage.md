# PermitMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Owner** | **string** | The user&#39;s wallet address (permit owner), as a 0x-prefixed hex string. | 
**Spender** | **string** | The vault contract address granted the allowance, as a 0x-prefixed hex string. | 
**Value** | **string** | Approved quantity in USDC base units (10^-6 USDC), as a decimal string. | 
**Nonce** | **string** | The owner&#39;s current USDC permit nonce on this chain, as a decimal string. | 
**Deadline** | **string** | Unix timestamp (seconds) at which the permit expires, as a decimal string. One hour from issuance. | 

## Methods

### NewPermitMessage

`func NewPermitMessage(owner string, spender string, value string, nonce string, deadline string, ) *PermitMessage`

NewPermitMessage instantiates a new PermitMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermitMessageWithDefaults

`func NewPermitMessageWithDefaults() *PermitMessage`

NewPermitMessageWithDefaults instantiates a new PermitMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOwner

`func (o *PermitMessage) GetOwner() string`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *PermitMessage) GetOwnerOk() (*string, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *PermitMessage) SetOwner(v string)`

SetOwner sets Owner field to given value.


### GetSpender

`func (o *PermitMessage) GetSpender() string`

GetSpender returns the Spender field if non-nil, zero value otherwise.

### GetSpenderOk

`func (o *PermitMessage) GetSpenderOk() (*string, bool)`

GetSpenderOk returns a tuple with the Spender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpender

`func (o *PermitMessage) SetSpender(v string)`

SetSpender sets Spender field to given value.


### GetValue

`func (o *PermitMessage) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *PermitMessage) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *PermitMessage) SetValue(v string)`

SetValue sets Value field to given value.


### GetNonce

`func (o *PermitMessage) GetNonce() string`

GetNonce returns the Nonce field if non-nil, zero value otherwise.

### GetNonceOk

`func (o *PermitMessage) GetNonceOk() (*string, bool)`

GetNonceOk returns a tuple with the Nonce field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonce

`func (o *PermitMessage) SetNonce(v string)`

SetNonce sets Nonce field to given value.


### GetDeadline

`func (o *PermitMessage) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *PermitMessage) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *PermitMessage) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


