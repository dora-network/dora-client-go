# TransformedAssets

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Gained** | Pointer to **map[string]string** | Assets that have been gained by stablecoin equivalence transformations. They cannot be withdrawn from the platform until converted back to the original asset. | [optional] 
**Lost** | Pointer to **map[string]string** | Assets that have been lost by stablecoin equivalence transformations. They can be recovered by converting back any assets gained by stablecoin equivalence transformations. | [optional] 

## Methods

### NewTransformedAssets

`func NewTransformedAssets() *TransformedAssets`

NewTransformedAssets instantiates a new TransformedAssets object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransformedAssetsWithDefaults

`func NewTransformedAssetsWithDefaults() *TransformedAssets`

NewTransformedAssetsWithDefaults instantiates a new TransformedAssets object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGained

`func (o *TransformedAssets) GetGained() map[string]string`

GetGained returns the Gained field if non-nil, zero value otherwise.

### GetGainedOk

`func (o *TransformedAssets) GetGainedOk() (*map[string]string, bool)`

GetGainedOk returns a tuple with the Gained field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGained

`func (o *TransformedAssets) SetGained(v map[string]string)`

SetGained sets Gained field to given value.

### HasGained

`func (o *TransformedAssets) HasGained() bool`

HasGained returns a boolean if a field has been set.

### GetLost

`func (o *TransformedAssets) GetLost() map[string]string`

GetLost returns the Lost field if non-nil, zero value otherwise.

### GetLostOk

`func (o *TransformedAssets) GetLostOk() (*map[string]string, bool)`

GetLostOk returns a tuple with the Lost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLost

`func (o *TransformedAssets) SetLost(v map[string]string)`

SetLost sets Lost field to given value.

### HasLost

`func (o *TransformedAssets) HasLost() bool`

HasLost returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


