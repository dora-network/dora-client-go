# PromoLinkBatchSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**SourceType** | [**PromoSourceType**](PromoSourceType.md) |  | 
**SourceId** | **string** |  | 
**SourceName** | **string** |  | 
**Allocation** | **int32** |  | 
**Issued** | **int64** |  | 
**Claimed** | **int64** |  | 
**Revoked** | **int64** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewPromoLinkBatchSummary

`func NewPromoLinkBatchSummary(id string, sourceType PromoSourceType, sourceId string, sourceName string, allocation int32, issued int64, claimed int64, revoked int64, createdAt time.Time, ) *PromoLinkBatchSummary`

NewPromoLinkBatchSummary instantiates a new PromoLinkBatchSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromoLinkBatchSummaryWithDefaults

`func NewPromoLinkBatchSummaryWithDefaults() *PromoLinkBatchSummary`

NewPromoLinkBatchSummaryWithDefaults instantiates a new PromoLinkBatchSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PromoLinkBatchSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PromoLinkBatchSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PromoLinkBatchSummary) SetId(v string)`

SetId sets Id field to given value.


### GetSourceType

`func (o *PromoLinkBatchSummary) GetSourceType() PromoSourceType`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *PromoLinkBatchSummary) GetSourceTypeOk() (*PromoSourceType, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *PromoLinkBatchSummary) SetSourceType(v PromoSourceType)`

SetSourceType sets SourceType field to given value.


### GetSourceId

`func (o *PromoLinkBatchSummary) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *PromoLinkBatchSummary) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *PromoLinkBatchSummary) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.


### GetSourceName

`func (o *PromoLinkBatchSummary) GetSourceName() string`

GetSourceName returns the SourceName field if non-nil, zero value otherwise.

### GetSourceNameOk

`func (o *PromoLinkBatchSummary) GetSourceNameOk() (*string, bool)`

GetSourceNameOk returns a tuple with the SourceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceName

`func (o *PromoLinkBatchSummary) SetSourceName(v string)`

SetSourceName sets SourceName field to given value.


### GetAllocation

`func (o *PromoLinkBatchSummary) GetAllocation() int32`

GetAllocation returns the Allocation field if non-nil, zero value otherwise.

### GetAllocationOk

`func (o *PromoLinkBatchSummary) GetAllocationOk() (*int32, bool)`

GetAllocationOk returns a tuple with the Allocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocation

`func (o *PromoLinkBatchSummary) SetAllocation(v int32)`

SetAllocation sets Allocation field to given value.


### GetIssued

`func (o *PromoLinkBatchSummary) GetIssued() int64`

GetIssued returns the Issued field if non-nil, zero value otherwise.

### GetIssuedOk

`func (o *PromoLinkBatchSummary) GetIssuedOk() (*int64, bool)`

GetIssuedOk returns a tuple with the Issued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssued

`func (o *PromoLinkBatchSummary) SetIssued(v int64)`

SetIssued sets Issued field to given value.


### GetClaimed

`func (o *PromoLinkBatchSummary) GetClaimed() int64`

GetClaimed returns the Claimed field if non-nil, zero value otherwise.

### GetClaimedOk

`func (o *PromoLinkBatchSummary) GetClaimedOk() (*int64, bool)`

GetClaimedOk returns a tuple with the Claimed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimed

`func (o *PromoLinkBatchSummary) SetClaimed(v int64)`

SetClaimed sets Claimed field to given value.


### GetRevoked

`func (o *PromoLinkBatchSummary) GetRevoked() int64`

GetRevoked returns the Revoked field if non-nil, zero value otherwise.

### GetRevokedOk

`func (o *PromoLinkBatchSummary) GetRevokedOk() (*int64, bool)`

GetRevokedOk returns a tuple with the Revoked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevoked

`func (o *PromoLinkBatchSummary) SetRevoked(v int64)`

SetRevoked sets Revoked field to given value.


### GetCreatedAt

`func (o *PromoLinkBatchSummary) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PromoLinkBatchSummary) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PromoLinkBatchSummary) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


