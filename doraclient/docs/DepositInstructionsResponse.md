# DepositInstructionsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The authenticated user the instructions are issued for. | 
**OwnerAddress** | **string** | The wallet address the instructions were issued for, echoed from the request. | 
**Quantity** | **string** | Human-decimal USDC deposit quantity, echoed from the request. | 
**Chains** | [**[]DepositInstructionForChain**](DepositInstructionForChain.md) |  | 

## Methods

### NewDepositInstructionsResponse

`func NewDepositInstructionsResponse(userId string, ownerAddress string, quantity string, chains []DepositInstructionForChain, ) *DepositInstructionsResponse`

NewDepositInstructionsResponse instantiates a new DepositInstructionsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDepositInstructionsResponseWithDefaults

`func NewDepositInstructionsResponseWithDefaults() *DepositInstructionsResponse`

NewDepositInstructionsResponseWithDefaults instantiates a new DepositInstructionsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *DepositInstructionsResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *DepositInstructionsResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *DepositInstructionsResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetOwnerAddress

`func (o *DepositInstructionsResponse) GetOwnerAddress() string`

GetOwnerAddress returns the OwnerAddress field if non-nil, zero value otherwise.

### GetOwnerAddressOk

`func (o *DepositInstructionsResponse) GetOwnerAddressOk() (*string, bool)`

GetOwnerAddressOk returns a tuple with the OwnerAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerAddress

`func (o *DepositInstructionsResponse) SetOwnerAddress(v string)`

SetOwnerAddress sets OwnerAddress field to given value.


### GetQuantity

`func (o *DepositInstructionsResponse) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *DepositInstructionsResponse) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *DepositInstructionsResponse) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetChains

`func (o *DepositInstructionsResponse) GetChains() []DepositInstructionForChain`

GetChains returns the Chains field if non-nil, zero value otherwise.

### GetChainsOk

`func (o *DepositInstructionsResponse) GetChainsOk() (*[]DepositInstructionForChain, bool)`

GetChainsOk returns a tuple with the Chains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChains

`func (o *DepositInstructionsResponse) SetChains(v []DepositInstructionForChain)`

SetChains sets Chains field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


