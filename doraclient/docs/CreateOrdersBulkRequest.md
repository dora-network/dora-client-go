# CreateOrdersBulkRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Orders** | [**[]CreateOrderRequest**](CreateOrderRequest.md) | Orders to submit, all with the same &#x60;order_book_id&#x60;. The maximum is configurable (matching.bulk_order_max_orders, default 20). | 
**Atomic** | Pointer to **bool** | Not currently supported: must be omitted or false, and &#x60;true&#x60; is rejected with 400. Orders are processed independently and partial creation is allowed. | [optional] [default to false]

## Methods

### NewCreateOrdersBulkRequest

`func NewCreateOrdersBulkRequest(orders []CreateOrderRequest, ) *CreateOrdersBulkRequest`

NewCreateOrdersBulkRequest instantiates a new CreateOrdersBulkRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrdersBulkRequestWithDefaults

`func NewCreateOrdersBulkRequestWithDefaults() *CreateOrdersBulkRequest`

NewCreateOrdersBulkRequestWithDefaults instantiates a new CreateOrdersBulkRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrders

`func (o *CreateOrdersBulkRequest) GetOrders() []CreateOrderRequest`

GetOrders returns the Orders field if non-nil, zero value otherwise.

### GetOrdersOk

`func (o *CreateOrdersBulkRequest) GetOrdersOk() (*[]CreateOrderRequest, bool)`

GetOrdersOk returns a tuple with the Orders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrders

`func (o *CreateOrdersBulkRequest) SetOrders(v []CreateOrderRequest)`

SetOrders sets Orders field to given value.


### GetAtomic

`func (o *CreateOrdersBulkRequest) GetAtomic() bool`

GetAtomic returns the Atomic field if non-nil, zero value otherwise.

### GetAtomicOk

`func (o *CreateOrdersBulkRequest) GetAtomicOk() (*bool, bool)`

GetAtomicOk returns a tuple with the Atomic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAtomic

`func (o *CreateOrdersBulkRequest) SetAtomic(v bool)`

SetAtomic sets Atomic field to given value.

### HasAtomic

`func (o *CreateOrdersBulkRequest) HasAtomic() bool`

HasAtomic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


