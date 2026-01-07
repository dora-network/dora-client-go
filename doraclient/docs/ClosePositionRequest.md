# ClosePositionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PositionId** | **string** |  | 
**OrderBookId** | **string** |  | 

## Methods

### NewClosePositionRequest

`func NewClosePositionRequest(positionId string, orderBookId string, ) *ClosePositionRequest`

NewClosePositionRequest instantiates a new ClosePositionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClosePositionRequestWithDefaults

`func NewClosePositionRequestWithDefaults() *ClosePositionRequest`

NewClosePositionRequestWithDefaults instantiates a new ClosePositionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPositionId

`func (o *ClosePositionRequest) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *ClosePositionRequest) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *ClosePositionRequest) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetOrderBookId

`func (o *ClosePositionRequest) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *ClosePositionRequest) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *ClosePositionRequest) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


