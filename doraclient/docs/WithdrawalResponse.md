# WithdrawalResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WithdrawalId** | Pointer to **string** |  | [optional] 
**NetworkChainId** | Pointer to **int32** | Internal numeric identifier of the chain. | [optional] 
**NetworkName** | Pointer to **string** | Human-readable network name. | [optional] 
**ChainId** | Pointer to **string** | EVM chain ID. | [optional] 
**UserId** | Pointer to **string** |  | [optional] 
**AccountId** | Pointer to **string** |  | [optional] 
**ToAddress** | Pointer to **string** | Destination wallet address as a 0x-prefixed hex string. | [optional] 
**Quantity** | Pointer to **string** | Human-decimal USDC quantity to withdraw (base units divided by 10^6). | [optional] 
**Fee** | Pointer to **string** | Human-decimal USDC network fee (base units divided by 10^6). 0 until the requester locks a quoted fee as part of approval. | [optional] 
**Status** | Pointer to [**Web3WithdrawalStatus**](Web3WithdrawalStatus.md) |  | [optional] 
**TxHash** | Pointer to **string** | Broadcast withdraw() transaction hash as a 0x-prefixed hex string. Present from &#x60;BROADCAST&#x60; onward. | [optional] 
**FailureReason** | Pointer to **string** | Reason the withdrawal was rejected or failed. Present for REJECTED/FAILED. | [optional] 
**ApprovedBy** | Pointer to **string** | Admin who approved the withdrawal. Present once approved. | [optional] 
**ApprovedAt** | Pointer to **time.Time** | When the withdrawal was approved. Present once approved. | [optional] 
**SettlementTransactionId** | Pointer to **string** | Ledger settlement transaction. Present once confirmed. | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewWithdrawalResponse

`func NewWithdrawalResponse() *WithdrawalResponse`

NewWithdrawalResponse instantiates a new WithdrawalResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWithdrawalResponseWithDefaults

`func NewWithdrawalResponseWithDefaults() *WithdrawalResponse`

NewWithdrawalResponseWithDefaults instantiates a new WithdrawalResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWithdrawalId

`func (o *WithdrawalResponse) GetWithdrawalId() string`

GetWithdrawalId returns the WithdrawalId field if non-nil, zero value otherwise.

### GetWithdrawalIdOk

`func (o *WithdrawalResponse) GetWithdrawalIdOk() (*string, bool)`

GetWithdrawalIdOk returns a tuple with the WithdrawalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithdrawalId

`func (o *WithdrawalResponse) SetWithdrawalId(v string)`

SetWithdrawalId sets WithdrawalId field to given value.

### HasWithdrawalId

`func (o *WithdrawalResponse) HasWithdrawalId() bool`

HasWithdrawalId returns a boolean if a field has been set.

### GetNetworkChainId

`func (o *WithdrawalResponse) GetNetworkChainId() int32`

GetNetworkChainId returns the NetworkChainId field if non-nil, zero value otherwise.

### GetNetworkChainIdOk

`func (o *WithdrawalResponse) GetNetworkChainIdOk() (*int32, bool)`

GetNetworkChainIdOk returns a tuple with the NetworkChainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkChainId

`func (o *WithdrawalResponse) SetNetworkChainId(v int32)`

SetNetworkChainId sets NetworkChainId field to given value.

### HasNetworkChainId

`func (o *WithdrawalResponse) HasNetworkChainId() bool`

HasNetworkChainId returns a boolean if a field has been set.

### GetNetworkName

`func (o *WithdrawalResponse) GetNetworkName() string`

GetNetworkName returns the NetworkName field if non-nil, zero value otherwise.

### GetNetworkNameOk

`func (o *WithdrawalResponse) GetNetworkNameOk() (*string, bool)`

GetNetworkNameOk returns a tuple with the NetworkName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkName

`func (o *WithdrawalResponse) SetNetworkName(v string)`

SetNetworkName sets NetworkName field to given value.

### HasNetworkName

`func (o *WithdrawalResponse) HasNetworkName() bool`

HasNetworkName returns a boolean if a field has been set.

### GetChainId

`func (o *WithdrawalResponse) GetChainId() string`

GetChainId returns the ChainId field if non-nil, zero value otherwise.

### GetChainIdOk

`func (o *WithdrawalResponse) GetChainIdOk() (*string, bool)`

GetChainIdOk returns a tuple with the ChainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChainId

`func (o *WithdrawalResponse) SetChainId(v string)`

SetChainId sets ChainId field to given value.

### HasChainId

`func (o *WithdrawalResponse) HasChainId() bool`

HasChainId returns a boolean if a field has been set.

### GetUserId

`func (o *WithdrawalResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *WithdrawalResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *WithdrawalResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *WithdrawalResponse) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetAccountId

`func (o *WithdrawalResponse) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *WithdrawalResponse) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *WithdrawalResponse) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *WithdrawalResponse) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetToAddress

`func (o *WithdrawalResponse) GetToAddress() string`

GetToAddress returns the ToAddress field if non-nil, zero value otherwise.

### GetToAddressOk

`func (o *WithdrawalResponse) GetToAddressOk() (*string, bool)`

GetToAddressOk returns a tuple with the ToAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToAddress

`func (o *WithdrawalResponse) SetToAddress(v string)`

SetToAddress sets ToAddress field to given value.

### HasToAddress

`func (o *WithdrawalResponse) HasToAddress() bool`

HasToAddress returns a boolean if a field has been set.

### GetQuantity

`func (o *WithdrawalResponse) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *WithdrawalResponse) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *WithdrawalResponse) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *WithdrawalResponse) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetFee

`func (o *WithdrawalResponse) GetFee() string`

GetFee returns the Fee field if non-nil, zero value otherwise.

### GetFeeOk

`func (o *WithdrawalResponse) GetFeeOk() (*string, bool)`

GetFeeOk returns a tuple with the Fee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFee

`func (o *WithdrawalResponse) SetFee(v string)`

SetFee sets Fee field to given value.

### HasFee

`func (o *WithdrawalResponse) HasFee() bool`

HasFee returns a boolean if a field has been set.

### GetStatus

`func (o *WithdrawalResponse) GetStatus() Web3WithdrawalStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WithdrawalResponse) GetStatusOk() (*Web3WithdrawalStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WithdrawalResponse) SetStatus(v Web3WithdrawalStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *WithdrawalResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTxHash

`func (o *WithdrawalResponse) GetTxHash() string`

GetTxHash returns the TxHash field if non-nil, zero value otherwise.

### GetTxHashOk

`func (o *WithdrawalResponse) GetTxHashOk() (*string, bool)`

GetTxHashOk returns a tuple with the TxHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTxHash

`func (o *WithdrawalResponse) SetTxHash(v string)`

SetTxHash sets TxHash field to given value.

### HasTxHash

`func (o *WithdrawalResponse) HasTxHash() bool`

HasTxHash returns a boolean if a field has been set.

### GetFailureReason

`func (o *WithdrawalResponse) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *WithdrawalResponse) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *WithdrawalResponse) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *WithdrawalResponse) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### GetApprovedBy

`func (o *WithdrawalResponse) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *WithdrawalResponse) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *WithdrawalResponse) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *WithdrawalResponse) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.

### GetApprovedAt

`func (o *WithdrawalResponse) GetApprovedAt() time.Time`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *WithdrawalResponse) GetApprovedAtOk() (*time.Time, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *WithdrawalResponse) SetApprovedAt(v time.Time)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *WithdrawalResponse) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### GetSettlementTransactionId

`func (o *WithdrawalResponse) GetSettlementTransactionId() string`

GetSettlementTransactionId returns the SettlementTransactionId field if non-nil, zero value otherwise.

### GetSettlementTransactionIdOk

`func (o *WithdrawalResponse) GetSettlementTransactionIdOk() (*string, bool)`

GetSettlementTransactionIdOk returns a tuple with the SettlementTransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlementTransactionId

`func (o *WithdrawalResponse) SetSettlementTransactionId(v string)`

SetSettlementTransactionId sets SettlementTransactionId field to given value.

### HasSettlementTransactionId

`func (o *WithdrawalResponse) HasSettlementTransactionId() bool`

HasSettlementTransactionId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *WithdrawalResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WithdrawalResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WithdrawalResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WithdrawalResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *WithdrawalResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WithdrawalResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WithdrawalResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WithdrawalResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


