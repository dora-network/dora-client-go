# PromoLinkListResponseAllOfData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | [**[]PromoLinkAdmin**](PromoLinkAdmin.md) |  | 
**NextCursor** | Pointer to **string** | Opaque unpadded base64url keyset cursor. | [optional] 

## Methods

### NewPromoLinkListResponseAllOfData

`func NewPromoLinkListResponseAllOfData(links []PromoLinkAdmin, ) *PromoLinkListResponseAllOfData`

NewPromoLinkListResponseAllOfData instantiates a new PromoLinkListResponseAllOfData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromoLinkListResponseAllOfDataWithDefaults

`func NewPromoLinkListResponseAllOfDataWithDefaults() *PromoLinkListResponseAllOfData`

NewPromoLinkListResponseAllOfDataWithDefaults instantiates a new PromoLinkListResponseAllOfData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLinks

`func (o *PromoLinkListResponseAllOfData) GetLinks() []PromoLinkAdmin`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *PromoLinkListResponseAllOfData) GetLinksOk() (*[]PromoLinkAdmin, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *PromoLinkListResponseAllOfData) SetLinks(v []PromoLinkAdmin)`

SetLinks sets Links field to given value.


### GetNextCursor

`func (o *PromoLinkListResponseAllOfData) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *PromoLinkListResponseAllOfData) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *PromoLinkListResponseAllOfData) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.

### HasNextCursor

`func (o *PromoLinkListResponseAllOfData) HasNextCursor() bool`

HasNextCursor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


