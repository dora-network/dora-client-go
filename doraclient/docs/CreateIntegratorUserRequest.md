# CreateIntegratorUserRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | Pointer to **string** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**CountryOfDomicile** | Pointer to [**CountryCode**](CountryCode.md) |  | [optional] 
**NativeAssetId** | Pointer to **string** |  | [optional] 
**PhotoUrl** | Pointer to **string** |  | [optional] 
**Provider** | Pointer to **string** |  | [optional] 
**ProviderId** | Pointer to **string** |  | [optional] 
**Timezone** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateIntegratorUserRequest

`func NewCreateIntegratorUserRequest() *CreateIntegratorUserRequest`

NewCreateIntegratorUserRequest instantiates a new CreateIntegratorUserRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateIntegratorUserRequestWithDefaults

`func NewCreateIntegratorUserRequestWithDefaults() *CreateIntegratorUserRequest`

NewCreateIntegratorUserRequestWithDefaults instantiates a new CreateIntegratorUserRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *CreateIntegratorUserRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateIntegratorUserRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateIntegratorUserRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CreateIntegratorUserRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetFirstName

`func (o *CreateIntegratorUserRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *CreateIntegratorUserRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *CreateIntegratorUserRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *CreateIntegratorUserRequest) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *CreateIntegratorUserRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *CreateIntegratorUserRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *CreateIntegratorUserRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *CreateIntegratorUserRequest) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetCountryOfDomicile

`func (o *CreateIntegratorUserRequest) GetCountryOfDomicile() CountryCode`

GetCountryOfDomicile returns the CountryOfDomicile field if non-nil, zero value otherwise.

### GetCountryOfDomicileOk

`func (o *CreateIntegratorUserRequest) GetCountryOfDomicileOk() (*CountryCode, bool)`

GetCountryOfDomicileOk returns a tuple with the CountryOfDomicile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfDomicile

`func (o *CreateIntegratorUserRequest) SetCountryOfDomicile(v CountryCode)`

SetCountryOfDomicile sets CountryOfDomicile field to given value.

### HasCountryOfDomicile

`func (o *CreateIntegratorUserRequest) HasCountryOfDomicile() bool`

HasCountryOfDomicile returns a boolean if a field has been set.

### GetNativeAssetId

`func (o *CreateIntegratorUserRequest) GetNativeAssetId() string`

GetNativeAssetId returns the NativeAssetId field if non-nil, zero value otherwise.

### GetNativeAssetIdOk

`func (o *CreateIntegratorUserRequest) GetNativeAssetIdOk() (*string, bool)`

GetNativeAssetIdOk returns a tuple with the NativeAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNativeAssetId

`func (o *CreateIntegratorUserRequest) SetNativeAssetId(v string)`

SetNativeAssetId sets NativeAssetId field to given value.

### HasNativeAssetId

`func (o *CreateIntegratorUserRequest) HasNativeAssetId() bool`

HasNativeAssetId returns a boolean if a field has been set.

### GetPhotoUrl

`func (o *CreateIntegratorUserRequest) GetPhotoUrl() string`

GetPhotoUrl returns the PhotoUrl field if non-nil, zero value otherwise.

### GetPhotoUrlOk

`func (o *CreateIntegratorUserRequest) GetPhotoUrlOk() (*string, bool)`

GetPhotoUrlOk returns a tuple with the PhotoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhotoUrl

`func (o *CreateIntegratorUserRequest) SetPhotoUrl(v string)`

SetPhotoUrl sets PhotoUrl field to given value.

### HasPhotoUrl

`func (o *CreateIntegratorUserRequest) HasPhotoUrl() bool`

HasPhotoUrl returns a boolean if a field has been set.

### GetProvider

`func (o *CreateIntegratorUserRequest) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateIntegratorUserRequest) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateIntegratorUserRequest) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *CreateIntegratorUserRequest) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetProviderId

`func (o *CreateIntegratorUserRequest) GetProviderId() string`

GetProviderId returns the ProviderId field if non-nil, zero value otherwise.

### GetProviderIdOk

`func (o *CreateIntegratorUserRequest) GetProviderIdOk() (*string, bool)`

GetProviderIdOk returns a tuple with the ProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderId

`func (o *CreateIntegratorUserRequest) SetProviderId(v string)`

SetProviderId sets ProviderId field to given value.

### HasProviderId

`func (o *CreateIntegratorUserRequest) HasProviderId() bool`

HasProviderId returns a boolean if a field has been set.

### GetTimezone

`func (o *CreateIntegratorUserRequest) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *CreateIntegratorUserRequest) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *CreateIntegratorUserRequest) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *CreateIntegratorUserRequest) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


