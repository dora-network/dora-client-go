# CreateWithdrawalRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WithdrawalId** | **string** | Client-supplied idempotency key (also the on-chain correlation key). Repeating a request with the same withdrawal_id has no additional effect. | 
**ToAddress** | **string** | Destination wallet address as a 0x-prefixed hex string. Must not be the zero address. | 
**Quantity** | **string** | Human-decimal USDC quantity to withdraw. Must be positive and no finer than USDC&#39;s 6 on-chain decimals. | 

## Methods

### NewCreateWithdrawalRequest

`func NewCreateWithdrawalRequest(withdrawalId string, toAddress string, quantity string, ) *CreateWithdrawalRequest`

NewCreateWithdrawalRequest instantiates a new CreateWithdrawalRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWithdrawalRequestWithDefaults

`func NewCreateWithdrawalRequestWithDefaults() *CreateWithdrawalRequest`

NewCreateWithdrawalRequestWithDefaults instantiates a new CreateWithdrawalRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWithdrawalId

`func (o *CreateWithdrawalRequest) GetWithdrawalId() string`

GetWithdrawalId returns the WithdrawalId field if non-nil, zero value otherwise.

### GetWithdrawalIdOk

`func (o *CreateWithdrawalRequest) GetWithdrawalIdOk() (*string, bool)`

GetWithdrawalIdOk returns a tuple with the WithdrawalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithdrawalId

`func (o *CreateWithdrawalRequest) SetWithdrawalId(v string)`

SetWithdrawalId sets WithdrawalId field to given value.


### GetToAddress

`func (o *CreateWithdrawalRequest) GetToAddress() string`

GetToAddress returns the ToAddress field if non-nil, zero value otherwise.

### GetToAddressOk

`func (o *CreateWithdrawalRequest) GetToAddressOk() (*string, bool)`

GetToAddressOk returns a tuple with the ToAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToAddress

`func (o *CreateWithdrawalRequest) SetToAddress(v string)`

SetToAddress sets ToAddress field to given value.


### GetQuantity

`func (o *CreateWithdrawalRequest) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateWithdrawalRequest) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateWithdrawalRequest) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


