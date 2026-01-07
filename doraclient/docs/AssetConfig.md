# AssetConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**Price** | **string** | if an asset is a CURRENCY, set 1 USD price,If an asset is a BOND and the price isn&#39;t found, set to 0 USD   You can find price details on /price/asset/{asset_id} route | 

## Methods

### NewAssetConfig

`func NewAssetConfig(assetId string, price string, ) *AssetConfig`

NewAssetConfig instantiates a new AssetConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetConfigWithDefaults

`func NewAssetConfigWithDefaults() *AssetConfig`

NewAssetConfigWithDefaults instantiates a new AssetConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetConfig) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetConfig) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetConfig) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetPrice

`func (o *AssetConfig) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *AssetConfig) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *AssetConfig) SetPrice(v string)`

SetPrice sets Price field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


