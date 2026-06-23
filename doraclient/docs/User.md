# User

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**ClosedAt** | Pointer to **time.Time** |  | [optional] 
**DisabledAt** | Pointer to **time.Time** |  | [optional] 
**Email** | **string** |  | 
**FirstName** | **string** |  | 
**LastName** | **string** |  | 
**CountryOfDomicile** | [**CountryCode**](CountryCode.md) |  | 
**NativeAssetId** | **string** |  | 
**PhotoUrl** | Pointer to **string** |  | [optional] 
**Provider** | Pointer to **string** |  | [optional] 
**ProviderId** | Pointer to **string** |  | [optional] 
**Roles** | [**[]UserRole**](UserRole.md) |  | 
**Timezone** | Pointer to **string** | User&#39;s timezone, e.g., &#39;America/New_York&#39;, or an offset. | [optional] 
**TimezoneOffset** | Pointer to **int32** | timezone offset in seconds | [optional] 
**VerifiedAt** | Pointer to **time.Time** |  | [optional] 
**ShowTutorialCards** | **bool** |  | 
**NotificationsEnabled** | **bool** |  | 
**TenantId** | **string** |  | 
**AllowEmailNotifications** | **bool** |  | 
**AllowLiquidationsNotifications** | **bool** |  | 
**AllowDepositWithdrawalNotifications** | **bool** |  | 
**AllowOrdersNotifications** | **bool** |  | 
**AllowCopyTrading** | **bool** |  | 

## Methods

### NewUser

`func NewUser(id string, email string, firstName string, lastName string, countryOfDomicile CountryCode, nativeAssetId string, roles []UserRole, showTutorialCards bool, notificationsEnabled bool, tenantId string, allowEmailNotifications bool, allowLiquidationsNotifications bool, allowDepositWithdrawalNotifications bool, allowOrdersNotifications bool, allowCopyTrading bool, ) *User`

NewUser instantiates a new User object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserWithDefaults

`func NewUserWithDefaults() *User`

NewUserWithDefaults instantiates a new User object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *User) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *User) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *User) SetId(v string)`

SetId sets Id field to given value.


### GetClosedAt

`func (o *User) GetClosedAt() time.Time`

GetClosedAt returns the ClosedAt field if non-nil, zero value otherwise.

### GetClosedAtOk

`func (o *User) GetClosedAtOk() (*time.Time, bool)`

GetClosedAtOk returns a tuple with the ClosedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosedAt

`func (o *User) SetClosedAt(v time.Time)`

SetClosedAt sets ClosedAt field to given value.

### HasClosedAt

`func (o *User) HasClosedAt() bool`

HasClosedAt returns a boolean if a field has been set.

### GetDisabledAt

`func (o *User) GetDisabledAt() time.Time`

GetDisabledAt returns the DisabledAt field if non-nil, zero value otherwise.

### GetDisabledAtOk

`func (o *User) GetDisabledAtOk() (*time.Time, bool)`

GetDisabledAtOk returns a tuple with the DisabledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabledAt

`func (o *User) SetDisabledAt(v time.Time)`

SetDisabledAt sets DisabledAt field to given value.

### HasDisabledAt

`func (o *User) HasDisabledAt() bool`

HasDisabledAt returns a boolean if a field has been set.

### GetEmail

`func (o *User) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *User) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *User) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetFirstName

`func (o *User) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *User) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *User) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *User) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *User) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *User) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetCountryOfDomicile

`func (o *User) GetCountryOfDomicile() CountryCode`

GetCountryOfDomicile returns the CountryOfDomicile field if non-nil, zero value otherwise.

### GetCountryOfDomicileOk

`func (o *User) GetCountryOfDomicileOk() (*CountryCode, bool)`

GetCountryOfDomicileOk returns a tuple with the CountryOfDomicile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfDomicile

`func (o *User) SetCountryOfDomicile(v CountryCode)`

SetCountryOfDomicile sets CountryOfDomicile field to given value.


### GetNativeAssetId

`func (o *User) GetNativeAssetId() string`

GetNativeAssetId returns the NativeAssetId field if non-nil, zero value otherwise.

### GetNativeAssetIdOk

`func (o *User) GetNativeAssetIdOk() (*string, bool)`

GetNativeAssetIdOk returns a tuple with the NativeAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNativeAssetId

`func (o *User) SetNativeAssetId(v string)`

SetNativeAssetId sets NativeAssetId field to given value.


### GetPhotoUrl

`func (o *User) GetPhotoUrl() string`

GetPhotoUrl returns the PhotoUrl field if non-nil, zero value otherwise.

### GetPhotoUrlOk

`func (o *User) GetPhotoUrlOk() (*string, bool)`

GetPhotoUrlOk returns a tuple with the PhotoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhotoUrl

`func (o *User) SetPhotoUrl(v string)`

SetPhotoUrl sets PhotoUrl field to given value.

### HasPhotoUrl

`func (o *User) HasPhotoUrl() bool`

HasPhotoUrl returns a boolean if a field has been set.

### GetProvider

`func (o *User) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *User) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *User) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *User) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetProviderId

`func (o *User) GetProviderId() string`

GetProviderId returns the ProviderId field if non-nil, zero value otherwise.

### GetProviderIdOk

`func (o *User) GetProviderIdOk() (*string, bool)`

GetProviderIdOk returns a tuple with the ProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderId

`func (o *User) SetProviderId(v string)`

SetProviderId sets ProviderId field to given value.

### HasProviderId

`func (o *User) HasProviderId() bool`

HasProviderId returns a boolean if a field has been set.

### GetRoles

`func (o *User) GetRoles() []UserRole`

GetRoles returns the Roles field if non-nil, zero value otherwise.

### GetRolesOk

`func (o *User) GetRolesOk() (*[]UserRole, bool)`

GetRolesOk returns a tuple with the Roles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoles

`func (o *User) SetRoles(v []UserRole)`

SetRoles sets Roles field to given value.


### GetTimezone

`func (o *User) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *User) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *User) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *User) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetTimezoneOffset

`func (o *User) GetTimezoneOffset() int32`

GetTimezoneOffset returns the TimezoneOffset field if non-nil, zero value otherwise.

### GetTimezoneOffsetOk

`func (o *User) GetTimezoneOffsetOk() (*int32, bool)`

GetTimezoneOffsetOk returns a tuple with the TimezoneOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezoneOffset

`func (o *User) SetTimezoneOffset(v int32)`

SetTimezoneOffset sets TimezoneOffset field to given value.

### HasTimezoneOffset

`func (o *User) HasTimezoneOffset() bool`

HasTimezoneOffset returns a boolean if a field has been set.

### GetVerifiedAt

`func (o *User) GetVerifiedAt() time.Time`

GetVerifiedAt returns the VerifiedAt field if non-nil, zero value otherwise.

### GetVerifiedAtOk

`func (o *User) GetVerifiedAtOk() (*time.Time, bool)`

GetVerifiedAtOk returns a tuple with the VerifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifiedAt

`func (o *User) SetVerifiedAt(v time.Time)`

SetVerifiedAt sets VerifiedAt field to given value.

### HasVerifiedAt

`func (o *User) HasVerifiedAt() bool`

HasVerifiedAt returns a boolean if a field has been set.

### GetShowTutorialCards

`func (o *User) GetShowTutorialCards() bool`

GetShowTutorialCards returns the ShowTutorialCards field if non-nil, zero value otherwise.

### GetShowTutorialCardsOk

`func (o *User) GetShowTutorialCardsOk() (*bool, bool)`

GetShowTutorialCardsOk returns a tuple with the ShowTutorialCards field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowTutorialCards

`func (o *User) SetShowTutorialCards(v bool)`

SetShowTutorialCards sets ShowTutorialCards field to given value.


### GetNotificationsEnabled

`func (o *User) GetNotificationsEnabled() bool`

GetNotificationsEnabled returns the NotificationsEnabled field if non-nil, zero value otherwise.

### GetNotificationsEnabledOk

`func (o *User) GetNotificationsEnabledOk() (*bool, bool)`

GetNotificationsEnabledOk returns a tuple with the NotificationsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationsEnabled

`func (o *User) SetNotificationsEnabled(v bool)`

SetNotificationsEnabled sets NotificationsEnabled field to given value.


### GetTenantId

`func (o *User) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *User) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *User) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetAllowEmailNotifications

`func (o *User) GetAllowEmailNotifications() bool`

GetAllowEmailNotifications returns the AllowEmailNotifications field if non-nil, zero value otherwise.

### GetAllowEmailNotificationsOk

`func (o *User) GetAllowEmailNotificationsOk() (*bool, bool)`

GetAllowEmailNotificationsOk returns a tuple with the AllowEmailNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowEmailNotifications

`func (o *User) SetAllowEmailNotifications(v bool)`

SetAllowEmailNotifications sets AllowEmailNotifications field to given value.


### GetAllowLiquidationsNotifications

`func (o *User) GetAllowLiquidationsNotifications() bool`

GetAllowLiquidationsNotifications returns the AllowLiquidationsNotifications field if non-nil, zero value otherwise.

### GetAllowLiquidationsNotificationsOk

`func (o *User) GetAllowLiquidationsNotificationsOk() (*bool, bool)`

GetAllowLiquidationsNotificationsOk returns a tuple with the AllowLiquidationsNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLiquidationsNotifications

`func (o *User) SetAllowLiquidationsNotifications(v bool)`

SetAllowLiquidationsNotifications sets AllowLiquidationsNotifications field to given value.


### GetAllowDepositWithdrawalNotifications

`func (o *User) GetAllowDepositWithdrawalNotifications() bool`

GetAllowDepositWithdrawalNotifications returns the AllowDepositWithdrawalNotifications field if non-nil, zero value otherwise.

### GetAllowDepositWithdrawalNotificationsOk

`func (o *User) GetAllowDepositWithdrawalNotificationsOk() (*bool, bool)`

GetAllowDepositWithdrawalNotificationsOk returns a tuple with the AllowDepositWithdrawalNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowDepositWithdrawalNotifications

`func (o *User) SetAllowDepositWithdrawalNotifications(v bool)`

SetAllowDepositWithdrawalNotifications sets AllowDepositWithdrawalNotifications field to given value.


### GetAllowOrdersNotifications

`func (o *User) GetAllowOrdersNotifications() bool`

GetAllowOrdersNotifications returns the AllowOrdersNotifications field if non-nil, zero value otherwise.

### GetAllowOrdersNotificationsOk

`func (o *User) GetAllowOrdersNotificationsOk() (*bool, bool)`

GetAllowOrdersNotificationsOk returns a tuple with the AllowOrdersNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowOrdersNotifications

`func (o *User) SetAllowOrdersNotifications(v bool)`

SetAllowOrdersNotifications sets AllowOrdersNotifications field to given value.


### GetAllowCopyTrading

`func (o *User) GetAllowCopyTrading() bool`

GetAllowCopyTrading returns the AllowCopyTrading field if non-nil, zero value otherwise.

### GetAllowCopyTradingOk

`func (o *User) GetAllowCopyTradingOk() (*bool, bool)`

GetAllowCopyTradingOk returns a tuple with the AllowCopyTrading field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowCopyTrading

`func (o *User) SetAllowCopyTrading(v bool)`

SetAllowCopyTrading sets AllowCopyTrading field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


