# AffiliateReferrer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**ProgramId** | **string** |  | 
**TenantId** | **string** | Owning tenant for administration. This does not define a referral destination. | 
**UserId** | **string** |  | 
**ReferralCode** | **string** | Reusable referral code, stored uppercase. Letters, digits, hyphens and underscores are accepted; the first character must be a letter or digit. Matching is case-insensitive. Separate from QR claim tokens. | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewAffiliateReferrer

`func NewAffiliateReferrer(id string, programId string, tenantId string, userId string, referralCode string, createdAt time.Time, ) *AffiliateReferrer`

NewAffiliateReferrer instantiates a new AffiliateReferrer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAffiliateReferrerWithDefaults

`func NewAffiliateReferrerWithDefaults() *AffiliateReferrer`

NewAffiliateReferrerWithDefaults instantiates a new AffiliateReferrer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AffiliateReferrer) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AffiliateReferrer) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AffiliateReferrer) SetId(v string)`

SetId sets Id field to given value.


### GetProgramId

`func (o *AffiliateReferrer) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *AffiliateReferrer) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *AffiliateReferrer) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetTenantId

`func (o *AffiliateReferrer) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *AffiliateReferrer) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *AffiliateReferrer) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetUserId

`func (o *AffiliateReferrer) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AffiliateReferrer) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AffiliateReferrer) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetReferralCode

`func (o *AffiliateReferrer) GetReferralCode() string`

GetReferralCode returns the ReferralCode field if non-nil, zero value otherwise.

### GetReferralCodeOk

`func (o *AffiliateReferrer) GetReferralCodeOk() (*string, bool)`

GetReferralCodeOk returns a tuple with the ReferralCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferralCode

`func (o *AffiliateReferrer) SetReferralCode(v string)`

SetReferralCode sets ReferralCode field to given value.


### GetCreatedAt

`func (o *AffiliateReferrer) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AffiliateReferrer) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AffiliateReferrer) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


