# PromoLinkAdmin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**TokenPrefix** | **string** |  | 
**Url** | Pointer to **string** | Only present when reveal&#x3D;true. Private; do not log or cache. | [optional] 
**Status** | [**PromoLinkStatus**](PromoLinkStatus.md) |  | 
**ExpiresAt** | **time.Time** |  | 
**ClaimedAt** | Pointer to **time.Time** |  | [optional] 
**ClaimedEmail** | Pointer to **string** | Masked as the first character, three asterisks, and domain. | [optional] 
**UserId** | Pointer to **string** |  | [optional] 

## Methods

### NewPromoLinkAdmin

`func NewPromoLinkAdmin(id string, tokenPrefix string, status PromoLinkStatus, expiresAt time.Time, ) *PromoLinkAdmin`

NewPromoLinkAdmin instantiates a new PromoLinkAdmin object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromoLinkAdminWithDefaults

`func NewPromoLinkAdminWithDefaults() *PromoLinkAdmin`

NewPromoLinkAdminWithDefaults instantiates a new PromoLinkAdmin object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PromoLinkAdmin) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PromoLinkAdmin) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PromoLinkAdmin) SetId(v string)`

SetId sets Id field to given value.


### GetTokenPrefix

`func (o *PromoLinkAdmin) GetTokenPrefix() string`

GetTokenPrefix returns the TokenPrefix field if non-nil, zero value otherwise.

### GetTokenPrefixOk

`func (o *PromoLinkAdmin) GetTokenPrefixOk() (*string, bool)`

GetTokenPrefixOk returns a tuple with the TokenPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenPrefix

`func (o *PromoLinkAdmin) SetTokenPrefix(v string)`

SetTokenPrefix sets TokenPrefix field to given value.


### GetUrl

`func (o *PromoLinkAdmin) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *PromoLinkAdmin) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *PromoLinkAdmin) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *PromoLinkAdmin) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetStatus

`func (o *PromoLinkAdmin) GetStatus() PromoLinkStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PromoLinkAdmin) GetStatusOk() (*PromoLinkStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PromoLinkAdmin) SetStatus(v PromoLinkStatus)`

SetStatus sets Status field to given value.


### GetExpiresAt

`func (o *PromoLinkAdmin) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *PromoLinkAdmin) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *PromoLinkAdmin) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetClaimedAt

`func (o *PromoLinkAdmin) GetClaimedAt() time.Time`

GetClaimedAt returns the ClaimedAt field if non-nil, zero value otherwise.

### GetClaimedAtOk

`func (o *PromoLinkAdmin) GetClaimedAtOk() (*time.Time, bool)`

GetClaimedAtOk returns a tuple with the ClaimedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimedAt

`func (o *PromoLinkAdmin) SetClaimedAt(v time.Time)`

SetClaimedAt sets ClaimedAt field to given value.

### HasClaimedAt

`func (o *PromoLinkAdmin) HasClaimedAt() bool`

HasClaimedAt returns a boolean if a field has been set.

### GetClaimedEmail

`func (o *PromoLinkAdmin) GetClaimedEmail() string`

GetClaimedEmail returns the ClaimedEmail field if non-nil, zero value otherwise.

### GetClaimedEmailOk

`func (o *PromoLinkAdmin) GetClaimedEmailOk() (*string, bool)`

GetClaimedEmailOk returns a tuple with the ClaimedEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimedEmail

`func (o *PromoLinkAdmin) SetClaimedEmail(v string)`

SetClaimedEmail sets ClaimedEmail field to given value.

### HasClaimedEmail

`func (o *PromoLinkAdmin) HasClaimedEmail() bool`

HasClaimedEmail returns a boolean if a field has been set.

### GetUserId

`func (o *PromoLinkAdmin) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *PromoLinkAdmin) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *PromoLinkAdmin) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *PromoLinkAdmin) HasUserId() bool`

HasUserId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


