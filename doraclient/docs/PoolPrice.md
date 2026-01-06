# PoolPrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PoolId** | Pointer to **string** |  | [optional] 
**Price** | Pointer to **float64** |  | [optional] 
**Timestamp** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewPoolPrice

`func NewPoolPrice() *PoolPrice`

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

### HasPoolId

`func (o *PoolPrice) HasPoolId() bool`

HasPoolId returns a boolean if a field has been set.

### GetPrice

`func (o *PoolPrice) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *PoolPrice) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *PoolPrice) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *PoolPrice) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

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

### HasTimestamp

`func (o *PoolPrice) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


