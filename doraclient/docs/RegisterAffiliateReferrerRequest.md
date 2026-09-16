# RegisterAffiliateReferrerRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | Existing, nonzero DORA user ID in the program owning tenant. | 
**ReferralCode** | Pointer to **NullableString** | Optional custom code: 3 to 64 letters, digits, hyphens or underscores after trimming, starting with a letter or digit. Stored uppercase and unique across all programs and tenants. Omitted, null or empty generates a random code. | [optional] 

## Methods

### NewRegisterAffiliateReferrerRequest

`func NewRegisterAffiliateReferrerRequest(userId string, ) *RegisterAffiliateReferrerRequest`

NewRegisterAffiliateReferrerRequest instantiates a new RegisterAffiliateReferrerRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegisterAffiliateReferrerRequestWithDefaults

`func NewRegisterAffiliateReferrerRequestWithDefaults() *RegisterAffiliateReferrerRequest`

NewRegisterAffiliateReferrerRequestWithDefaults instantiates a new RegisterAffiliateReferrerRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *RegisterAffiliateReferrerRequest) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *RegisterAffiliateReferrerRequest) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *RegisterAffiliateReferrerRequest) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetReferralCode

`func (o *RegisterAffiliateReferrerRequest) GetReferralCode() string`

GetReferralCode returns the ReferralCode field if non-nil, zero value otherwise.

### GetReferralCodeOk

`func (o *RegisterAffiliateReferrerRequest) GetReferralCodeOk() (*string, bool)`

GetReferralCodeOk returns a tuple with the ReferralCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferralCode

`func (o *RegisterAffiliateReferrerRequest) SetReferralCode(v string)`

SetReferralCode sets ReferralCode field to given value.

### HasReferralCode

`func (o *RegisterAffiliateReferrerRequest) HasReferralCode() bool`

HasReferralCode returns a boolean if a field has been set.

### SetReferralCodeNil

`func (o *RegisterAffiliateReferrerRequest) SetReferralCodeNil(b bool)`

 SetReferralCodeNil sets the value for ReferralCode to be an explicit nil

### UnsetReferralCode
`func (o *RegisterAffiliateReferrerRequest) UnsetReferralCode()`

UnsetReferralCode ensures that no value is present for ReferralCode, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


