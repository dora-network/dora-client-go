# BulkOrderResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** | Position of the order in the request | 
**ClientOrderId** | Pointer to **string** |  | [optional] 
**OrderId** | Pointer to **string** | Present when the order was created | [optional] 
**Status** | **int32** | HTTP status the order would have received from POST /v1/orders: 201 when created | 
**Error** | Pointer to **string** | Present when the order was rejected | [optional] 

## Methods

### NewBulkOrderResult

`func NewBulkOrderResult(index int32, status int32, ) *BulkOrderResult`

NewBulkOrderResult instantiates a new BulkOrderResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkOrderResultWithDefaults

`func NewBulkOrderResultWithDefaults() *BulkOrderResult`

NewBulkOrderResultWithDefaults instantiates a new BulkOrderResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *BulkOrderResult) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *BulkOrderResult) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *BulkOrderResult) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetClientOrderId

`func (o *BulkOrderResult) GetClientOrderId() string`

GetClientOrderId returns the ClientOrderId field if non-nil, zero value otherwise.

### GetClientOrderIdOk

`func (o *BulkOrderResult) GetClientOrderIdOk() (*string, bool)`

GetClientOrderIdOk returns a tuple with the ClientOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientOrderId

`func (o *BulkOrderResult) SetClientOrderId(v string)`

SetClientOrderId sets ClientOrderId field to given value.

### HasClientOrderId

`func (o *BulkOrderResult) HasClientOrderId() bool`

HasClientOrderId returns a boolean if a field has been set.

### GetOrderId

`func (o *BulkOrderResult) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *BulkOrderResult) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *BulkOrderResult) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *BulkOrderResult) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetStatus

`func (o *BulkOrderResult) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BulkOrderResult) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BulkOrderResult) SetStatus(v int32)`

SetStatus sets Status field to given value.


### GetError

`func (o *BulkOrderResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *BulkOrderResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *BulkOrderResult) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *BulkOrderResult) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


