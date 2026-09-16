# IssuedPromoLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**TokenPrefix** | **string** |  | 
**Url** | **string** | Private claim URL. Do not log or cache. | 
**QrUrl** | **string** |  | 
**ExpiresAt** | **time.Time** |  | 

## Methods

### NewIssuedPromoLink

`func NewIssuedPromoLink(id string, tokenPrefix string, url string, qrUrl string, expiresAt time.Time, ) *IssuedPromoLink`

NewIssuedPromoLink instantiates a new IssuedPromoLink object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIssuedPromoLinkWithDefaults

`func NewIssuedPromoLinkWithDefaults() *IssuedPromoLink`

NewIssuedPromoLinkWithDefaults instantiates a new IssuedPromoLink object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IssuedPromoLink) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IssuedPromoLink) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IssuedPromoLink) SetId(v string)`

SetId sets Id field to given value.


### GetTokenPrefix

`func (o *IssuedPromoLink) GetTokenPrefix() string`

GetTokenPrefix returns the TokenPrefix field if non-nil, zero value otherwise.

### GetTokenPrefixOk

`func (o *IssuedPromoLink) GetTokenPrefixOk() (*string, bool)`

GetTokenPrefixOk returns a tuple with the TokenPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenPrefix

`func (o *IssuedPromoLink) SetTokenPrefix(v string)`

SetTokenPrefix sets TokenPrefix field to given value.


### GetUrl

`func (o *IssuedPromoLink) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *IssuedPromoLink) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *IssuedPromoLink) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetQrUrl

`func (o *IssuedPromoLink) GetQrUrl() string`

GetQrUrl returns the QrUrl field if non-nil, zero value otherwise.

### GetQrUrlOk

`func (o *IssuedPromoLink) GetQrUrlOk() (*string, bool)`

GetQrUrlOk returns a tuple with the QrUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrUrl

`func (o *IssuedPromoLink) SetQrUrl(v string)`

SetQrUrl sets QrUrl field to given value.


### GetExpiresAt

`func (o *IssuedPromoLink) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *IssuedPromoLink) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *IssuedPromoLink) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


