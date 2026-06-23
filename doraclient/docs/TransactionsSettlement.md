# TransactionsSettlement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TxId** | **string** |  | 
**UserId** | **string** |  | 
**TenantId** | **string** |  | 
**PositionId** | **string** |  | 
**TxKind** | **string** |  | 
**QuantityUsd** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**SettledAt** | Pointer to **time.Time** |  | [optional] 
**SettledBy** | Pointer to **string** |  | [optional] 

## Methods

### NewTransactionsSettlement

`func NewTransactionsSettlement(txId string, userId string, tenantId string, positionId string, txKind string, quantityUsd string, createdAt time.Time, ) *TransactionsSettlement`

NewTransactionsSettlement instantiates a new TransactionsSettlement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransactionsSettlementWithDefaults

`func NewTransactionsSettlementWithDefaults() *TransactionsSettlement`

NewTransactionsSettlementWithDefaults instantiates a new TransactionsSettlement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTxId

`func (o *TransactionsSettlement) GetTxId() string`

GetTxId returns the TxId field if non-nil, zero value otherwise.

### GetTxIdOk

`func (o *TransactionsSettlement) GetTxIdOk() (*string, bool)`

GetTxIdOk returns a tuple with the TxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTxId

`func (o *TransactionsSettlement) SetTxId(v string)`

SetTxId sets TxId field to given value.


### GetUserId

`func (o *TransactionsSettlement) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *TransactionsSettlement) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *TransactionsSettlement) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetTenantId

`func (o *TransactionsSettlement) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *TransactionsSettlement) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *TransactionsSettlement) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetPositionId

`func (o *TransactionsSettlement) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *TransactionsSettlement) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *TransactionsSettlement) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetTxKind

`func (o *TransactionsSettlement) GetTxKind() string`

GetTxKind returns the TxKind field if non-nil, zero value otherwise.

### GetTxKindOk

`func (o *TransactionsSettlement) GetTxKindOk() (*string, bool)`

GetTxKindOk returns a tuple with the TxKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTxKind

`func (o *TransactionsSettlement) SetTxKind(v string)`

SetTxKind sets TxKind field to given value.


### GetQuantityUsd

`func (o *TransactionsSettlement) GetQuantityUsd() string`

GetQuantityUsd returns the QuantityUsd field if non-nil, zero value otherwise.

### GetQuantityUsdOk

`func (o *TransactionsSettlement) GetQuantityUsdOk() (*string, bool)`

GetQuantityUsdOk returns a tuple with the QuantityUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityUsd

`func (o *TransactionsSettlement) SetQuantityUsd(v string)`

SetQuantityUsd sets QuantityUsd field to given value.


### GetCreatedAt

`func (o *TransactionsSettlement) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TransactionsSettlement) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TransactionsSettlement) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetSettledAt

`func (o *TransactionsSettlement) GetSettledAt() time.Time`

GetSettledAt returns the SettledAt field if non-nil, zero value otherwise.

### GetSettledAtOk

`func (o *TransactionsSettlement) GetSettledAtOk() (*time.Time, bool)`

GetSettledAtOk returns a tuple with the SettledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettledAt

`func (o *TransactionsSettlement) SetSettledAt(v time.Time)`

SetSettledAt sets SettledAt field to given value.

### HasSettledAt

`func (o *TransactionsSettlement) HasSettledAt() bool`

HasSettledAt returns a boolean if a field has been set.

### GetSettledBy

`func (o *TransactionsSettlement) GetSettledBy() string`

GetSettledBy returns the SettledBy field if non-nil, zero value otherwise.

### GetSettledByOk

`func (o *TransactionsSettlement) GetSettledByOk() (*string, bool)`

GetSettledByOk returns a tuple with the SettledBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettledBy

`func (o *TransactionsSettlement) SetSettledBy(v string)`

SetSettledBy sets SettledBy field to given value.

### HasSettledBy

`func (o *TransactionsSettlement) HasSettledBy() bool`

HasSettledBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


