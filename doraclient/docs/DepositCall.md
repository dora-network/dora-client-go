# DepositCall

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**To** | **string** | The vault contract address, as a 0x-prefixed hex string. | 
**ChainId** | **int64** | EVM chain ID, as a JSON number. | 
**Value** | **string** | Native currency value to send with the transaction. Always &#39;0&#39;. | 
**FunctionSignature** | **string** | Canonical Solidity signature of the vault&#39;s permit-aware deposit function: deposit(uint256,bytes16,bytes32,uint256,uint8,bytes32,bytes32). | 
**Selector** | **string** | The 4-byte ABI call selector of function_signature, as a 0x-prefixed hex string. | 
**Args** | [**DepositArgs**](DepositArgs.md) |  | 

## Methods

### NewDepositCall

`func NewDepositCall(to string, chainId int64, value string, functionSignature string, selector string, args DepositArgs, ) *DepositCall`

NewDepositCall instantiates a new DepositCall object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDepositCallWithDefaults

`func NewDepositCallWithDefaults() *DepositCall`

NewDepositCallWithDefaults instantiates a new DepositCall object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTo

`func (o *DepositCall) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *DepositCall) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *DepositCall) SetTo(v string)`

SetTo sets To field to given value.


### GetChainId

`func (o *DepositCall) GetChainId() int64`

GetChainId returns the ChainId field if non-nil, zero value otherwise.

### GetChainIdOk

`func (o *DepositCall) GetChainIdOk() (*int64, bool)`

GetChainIdOk returns a tuple with the ChainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChainId

`func (o *DepositCall) SetChainId(v int64)`

SetChainId sets ChainId field to given value.


### GetValue

`func (o *DepositCall) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *DepositCall) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *DepositCall) SetValue(v string)`

SetValue sets Value field to given value.


### GetFunctionSignature

`func (o *DepositCall) GetFunctionSignature() string`

GetFunctionSignature returns the FunctionSignature field if non-nil, zero value otherwise.

### GetFunctionSignatureOk

`func (o *DepositCall) GetFunctionSignatureOk() (*string, bool)`

GetFunctionSignatureOk returns a tuple with the FunctionSignature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunctionSignature

`func (o *DepositCall) SetFunctionSignature(v string)`

SetFunctionSignature sets FunctionSignature field to given value.


### GetSelector

`func (o *DepositCall) GetSelector() string`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *DepositCall) GetSelectorOk() (*string, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *DepositCall) SetSelector(v string)`

SetSelector sets Selector field to given value.


### GetArgs

`func (o *DepositCall) GetArgs() DepositArgs`

GetArgs returns the Args field if non-nil, zero value otherwise.

### GetArgsOk

`func (o *DepositCall) GetArgsOk() (*DepositArgs, bool)`

GetArgsOk returns a tuple with the Args field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArgs

`func (o *DepositCall) SetArgs(v DepositArgs)`

SetArgs sets Args field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


