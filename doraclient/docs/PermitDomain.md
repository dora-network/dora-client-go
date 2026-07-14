# PermitDomain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | EIP-712 domain name of the USDC token, e.g. &#39;USD Coin&#39;. | 
**Version** | **string** | EIP-712 domain version of the USDC token, e.g. &#39;2&#39;. | 
**ChainId** | **int64** | EVM chain ID, as a JSON number. | 
**VerifyingContract** | **string** | The USDC token contract address, as a 0x-prefixed hex string. | 

## Methods

### NewPermitDomain

`func NewPermitDomain(name string, version string, chainId int64, verifyingContract string, ) *PermitDomain`

NewPermitDomain instantiates a new PermitDomain object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermitDomainWithDefaults

`func NewPermitDomainWithDefaults() *PermitDomain`

NewPermitDomainWithDefaults instantiates a new PermitDomain object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PermitDomain) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PermitDomain) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PermitDomain) SetName(v string)`

SetName sets Name field to given value.


### GetVersion

`func (o *PermitDomain) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *PermitDomain) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *PermitDomain) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetChainId

`func (o *PermitDomain) GetChainId() int64`

GetChainId returns the ChainId field if non-nil, zero value otherwise.

### GetChainIdOk

`func (o *PermitDomain) GetChainIdOk() (*int64, bool)`

GetChainIdOk returns a tuple with the ChainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChainId

`func (o *PermitDomain) SetChainId(v int64)`

SetChainId sets ChainId field to given value.


### GetVerifyingContract

`func (o *PermitDomain) GetVerifyingContract() string`

GetVerifyingContract returns the VerifyingContract field if non-nil, zero value otherwise.

### GetVerifyingContractOk

`func (o *PermitDomain) GetVerifyingContractOk() (*string, bool)`

GetVerifyingContractOk returns a tuple with the VerifyingContract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyingContract

`func (o *PermitDomain) SetVerifyingContract(v string)`

SetVerifyingContract sets VerifyingContract field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


