# AffiliateReferrer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**ProgramId** | **string** |  | 
**TenantId** | **string** | Owning tenant for administration. This does not define a referral destination. | 
**UserId** | **string** |  | 
**ReferralCode** | **string** | Current code to share; previously issued codes remain valid. Stored uppercase and unique across all programs and tenants. | 
**CreatedAt** | **time.Time** |  | 
**CustomizedAt** | **NullableTime** | When the owner used their one code change; null until then. | 

## Methods

### NewAffiliateReferrer

`func NewAffiliateReferrer(id string, programId string, tenantId string, userId string, referralCode string, createdAt time.Time, customizedAt NullableTime, ) *AffiliateReferrer`

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


### GetCustomizedAt

`func (o *AffiliateReferrer) GetCustomizedAt() time.Time`

GetCustomizedAt returns the CustomizedAt field if non-nil, zero value otherwise.

### GetCustomizedAtOk

`func (o *AffiliateReferrer) GetCustomizedAtOk() (*time.Time, bool)`

GetCustomizedAtOk returns a tuple with the CustomizedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomizedAt

`func (o *AffiliateReferrer) SetCustomizedAt(v time.Time)`

SetCustomizedAt sets CustomizedAt field to given value.


### SetCustomizedAtNil

`func (o *AffiliateReferrer) SetCustomizedAtNil(b bool)`

 SetCustomizedAtNil sets the value for CustomizedAt to be an explicit nil

### UnsetCustomizedAt
`func (o *AffiliateReferrer) UnsetCustomizedAt()`

UnsetCustomizedAt ensures that no value is present for CustomizedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


