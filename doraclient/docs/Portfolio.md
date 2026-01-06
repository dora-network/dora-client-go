# Portfolio

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | Pointer to **string** |  | [optional] 
**Position** | Pointer to [**map[string]map[string]Position**](map.md) |  | [optional] 
**NetStablecoinEquivalence** | Pointer to [**TransformedAssets**](TransformedAssets.md) |  | [optional] 

## Methods

### NewPortfolio

`func NewPortfolio() *Portfolio`

NewPortfolio instantiates a new Portfolio object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortfolioWithDefaults

`func NewPortfolioWithDefaults() *Portfolio`

NewPortfolioWithDefaults instantiates a new Portfolio object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *Portfolio) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Portfolio) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Portfolio) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *Portfolio) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetPosition

`func (o *Portfolio) GetPosition() map[string]map[string]Position`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *Portfolio) GetPositionOk() (*map[string]map[string]Position, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *Portfolio) SetPosition(v map[string]map[string]Position)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *Portfolio) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetNetStablecoinEquivalence

`func (o *Portfolio) GetNetStablecoinEquivalence() TransformedAssets`

GetNetStablecoinEquivalence returns the NetStablecoinEquivalence field if non-nil, zero value otherwise.

### GetNetStablecoinEquivalenceOk

`func (o *Portfolio) GetNetStablecoinEquivalenceOk() (*TransformedAssets, bool)`

GetNetStablecoinEquivalenceOk returns a tuple with the NetStablecoinEquivalence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetStablecoinEquivalence

`func (o *Portfolio) SetNetStablecoinEquivalence(v TransformedAssets)`

SetNetStablecoinEquivalence sets NetStablecoinEquivalence field to given value.

### HasNetStablecoinEquivalence

`func (o *Portfolio) HasNetStablecoinEquivalence() bool`

HasNetStablecoinEquivalence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


