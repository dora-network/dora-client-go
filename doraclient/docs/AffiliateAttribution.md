# AffiliateAttribution

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReferredUserId** | **string** |  | 
**ProgramId** | **string** |  | 
**ReferrerId** | **string** |  | 
**ReferrerUserId** | **string** |  | 
**TenantId** | **string** |  | 
**SignupSource** | **string** | Signup hostname when assigned at signup; empty for an assignment made later. | 
**CreatedAt** | **time.Time** | Immutable assignment time; activity begins counting from this timestamp. | 
**ReferralCode** | **string** |  | 

## Methods

### NewAffiliateAttribution

`func NewAffiliateAttribution(referredUserId string, programId string, referrerId string, referrerUserId string, tenantId string, signupSource string, createdAt time.Time, referralCode string, ) *AffiliateAttribution`

NewAffiliateAttribution instantiates a new AffiliateAttribution object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAffiliateAttributionWithDefaults

`func NewAffiliateAttributionWithDefaults() *AffiliateAttribution`

NewAffiliateAttributionWithDefaults instantiates a new AffiliateAttribution object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReferredUserId

`func (o *AffiliateAttribution) GetReferredUserId() string`

GetReferredUserId returns the ReferredUserId field if non-nil, zero value otherwise.

### GetReferredUserIdOk

`func (o *AffiliateAttribution) GetReferredUserIdOk() (*string, bool)`

GetReferredUserIdOk returns a tuple with the ReferredUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferredUserId

`func (o *AffiliateAttribution) SetReferredUserId(v string)`

SetReferredUserId sets ReferredUserId field to given value.


### GetProgramId

`func (o *AffiliateAttribution) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *AffiliateAttribution) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *AffiliateAttribution) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetReferrerId

`func (o *AffiliateAttribution) GetReferrerId() string`

GetReferrerId returns the ReferrerId field if non-nil, zero value otherwise.

### GetReferrerIdOk

`func (o *AffiliateAttribution) GetReferrerIdOk() (*string, bool)`

GetReferrerIdOk returns a tuple with the ReferrerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerId

`func (o *AffiliateAttribution) SetReferrerId(v string)`

SetReferrerId sets ReferrerId field to given value.


### GetReferrerUserId

`func (o *AffiliateAttribution) GetReferrerUserId() string`

GetReferrerUserId returns the ReferrerUserId field if non-nil, zero value otherwise.

### GetReferrerUserIdOk

`func (o *AffiliateAttribution) GetReferrerUserIdOk() (*string, bool)`

GetReferrerUserIdOk returns a tuple with the ReferrerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerUserId

`func (o *AffiliateAttribution) SetReferrerUserId(v string)`

SetReferrerUserId sets ReferrerUserId field to given value.


### GetTenantId

`func (o *AffiliateAttribution) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *AffiliateAttribution) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *AffiliateAttribution) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetSignupSource

`func (o *AffiliateAttribution) GetSignupSource() string`

GetSignupSource returns the SignupSource field if non-nil, zero value otherwise.

### GetSignupSourceOk

`func (o *AffiliateAttribution) GetSignupSourceOk() (*string, bool)`

GetSignupSourceOk returns a tuple with the SignupSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignupSource

`func (o *AffiliateAttribution) SetSignupSource(v string)`

SetSignupSource sets SignupSource field to given value.


### GetCreatedAt

`func (o *AffiliateAttribution) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AffiliateAttribution) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AffiliateAttribution) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetReferralCode

`func (o *AffiliateAttribution) GetReferralCode() string`

GetReferralCode returns the ReferralCode field if non-nil, zero value otherwise.

### GetReferralCodeOk

`func (o *AffiliateAttribution) GetReferralCodeOk() (*string, bool)`

GetReferralCodeOk returns a tuple with the ReferralCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferralCode

`func (o *AffiliateAttribution) SetReferralCode(v string)`

SetReferralCode sets ReferralCode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


