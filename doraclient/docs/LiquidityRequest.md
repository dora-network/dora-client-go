# LiquidityRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PositionId** | **string** |  | 
**Quantity** | **string** |  | 

## Methods

### NewLiquidityRequest

`func NewLiquidityRequest(positionId string, quantity string, ) *LiquidityRequest`

NewLiquidityRequest instantiates a new LiquidityRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLiquidityRequestWithDefaults

`func NewLiquidityRequestWithDefaults() *LiquidityRequest`

NewLiquidityRequestWithDefaults instantiates a new LiquidityRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPositionId

`func (o *LiquidityRequest) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *LiquidityRequest) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *LiquidityRequest) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetQuantity

`func (o *LiquidityRequest) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *LiquidityRequest) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *LiquidityRequest) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


