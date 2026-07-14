# DepositResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NetworkChainId** | **int32** | Internal numeric identifier of the chain. | 
**NetworkName** | **string** | Human-readable network name. | 
**ChainId** | **string** | EVM chain ID. | 
**TxHash** | **string** | Transaction hash as a 0x-prefixed hex string. | 
**LogIndex** | **int32** | Index of the log within the transaction. | 
**BlockNumber** | **int64** |  | 
**BlockTime** | **time.Time** |  | 
**ContractAddress** | **string** | Vault contract address as a 0x-prefixed hex string. | 
**DepositorAddress** | **string** | Address that made the deposit, as a 0x-prefixed hex string. | 
**UserId** | **string** |  | 
**Quantity** | **string** | Human-decimal USDC value (base units divided by 10^6). | 
**ClientReferenceId** | Pointer to **string** | Optional client-supplied reference, as a 0x-prefixed hex string. | [optional] 
**Status** | [**Web3EventStatus**](Web3EventStatus.md) |  | 
**TransactionId** | Pointer to **string** | Internal transaction ID, present once the deposit has been credited. | [optional] 
**ObservedAt** | **time.Time** |  | 

## Methods

### NewDepositResponse

`func NewDepositResponse(networkChainId int32, networkName string, chainId string, txHash string, logIndex int32, blockNumber int64, blockTime time.Time, contractAddress string, depositorAddress string, userId string, quantity string, status Web3EventStatus, observedAt time.Time, ) *DepositResponse`

NewDepositResponse instantiates a new DepositResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDepositResponseWithDefaults

`func NewDepositResponseWithDefaults() *DepositResponse`

NewDepositResponseWithDefaults instantiates a new DepositResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetworkChainId

`func (o *DepositResponse) GetNetworkChainId() int32`

GetNetworkChainId returns the NetworkChainId field if non-nil, zero value otherwise.

### GetNetworkChainIdOk

`func (o *DepositResponse) GetNetworkChainIdOk() (*int32, bool)`

GetNetworkChainIdOk returns a tuple with the NetworkChainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkChainId

`func (o *DepositResponse) SetNetworkChainId(v int32)`

SetNetworkChainId sets NetworkChainId field to given value.


### GetNetworkName

`func (o *DepositResponse) GetNetworkName() string`

GetNetworkName returns the NetworkName field if non-nil, zero value otherwise.

### GetNetworkNameOk

`func (o *DepositResponse) GetNetworkNameOk() (*string, bool)`

GetNetworkNameOk returns a tuple with the NetworkName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkName

`func (o *DepositResponse) SetNetworkName(v string)`

SetNetworkName sets NetworkName field to given value.


### GetChainId

`func (o *DepositResponse) GetChainId() string`

GetChainId returns the ChainId field if non-nil, zero value otherwise.

### GetChainIdOk

`func (o *DepositResponse) GetChainIdOk() (*string, bool)`

GetChainIdOk returns a tuple with the ChainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChainId

`func (o *DepositResponse) SetChainId(v string)`

SetChainId sets ChainId field to given value.


### GetTxHash

`func (o *DepositResponse) GetTxHash() string`

GetTxHash returns the TxHash field if non-nil, zero value otherwise.

### GetTxHashOk

`func (o *DepositResponse) GetTxHashOk() (*string, bool)`

GetTxHashOk returns a tuple with the TxHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTxHash

`func (o *DepositResponse) SetTxHash(v string)`

SetTxHash sets TxHash field to given value.


### GetLogIndex

`func (o *DepositResponse) GetLogIndex() int32`

GetLogIndex returns the LogIndex field if non-nil, zero value otherwise.

### GetLogIndexOk

`func (o *DepositResponse) GetLogIndexOk() (*int32, bool)`

GetLogIndexOk returns a tuple with the LogIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogIndex

`func (o *DepositResponse) SetLogIndex(v int32)`

SetLogIndex sets LogIndex field to given value.


### GetBlockNumber

`func (o *DepositResponse) GetBlockNumber() int64`

GetBlockNumber returns the BlockNumber field if non-nil, zero value otherwise.

### GetBlockNumberOk

`func (o *DepositResponse) GetBlockNumberOk() (*int64, bool)`

GetBlockNumberOk returns a tuple with the BlockNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockNumber

`func (o *DepositResponse) SetBlockNumber(v int64)`

SetBlockNumber sets BlockNumber field to given value.


### GetBlockTime

`func (o *DepositResponse) GetBlockTime() time.Time`

GetBlockTime returns the BlockTime field if non-nil, zero value otherwise.

### GetBlockTimeOk

`func (o *DepositResponse) GetBlockTimeOk() (*time.Time, bool)`

GetBlockTimeOk returns a tuple with the BlockTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockTime

`func (o *DepositResponse) SetBlockTime(v time.Time)`

SetBlockTime sets BlockTime field to given value.


### GetContractAddress

`func (o *DepositResponse) GetContractAddress() string`

GetContractAddress returns the ContractAddress field if non-nil, zero value otherwise.

### GetContractAddressOk

`func (o *DepositResponse) GetContractAddressOk() (*string, bool)`

GetContractAddressOk returns a tuple with the ContractAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractAddress

`func (o *DepositResponse) SetContractAddress(v string)`

SetContractAddress sets ContractAddress field to given value.


### GetDepositorAddress

`func (o *DepositResponse) GetDepositorAddress() string`

GetDepositorAddress returns the DepositorAddress field if non-nil, zero value otherwise.

### GetDepositorAddressOk

`func (o *DepositResponse) GetDepositorAddressOk() (*string, bool)`

GetDepositorAddressOk returns a tuple with the DepositorAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositorAddress

`func (o *DepositResponse) SetDepositorAddress(v string)`

SetDepositorAddress sets DepositorAddress field to given value.


### GetUserId

`func (o *DepositResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *DepositResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *DepositResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetQuantity

`func (o *DepositResponse) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *DepositResponse) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *DepositResponse) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetClientReferenceId

`func (o *DepositResponse) GetClientReferenceId() string`

GetClientReferenceId returns the ClientReferenceId field if non-nil, zero value otherwise.

### GetClientReferenceIdOk

`func (o *DepositResponse) GetClientReferenceIdOk() (*string, bool)`

GetClientReferenceIdOk returns a tuple with the ClientReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientReferenceId

`func (o *DepositResponse) SetClientReferenceId(v string)`

SetClientReferenceId sets ClientReferenceId field to given value.

### HasClientReferenceId

`func (o *DepositResponse) HasClientReferenceId() bool`

HasClientReferenceId returns a boolean if a field has been set.

### GetStatus

`func (o *DepositResponse) GetStatus() Web3EventStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DepositResponse) GetStatusOk() (*Web3EventStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DepositResponse) SetStatus(v Web3EventStatus)`

SetStatus sets Status field to given value.


### GetTransactionId

`func (o *DepositResponse) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *DepositResponse) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *DepositResponse) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.

### HasTransactionId

`func (o *DepositResponse) HasTransactionId() bool`

HasTransactionId returns a boolean if a field has been set.

### GetObservedAt

`func (o *DepositResponse) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *DepositResponse) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *DepositResponse) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


