# AssetConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**Price** | **string** | if an asset is a CURRENCY, set 1 USD price,If an asset is a BOND and the price isn&#39;t found, set to 0 USD   You can find price details on /price/asset/{asset_id} route | 
**ModuleAvailable** | Pointer to **string** | Optional leverage module available balance for this asset, from /v1/ledger/module/{asset_id}. If provided, validation rejects orders that need to borrow more than the module can supply. | [optional] 
**ModuleSupplied** | Pointer to **string** | Optional leverage module total supplied balance for this asset, from /v1/ledger/module/{asset_id}. Required with module_available when the asset has max_utilization. | [optional] 
**ModuleBorrowed** | Pointer to **string** | Optional leverage module borrowed balance for this asset, from /v1/ledger/module/{asset_id}. Required with module_available when the asset has max_utilization. | [optional] 

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


### GetModuleAvailable

`func (o *AssetConfig) GetModuleAvailable() string`

GetModuleAvailable returns the ModuleAvailable field if non-nil, zero value otherwise.

### GetModuleAvailableOk

`func (o *AssetConfig) GetModuleAvailableOk() (*string, bool)`

GetModuleAvailableOk returns a tuple with the ModuleAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModuleAvailable

`func (o *AssetConfig) SetModuleAvailable(v string)`

SetModuleAvailable sets ModuleAvailable field to given value.

### HasModuleAvailable

`func (o *AssetConfig) HasModuleAvailable() bool`

HasModuleAvailable returns a boolean if a field has been set.

### GetModuleSupplied

`func (o *AssetConfig) GetModuleSupplied() string`

GetModuleSupplied returns the ModuleSupplied field if non-nil, zero value otherwise.

### GetModuleSuppliedOk

`func (o *AssetConfig) GetModuleSuppliedOk() (*string, bool)`

GetModuleSuppliedOk returns a tuple with the ModuleSupplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModuleSupplied

`func (o *AssetConfig) SetModuleSupplied(v string)`

SetModuleSupplied sets ModuleSupplied field to given value.

### HasModuleSupplied

`func (o *AssetConfig) HasModuleSupplied() bool`

HasModuleSupplied returns a boolean if a field has been set.

### GetModuleBorrowed

`func (o *AssetConfig) GetModuleBorrowed() string`

GetModuleBorrowed returns the ModuleBorrowed field if non-nil, zero value otherwise.

### GetModuleBorrowedOk

`func (o *AssetConfig) GetModuleBorrowedOk() (*string, bool)`

GetModuleBorrowedOk returns a tuple with the ModuleBorrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModuleBorrowed

`func (o *AssetConfig) SetModuleBorrowed(v string)`

SetModuleBorrowed sets ModuleBorrowed field to given value.

### HasModuleBorrowed

`func (o *AssetConfig) HasModuleBorrowed() bool`

HasModuleBorrowed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


