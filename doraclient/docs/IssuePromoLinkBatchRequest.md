# IssuePromoLinkBatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SourceType** | [**PromoSourceType**](PromoSourceType.md) |  | 
**SourceId** | **string** |  | 
**SourceName** | Pointer to **string** |  | [optional] 
**Allocation** | **int32** | Cannot exceed the configured max_links_per_batch or remaining campaign capacity. | 
**Note** | Pointer to **string** |  | [optional] 
**ExpiresAt** | Pointer to **time.Time** | Defaults to challenge end and must fall between challenge start and end in the future. | [optional] 

## Methods

### NewIssuePromoLinkBatchRequest

`func NewIssuePromoLinkBatchRequest(sourceType PromoSourceType, sourceId string, allocation int32, ) *IssuePromoLinkBatchRequest`

NewIssuePromoLinkBatchRequest instantiates a new IssuePromoLinkBatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIssuePromoLinkBatchRequestWithDefaults

`func NewIssuePromoLinkBatchRequestWithDefaults() *IssuePromoLinkBatchRequest`

NewIssuePromoLinkBatchRequestWithDefaults instantiates a new IssuePromoLinkBatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSourceType

`func (o *IssuePromoLinkBatchRequest) GetSourceType() PromoSourceType`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *IssuePromoLinkBatchRequest) GetSourceTypeOk() (*PromoSourceType, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *IssuePromoLinkBatchRequest) SetSourceType(v PromoSourceType)`

SetSourceType sets SourceType field to given value.


### GetSourceId

`func (o *IssuePromoLinkBatchRequest) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *IssuePromoLinkBatchRequest) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *IssuePromoLinkBatchRequest) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.


### GetSourceName

`func (o *IssuePromoLinkBatchRequest) GetSourceName() string`

GetSourceName returns the SourceName field if non-nil, zero value otherwise.

### GetSourceNameOk

`func (o *IssuePromoLinkBatchRequest) GetSourceNameOk() (*string, bool)`

GetSourceNameOk returns a tuple with the SourceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceName

`func (o *IssuePromoLinkBatchRequest) SetSourceName(v string)`

SetSourceName sets SourceName field to given value.

### HasSourceName

`func (o *IssuePromoLinkBatchRequest) HasSourceName() bool`

HasSourceName returns a boolean if a field has been set.

### GetAllocation

`func (o *IssuePromoLinkBatchRequest) GetAllocation() int32`

GetAllocation returns the Allocation field if non-nil, zero value otherwise.

### GetAllocationOk

`func (o *IssuePromoLinkBatchRequest) GetAllocationOk() (*int32, bool)`

GetAllocationOk returns a tuple with the Allocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocation

`func (o *IssuePromoLinkBatchRequest) SetAllocation(v int32)`

SetAllocation sets Allocation field to given value.


### GetNote

`func (o *IssuePromoLinkBatchRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *IssuePromoLinkBatchRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *IssuePromoLinkBatchRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *IssuePromoLinkBatchRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetExpiresAt

`func (o *IssuePromoLinkBatchRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *IssuePromoLinkBatchRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *IssuePromoLinkBatchRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *IssuePromoLinkBatchRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


