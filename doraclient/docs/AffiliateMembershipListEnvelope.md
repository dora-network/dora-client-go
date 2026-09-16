# AffiliateMembershipListEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]AffiliateMembership**](AffiliateMembership.md) |  | 
**Metadata** | [**Metadata**](Metadata.md) |  | 

## Methods

### NewAffiliateMembershipListEnvelope

`func NewAffiliateMembershipListEnvelope(data []AffiliateMembership, metadata Metadata, ) *AffiliateMembershipListEnvelope`

NewAffiliateMembershipListEnvelope instantiates a new AffiliateMembershipListEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAffiliateMembershipListEnvelopeWithDefaults

`func NewAffiliateMembershipListEnvelopeWithDefaults() *AffiliateMembershipListEnvelope`

NewAffiliateMembershipListEnvelopeWithDefaults instantiates a new AffiliateMembershipListEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AffiliateMembershipListEnvelope) GetData() []AffiliateMembership`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AffiliateMembershipListEnvelope) GetDataOk() (*[]AffiliateMembership, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AffiliateMembershipListEnvelope) SetData(v []AffiliateMembership)`

SetData sets Data field to given value.


### GetMetadata

`func (o *AffiliateMembershipListEnvelope) GetMetadata() Metadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AffiliateMembershipListEnvelope) GetMetadataOk() (*Metadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AffiliateMembershipListEnvelope) SetMetadata(v Metadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


