# UserConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**PhotoUrl** | Pointer to **string** |  | [optional] 
**Timezone** | Pointer to **string** | User&#39;s timezone, e.g., &#39;America/New_York&#39;, or an offset. | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**ShowTutorialCards** | **bool** |  | 
**NotificationsEnabled** | **bool** |  | 
**AllowEmailNotifications** | **bool** |  | 
**AllowLiquidationsNotifications** | **bool** |  | 
**AllowDepositWithdrawalNotifications** | **bool** |  | 
**AllowOrdersNotifications** | **bool** |  | 

## Methods

### NewUserConfig

`func NewUserConfig(id string, createdAt time.Time, updatedAt time.Time, showTutorialCards bool, notificationsEnabled bool, allowEmailNotifications bool, allowLiquidationsNotifications bool, allowDepositWithdrawalNotifications bool, allowOrdersNotifications bool, ) *UserConfig`

NewUserConfig instantiates a new UserConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserConfigWithDefaults

`func NewUserConfigWithDefaults() *UserConfig`

NewUserConfigWithDefaults instantiates a new UserConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UserConfig) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserConfig) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserConfig) SetId(v string)`

SetId sets Id field to given value.


### GetPhotoUrl

`func (o *UserConfig) GetPhotoUrl() string`

GetPhotoUrl returns the PhotoUrl field if non-nil, zero value otherwise.

### GetPhotoUrlOk

`func (o *UserConfig) GetPhotoUrlOk() (*string, bool)`

GetPhotoUrlOk returns a tuple with the PhotoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhotoUrl

`func (o *UserConfig) SetPhotoUrl(v string)`

SetPhotoUrl sets PhotoUrl field to given value.

### HasPhotoUrl

`func (o *UserConfig) HasPhotoUrl() bool`

HasPhotoUrl returns a boolean if a field has been set.

### GetTimezone

`func (o *UserConfig) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *UserConfig) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *UserConfig) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *UserConfig) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetCreatedAt

`func (o *UserConfig) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UserConfig) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UserConfig) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *UserConfig) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *UserConfig) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *UserConfig) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetShowTutorialCards

`func (o *UserConfig) GetShowTutorialCards() bool`

GetShowTutorialCards returns the ShowTutorialCards field if non-nil, zero value otherwise.

### GetShowTutorialCardsOk

`func (o *UserConfig) GetShowTutorialCardsOk() (*bool, bool)`

GetShowTutorialCardsOk returns a tuple with the ShowTutorialCards field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowTutorialCards

`func (o *UserConfig) SetShowTutorialCards(v bool)`

SetShowTutorialCards sets ShowTutorialCards field to given value.


### GetNotificationsEnabled

`func (o *UserConfig) GetNotificationsEnabled() bool`

GetNotificationsEnabled returns the NotificationsEnabled field if non-nil, zero value otherwise.

### GetNotificationsEnabledOk

`func (o *UserConfig) GetNotificationsEnabledOk() (*bool, bool)`

GetNotificationsEnabledOk returns a tuple with the NotificationsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationsEnabled

`func (o *UserConfig) SetNotificationsEnabled(v bool)`

SetNotificationsEnabled sets NotificationsEnabled field to given value.


### GetAllowEmailNotifications

`func (o *UserConfig) GetAllowEmailNotifications() bool`

GetAllowEmailNotifications returns the AllowEmailNotifications field if non-nil, zero value otherwise.

### GetAllowEmailNotificationsOk

`func (o *UserConfig) GetAllowEmailNotificationsOk() (*bool, bool)`

GetAllowEmailNotificationsOk returns a tuple with the AllowEmailNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowEmailNotifications

`func (o *UserConfig) SetAllowEmailNotifications(v bool)`

SetAllowEmailNotifications sets AllowEmailNotifications field to given value.


### GetAllowLiquidationsNotifications

`func (o *UserConfig) GetAllowLiquidationsNotifications() bool`

GetAllowLiquidationsNotifications returns the AllowLiquidationsNotifications field if non-nil, zero value otherwise.

### GetAllowLiquidationsNotificationsOk

`func (o *UserConfig) GetAllowLiquidationsNotificationsOk() (*bool, bool)`

GetAllowLiquidationsNotificationsOk returns a tuple with the AllowLiquidationsNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLiquidationsNotifications

`func (o *UserConfig) SetAllowLiquidationsNotifications(v bool)`

SetAllowLiquidationsNotifications sets AllowLiquidationsNotifications field to given value.


### GetAllowDepositWithdrawalNotifications

`func (o *UserConfig) GetAllowDepositWithdrawalNotifications() bool`

GetAllowDepositWithdrawalNotifications returns the AllowDepositWithdrawalNotifications field if non-nil, zero value otherwise.

### GetAllowDepositWithdrawalNotificationsOk

`func (o *UserConfig) GetAllowDepositWithdrawalNotificationsOk() (*bool, bool)`

GetAllowDepositWithdrawalNotificationsOk returns a tuple with the AllowDepositWithdrawalNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowDepositWithdrawalNotifications

`func (o *UserConfig) SetAllowDepositWithdrawalNotifications(v bool)`

SetAllowDepositWithdrawalNotifications sets AllowDepositWithdrawalNotifications field to given value.


### GetAllowOrdersNotifications

`func (o *UserConfig) GetAllowOrdersNotifications() bool`

GetAllowOrdersNotifications returns the AllowOrdersNotifications field if non-nil, zero value otherwise.

### GetAllowOrdersNotificationsOk

`func (o *UserConfig) GetAllowOrdersNotificationsOk() (*bool, bool)`

GetAllowOrdersNotificationsOk returns a tuple with the AllowOrdersNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowOrdersNotifications

`func (o *UserConfig) SetAllowOrdersNotifications(v bool)`

SetAllowOrdersNotifications sets AllowOrdersNotifications field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


