# Transaction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**Kind** | [**TransactionKind**](TransactionKind.md) |  | 
**Asset0** | **string** |  | 
**Quantity0** | **string** |  | 
**Quantity1** | **string** |  | 
**Asset1** | **string** |  | 
**UserId** | **string** |  | 
**AdminUserId** | **string** |  | 
**OrderSide** | [**Side**](Side.md) |  | 

## Methods

### NewTransaction

`func NewTransaction(id string, createdAt time.Time, kind TransactionKind, asset0 string, quantity0 string, quantity1 string, asset1 string, userId string, adminUserId string, orderSide Side, ) *Transaction`

NewTransaction instantiates a new Transaction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransactionWithDefaults

`func NewTransactionWithDefaults() *Transaction`

NewTransactionWithDefaults instantiates a new Transaction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Transaction) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Transaction) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Transaction) SetId(v string)`

SetId sets Id field to given value.


### GetCreatedAt

`func (o *Transaction) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Transaction) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Transaction) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetKind

`func (o *Transaction) GetKind() TransactionKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Transaction) GetKindOk() (*TransactionKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Transaction) SetKind(v TransactionKind)`

SetKind sets Kind field to given value.


### GetAsset0

`func (o *Transaction) GetAsset0() string`

GetAsset0 returns the Asset0 field if non-nil, zero value otherwise.

### GetAsset0Ok

`func (o *Transaction) GetAsset0Ok() (*string, bool)`

GetAsset0Ok returns a tuple with the Asset0 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsset0

`func (o *Transaction) SetAsset0(v string)`

SetAsset0 sets Asset0 field to given value.


### GetQuantity0

`func (o *Transaction) GetQuantity0() string`

GetQuantity0 returns the Quantity0 field if non-nil, zero value otherwise.

### GetQuantity0Ok

`func (o *Transaction) GetQuantity0Ok() (*string, bool)`

GetQuantity0Ok returns a tuple with the Quantity0 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity0

`func (o *Transaction) SetQuantity0(v string)`

SetQuantity0 sets Quantity0 field to given value.


### GetQuantity1

`func (o *Transaction) GetQuantity1() string`

GetQuantity1 returns the Quantity1 field if non-nil, zero value otherwise.

### GetQuantity1Ok

`func (o *Transaction) GetQuantity1Ok() (*string, bool)`

GetQuantity1Ok returns a tuple with the Quantity1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity1

`func (o *Transaction) SetQuantity1(v string)`

SetQuantity1 sets Quantity1 field to given value.


### GetAsset1

`func (o *Transaction) GetAsset1() string`

GetAsset1 returns the Asset1 field if non-nil, zero value otherwise.

### GetAsset1Ok

`func (o *Transaction) GetAsset1Ok() (*string, bool)`

GetAsset1Ok returns a tuple with the Asset1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsset1

`func (o *Transaction) SetAsset1(v string)`

SetAsset1 sets Asset1 field to given value.


### GetUserId

`func (o *Transaction) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Transaction) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Transaction) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetAdminUserId

`func (o *Transaction) GetAdminUserId() string`

GetAdminUserId returns the AdminUserId field if non-nil, zero value otherwise.

### GetAdminUserIdOk

`func (o *Transaction) GetAdminUserIdOk() (*string, bool)`

GetAdminUserIdOk returns a tuple with the AdminUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminUserId

`func (o *Transaction) SetAdminUserId(v string)`

SetAdminUserId sets AdminUserId field to given value.


### GetOrderSide

`func (o *Transaction) GetOrderSide() Side`

GetOrderSide returns the OrderSide field if non-nil, zero value otherwise.

### GetOrderSideOk

`func (o *Transaction) GetOrderSideOk() (*Side, bool)`

GetOrderSideOk returns a tuple with the OrderSide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderSide

`func (o *Transaction) SetOrderSide(v Side)`

SetOrderSide sets OrderSide field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


