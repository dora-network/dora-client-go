# DepositArgs

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quantity** | **string** | Deposit quantity in USDC base units (10^-6 USDC), as a decimal string. Matches the permit&#39;s value. | 
**UserId** | **string** | The caller&#39;s user ID as 16 bytes, 0x-prefixed hex. Stored on-chain with the deposit and mapped back to the user by the indexer. | 
**ClientReferenceId** | **string** | The bytes32 client reference as a 0x-prefixed hex string. All zero bytes when not supplied. | 
**Deadline** | **string** | Unix timestamp (seconds), as a decimal string. Matches the permit&#39;s deadline exactly. | 

## Methods

### NewDepositArgs

`func NewDepositArgs(quantity string, userId string, clientReferenceId string, deadline string, ) *DepositArgs`

NewDepositArgs instantiates a new DepositArgs object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDepositArgsWithDefaults

`func NewDepositArgsWithDefaults() *DepositArgs`

NewDepositArgsWithDefaults instantiates a new DepositArgs object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuantity

`func (o *DepositArgs) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *DepositArgs) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *DepositArgs) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetUserId

`func (o *DepositArgs) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *DepositArgs) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *DepositArgs) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetClientReferenceId

`func (o *DepositArgs) GetClientReferenceId() string`

GetClientReferenceId returns the ClientReferenceId field if non-nil, zero value otherwise.

### GetClientReferenceIdOk

`func (o *DepositArgs) GetClientReferenceIdOk() (*string, bool)`

GetClientReferenceIdOk returns a tuple with the ClientReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientReferenceId

`func (o *DepositArgs) SetClientReferenceId(v string)`

SetClientReferenceId sets ClientReferenceId field to given value.


### GetDeadline

`func (o *DepositArgs) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *DepositArgs) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *DepositArgs) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


