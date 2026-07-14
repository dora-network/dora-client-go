# DepositInstructionForChain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NetworkName** | **string** | Human-readable network name, e.g. &#39;Ethereum Mainnet&#39;. | 
**ChainId** | **string** | EVM chain ID. | 
**ContractAddress** | **string** | The DoraUSDCVault contract address for this chain, as a 0x-prefixed hex string. | 
**UsdcAddress** | **string** | The ERC-20 USDC token contract on this chain, as a 0x-prefixed hex string. It is the verifying contract of the permit; the spender granted by the permit is contract_address (the vault). | 
**Approval** | [**PermitTypedData**](PermitTypedData.md) |  | 
**Deposit** | [**DepositCall**](DepositCall.md) |  | 

## Methods

### NewDepositInstructionForChain

`func NewDepositInstructionForChain(networkName string, chainId string, contractAddress string, usdcAddress string, approval PermitTypedData, deposit DepositCall, ) *DepositInstructionForChain`

NewDepositInstructionForChain instantiates a new DepositInstructionForChain object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDepositInstructionForChainWithDefaults

`func NewDepositInstructionForChainWithDefaults() *DepositInstructionForChain`

NewDepositInstructionForChainWithDefaults instantiates a new DepositInstructionForChain object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetworkName

`func (o *DepositInstructionForChain) GetNetworkName() string`

GetNetworkName returns the NetworkName field if non-nil, zero value otherwise.

### GetNetworkNameOk

`func (o *DepositInstructionForChain) GetNetworkNameOk() (*string, bool)`

GetNetworkNameOk returns a tuple with the NetworkName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkName

`func (o *DepositInstructionForChain) SetNetworkName(v string)`

SetNetworkName sets NetworkName field to given value.


### GetChainId

`func (o *DepositInstructionForChain) GetChainId() string`

GetChainId returns the ChainId field if non-nil, zero value otherwise.

### GetChainIdOk

`func (o *DepositInstructionForChain) GetChainIdOk() (*string, bool)`

GetChainIdOk returns a tuple with the ChainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChainId

`func (o *DepositInstructionForChain) SetChainId(v string)`

SetChainId sets ChainId field to given value.


### GetContractAddress

`func (o *DepositInstructionForChain) GetContractAddress() string`

GetContractAddress returns the ContractAddress field if non-nil, zero value otherwise.

### GetContractAddressOk

`func (o *DepositInstructionForChain) GetContractAddressOk() (*string, bool)`

GetContractAddressOk returns a tuple with the ContractAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractAddress

`func (o *DepositInstructionForChain) SetContractAddress(v string)`

SetContractAddress sets ContractAddress field to given value.


### GetUsdcAddress

`func (o *DepositInstructionForChain) GetUsdcAddress() string`

GetUsdcAddress returns the UsdcAddress field if non-nil, zero value otherwise.

### GetUsdcAddressOk

`func (o *DepositInstructionForChain) GetUsdcAddressOk() (*string, bool)`

GetUsdcAddressOk returns a tuple with the UsdcAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsdcAddress

`func (o *DepositInstructionForChain) SetUsdcAddress(v string)`

SetUsdcAddress sets UsdcAddress field to given value.


### GetApproval

`func (o *DepositInstructionForChain) GetApproval() PermitTypedData`

GetApproval returns the Approval field if non-nil, zero value otherwise.

### GetApprovalOk

`func (o *DepositInstructionForChain) GetApprovalOk() (*PermitTypedData, bool)`

GetApprovalOk returns a tuple with the Approval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApproval

`func (o *DepositInstructionForChain) SetApproval(v PermitTypedData)`

SetApproval sets Approval field to given value.


### GetDeposit

`func (o *DepositInstructionForChain) GetDeposit() DepositCall`

GetDeposit returns the Deposit field if non-nil, zero value otherwise.

### GetDepositOk

`func (o *DepositInstructionForChain) GetDepositOk() (*DepositCall, bool)`

GetDepositOk returns a tuple with the Deposit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeposit

`func (o *DepositInstructionForChain) SetDeposit(v DepositCall)`

SetDeposit sets Deposit field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


