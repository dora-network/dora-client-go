# PositionAsset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**Kind** | [**AssetKind**](AssetKind.md) |  | 
**Borrowed** | **string** |  | 
**ImpendingBorrows** | **string** |  | 
**Available** | **string** |  | 
**Locked** | **string** |  | 

## Methods

### NewPositionAsset

`func NewPositionAsset(assetId string, kind AssetKind, borrowed string, impendingBorrows string, available string, locked string, ) *PositionAsset`

NewPositionAsset instantiates a new PositionAsset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPositionAssetWithDefaults

`func NewPositionAssetWithDefaults() *PositionAsset`

NewPositionAssetWithDefaults instantiates a new PositionAsset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *PositionAsset) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *PositionAsset) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *PositionAsset) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetKind

`func (o *PositionAsset) GetKind() AssetKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *PositionAsset) GetKindOk() (*AssetKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *PositionAsset) SetKind(v AssetKind)`

SetKind sets Kind field to given value.


### GetBorrowed

`func (o *PositionAsset) GetBorrowed() string`

GetBorrowed returns the Borrowed field if non-nil, zero value otherwise.

### GetBorrowedOk

`func (o *PositionAsset) GetBorrowedOk() (*string, bool)`

GetBorrowedOk returns a tuple with the Borrowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowed

`func (o *PositionAsset) SetBorrowed(v string)`

SetBorrowed sets Borrowed field to given value.


### GetImpendingBorrows

`func (o *PositionAsset) GetImpendingBorrows() string`

GetImpendingBorrows returns the ImpendingBorrows field if non-nil, zero value otherwise.

### GetImpendingBorrowsOk

`func (o *PositionAsset) GetImpendingBorrowsOk() (*string, bool)`

GetImpendingBorrowsOk returns a tuple with the ImpendingBorrows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpendingBorrows

`func (o *PositionAsset) SetImpendingBorrows(v string)`

SetImpendingBorrows sets ImpendingBorrows field to given value.


### GetAvailable

`func (o *PositionAsset) GetAvailable() string`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *PositionAsset) GetAvailableOk() (*string, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *PositionAsset) SetAvailable(v string)`

SetAvailable sets Available field to given value.


### GetLocked

`func (o *PositionAsset) GetLocked() string`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *PositionAsset) GetLockedOk() (*string, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *PositionAsset) SetLocked(v string)`

SetLocked sets Locked field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


