# PoolPrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PoolId** | **string** |  | 
**Price** | **string** |  | 
**Timestamp** | **time.Time** |  | 

## Methods

### NewPoolPrice

`func NewPoolPrice(poolId string, price string, timestamp time.Time, ) *PoolPrice`

NewPoolPrice instantiates a new PoolPrice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoolPriceWithDefaults

`func NewPoolPriceWithDefaults() *PoolPrice`

NewPoolPriceWithDefaults instantiates a new PoolPrice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPoolId

`func (o *PoolPrice) GetPoolId() string`

GetPoolId returns the PoolId field if non-nil, zero value otherwise.

### GetPoolIdOk

`func (o *PoolPrice) GetPoolIdOk() (*string, bool)`

GetPoolIdOk returns a tuple with the PoolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolId

`func (o *PoolPrice) SetPoolId(v string)`

SetPoolId sets PoolId field to given value.


### GetPrice

`func (o *PoolPrice) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *PoolPrice) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *PoolPrice) SetPrice(v string)`

SetPrice sets Price field to given value.


### GetTimestamp

`func (o *PoolPrice) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *PoolPrice) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *PoolPrice) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


