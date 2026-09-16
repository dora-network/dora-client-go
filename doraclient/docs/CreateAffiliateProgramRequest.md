# CreateAffiliateProgramRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | **string** | Owning tenant for administration. This does not define a referral destination. | 
**Name** | **string** | No surrounding whitespace or control characters. | 
**Description** | Pointer to **NullableString** | Omitted or null defaults to an empty description. | [optional] [default to ""]
**IsActive** | Pointer to **bool** | Inactive programs retain registrations, but cannot issue or resolve codes. Set true to create an active program. | [optional] [default to false]

## Methods

### NewCreateAffiliateProgramRequest

`func NewCreateAffiliateProgramRequest(tenantId string, name string, ) *CreateAffiliateProgramRequest`

NewCreateAffiliateProgramRequest instantiates a new CreateAffiliateProgramRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAffiliateProgramRequestWithDefaults

`func NewCreateAffiliateProgramRequestWithDefaults() *CreateAffiliateProgramRequest`

NewCreateAffiliateProgramRequestWithDefaults instantiates a new CreateAffiliateProgramRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *CreateAffiliateProgramRequest) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *CreateAffiliateProgramRequest) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *CreateAffiliateProgramRequest) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetName

`func (o *CreateAffiliateProgramRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateAffiliateProgramRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateAffiliateProgramRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CreateAffiliateProgramRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateAffiliateProgramRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateAffiliateProgramRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateAffiliateProgramRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateAffiliateProgramRequest) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateAffiliateProgramRequest) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetIsActive

`func (o *CreateAffiliateProgramRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *CreateAffiliateProgramRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *CreateAffiliateProgramRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *CreateAffiliateProgramRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


