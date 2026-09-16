# AffiliateMembership

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**ProgramId** | **string** |  | 
**TenantId** | **string** | Owning tenant for administration. This does not define a referral destination. | 
**UserId** | **string** |  | 
**ReferralCode** | **string** | Reusable referral code, stored uppercase. Letters, digits, hyphens and underscores are accepted; the first character must be a letter or digit. Matching is case-insensitive. Separate from QR claim tokens. | 
**CreatedAt** | **time.Time** |  | 
**ProgramName** | **string** |  | 
**IsActive** | **bool** |  | 

## Methods

### NewAffiliateMembership

`func NewAffiliateMembership(id string, programId string, tenantId string, userId string, referralCode string, createdAt time.Time, programName string, isActive bool, ) *AffiliateMembership`

NewAffiliateMembership instantiates a new AffiliateMembership object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAffiliateMembershipWithDefaults

`func NewAffiliateMembershipWithDefaults() *AffiliateMembership`

NewAffiliateMembershipWithDefaults instantiates a new AffiliateMembership object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AffiliateMembership) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AffiliateMembership) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AffiliateMembership) SetId(v string)`

SetId sets Id field to given value.


### GetProgramId

`func (o *AffiliateMembership) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *AffiliateMembership) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *AffiliateMembership) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetTenantId

`func (o *AffiliateMembership) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *AffiliateMembership) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *AffiliateMembership) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetUserId

`func (o *AffiliateMembership) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AffiliateMembership) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AffiliateMembership) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetReferralCode

`func (o *AffiliateMembership) GetReferralCode() string`

GetReferralCode returns the ReferralCode field if non-nil, zero value otherwise.

### GetReferralCodeOk

`func (o *AffiliateMembership) GetReferralCodeOk() (*string, bool)`

GetReferralCodeOk returns a tuple with the ReferralCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferralCode

`func (o *AffiliateMembership) SetReferralCode(v string)`

SetReferralCode sets ReferralCode field to given value.


### GetCreatedAt

`func (o *AffiliateMembership) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AffiliateMembership) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AffiliateMembership) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetProgramName

`func (o *AffiliateMembership) GetProgramName() string`

GetProgramName returns the ProgramName field if non-nil, zero value otherwise.

### GetProgramNameOk

`func (o *AffiliateMembership) GetProgramNameOk() (*string, bool)`

GetProgramNameOk returns a tuple with the ProgramName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramName

`func (o *AffiliateMembership) SetProgramName(v string)`

SetProgramName sets ProgramName field to given value.


### GetIsActive

`func (o *AffiliateMembership) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *AffiliateMembership) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *AffiliateMembership) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


