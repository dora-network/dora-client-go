# IssuePromoLinkBatchResponseAllOfData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BatchId** | **string** |  | 
**SourceId** | **string** |  | 
**Allocation** | **int32** |  | 
**Links** | [**[]IssuedPromoLink**](IssuedPromoLink.md) |  | 

## Methods

### NewIssuePromoLinkBatchResponseAllOfData

`func NewIssuePromoLinkBatchResponseAllOfData(batchId string, sourceId string, allocation int32, links []IssuedPromoLink, ) *IssuePromoLinkBatchResponseAllOfData`

NewIssuePromoLinkBatchResponseAllOfData instantiates a new IssuePromoLinkBatchResponseAllOfData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIssuePromoLinkBatchResponseAllOfDataWithDefaults

`func NewIssuePromoLinkBatchResponseAllOfDataWithDefaults() *IssuePromoLinkBatchResponseAllOfData`

NewIssuePromoLinkBatchResponseAllOfDataWithDefaults instantiates a new IssuePromoLinkBatchResponseAllOfData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBatchId

`func (o *IssuePromoLinkBatchResponseAllOfData) GetBatchId() string`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *IssuePromoLinkBatchResponseAllOfData) GetBatchIdOk() (*string, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *IssuePromoLinkBatchResponseAllOfData) SetBatchId(v string)`

SetBatchId sets BatchId field to given value.


### GetSourceId

`func (o *IssuePromoLinkBatchResponseAllOfData) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *IssuePromoLinkBatchResponseAllOfData) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *IssuePromoLinkBatchResponseAllOfData) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.


### GetAllocation

`func (o *IssuePromoLinkBatchResponseAllOfData) GetAllocation() int32`

GetAllocation returns the Allocation field if non-nil, zero value otherwise.

### GetAllocationOk

`func (o *IssuePromoLinkBatchResponseAllOfData) GetAllocationOk() (*int32, bool)`

GetAllocationOk returns a tuple with the Allocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocation

`func (o *IssuePromoLinkBatchResponseAllOfData) SetAllocation(v int32)`

SetAllocation sets Allocation field to given value.


### GetLinks

`func (o *IssuePromoLinkBatchResponseAllOfData) GetLinks() []IssuedPromoLink`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *IssuePromoLinkBatchResponseAllOfData) GetLinksOk() (*[]IssuedPromoLink, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *IssuePromoLinkBatchResponseAllOfData) SetLinks(v []IssuedPromoLink)`

SetLinks sets Links field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


