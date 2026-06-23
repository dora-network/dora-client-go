# UpdateUserConfigRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PhotoUrl** | Pointer to [**UpdateFieldString**](UpdateFieldString.md) | Optional: URL of the user&#39;s profile photo, optional. | [optional] 
**Timezone** | [**UpdateFieldString**](UpdateFieldString.md) | User&#39;s timezone, e.g., &#39;America/New_York&#39;, or an offset. | 
**ShowTutorialCards** | Pointer to [**UpdateFieldBoolean**](UpdateFieldBoolean.md) | Optional: Whether to show the tutorial. | [optional] 
**NotificationsEnabled** | Pointer to [**UpdateFieldBoolean**](UpdateFieldBoolean.md) | Optional: Whether to show the notifications. | [optional] 
**AllowEmailNotifications** | Pointer to [**UpdateFieldBoolean**](UpdateFieldBoolean.md) | Optional: Whether to allow email notifications. | [optional] 
**AllowLiquidationsNotifications** | Pointer to [**UpdateFieldBoolean**](UpdateFieldBoolean.md) | Optional: Whether to allow liquidations notifications. | [optional] 
**AllowDepositWithdrawalNotifications** | Pointer to [**UpdateFieldBoolean**](UpdateFieldBoolean.md) | Optional: Whether to allow deposit/withdrawal notifications. | [optional] 
**AllowOrdersNotifications** | Pointer to [**UpdateFieldBoolean**](UpdateFieldBoolean.md) | Optional: Whether to allow orders notifications. | [optional] 
**AllowCopyTrading** | Pointer to [**UpdateFieldBoolean**](UpdateFieldBoolean.md) | Optional: Whether to allow copy trading. | [optional] 

## Methods

### NewUpdateUserConfigRequest

`func NewUpdateUserConfigRequest(timezone UpdateFieldString, ) *UpdateUserConfigRequest`

NewUpdateUserConfigRequest instantiates a new UpdateUserConfigRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateUserConfigRequestWithDefaults

`func NewUpdateUserConfigRequestWithDefaults() *UpdateUserConfigRequest`

NewUpdateUserConfigRequestWithDefaults instantiates a new UpdateUserConfigRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhotoUrl

`func (o *UpdateUserConfigRequest) GetPhotoUrl() UpdateFieldString`

GetPhotoUrl returns the PhotoUrl field if non-nil, zero value otherwise.

### GetPhotoUrlOk

`func (o *UpdateUserConfigRequest) GetPhotoUrlOk() (*UpdateFieldString, bool)`

GetPhotoUrlOk returns a tuple with the PhotoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhotoUrl

`func (o *UpdateUserConfigRequest) SetPhotoUrl(v UpdateFieldString)`

SetPhotoUrl sets PhotoUrl field to given value.

### HasPhotoUrl

`func (o *UpdateUserConfigRequest) HasPhotoUrl() bool`

HasPhotoUrl returns a boolean if a field has been set.

### GetTimezone

`func (o *UpdateUserConfigRequest) GetTimezone() UpdateFieldString`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *UpdateUserConfigRequest) GetTimezoneOk() (*UpdateFieldString, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *UpdateUserConfigRequest) SetTimezone(v UpdateFieldString)`

SetTimezone sets Timezone field to given value.


### GetShowTutorialCards

`func (o *UpdateUserConfigRequest) GetShowTutorialCards() UpdateFieldBoolean`

GetShowTutorialCards returns the ShowTutorialCards field if non-nil, zero value otherwise.

### GetShowTutorialCardsOk

`func (o *UpdateUserConfigRequest) GetShowTutorialCardsOk() (*UpdateFieldBoolean, bool)`

GetShowTutorialCardsOk returns a tuple with the ShowTutorialCards field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowTutorialCards

`func (o *UpdateUserConfigRequest) SetShowTutorialCards(v UpdateFieldBoolean)`

SetShowTutorialCards sets ShowTutorialCards field to given value.

### HasShowTutorialCards

`func (o *UpdateUserConfigRequest) HasShowTutorialCards() bool`

HasShowTutorialCards returns a boolean if a field has been set.

### GetNotificationsEnabled

`func (o *UpdateUserConfigRequest) GetNotificationsEnabled() UpdateFieldBoolean`

GetNotificationsEnabled returns the NotificationsEnabled field if non-nil, zero value otherwise.

### GetNotificationsEnabledOk

`func (o *UpdateUserConfigRequest) GetNotificationsEnabledOk() (*UpdateFieldBoolean, bool)`

GetNotificationsEnabledOk returns a tuple with the NotificationsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationsEnabled

`func (o *UpdateUserConfigRequest) SetNotificationsEnabled(v UpdateFieldBoolean)`

SetNotificationsEnabled sets NotificationsEnabled field to given value.

### HasNotificationsEnabled

`func (o *UpdateUserConfigRequest) HasNotificationsEnabled() bool`

HasNotificationsEnabled returns a boolean if a field has been set.

### GetAllowEmailNotifications

`func (o *UpdateUserConfigRequest) GetAllowEmailNotifications() UpdateFieldBoolean`

GetAllowEmailNotifications returns the AllowEmailNotifications field if non-nil, zero value otherwise.

### GetAllowEmailNotificationsOk

`func (o *UpdateUserConfigRequest) GetAllowEmailNotificationsOk() (*UpdateFieldBoolean, bool)`

GetAllowEmailNotificationsOk returns a tuple with the AllowEmailNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowEmailNotifications

`func (o *UpdateUserConfigRequest) SetAllowEmailNotifications(v UpdateFieldBoolean)`

SetAllowEmailNotifications sets AllowEmailNotifications field to given value.

### HasAllowEmailNotifications

`func (o *UpdateUserConfigRequest) HasAllowEmailNotifications() bool`

HasAllowEmailNotifications returns a boolean if a field has been set.

### GetAllowLiquidationsNotifications

`func (o *UpdateUserConfigRequest) GetAllowLiquidationsNotifications() UpdateFieldBoolean`

GetAllowLiquidationsNotifications returns the AllowLiquidationsNotifications field if non-nil, zero value otherwise.

### GetAllowLiquidationsNotificationsOk

`func (o *UpdateUserConfigRequest) GetAllowLiquidationsNotificationsOk() (*UpdateFieldBoolean, bool)`

GetAllowLiquidationsNotificationsOk returns a tuple with the AllowLiquidationsNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLiquidationsNotifications

`func (o *UpdateUserConfigRequest) SetAllowLiquidationsNotifications(v UpdateFieldBoolean)`

SetAllowLiquidationsNotifications sets AllowLiquidationsNotifications field to given value.

### HasAllowLiquidationsNotifications

`func (o *UpdateUserConfigRequest) HasAllowLiquidationsNotifications() bool`

HasAllowLiquidationsNotifications returns a boolean if a field has been set.

### GetAllowDepositWithdrawalNotifications

`func (o *UpdateUserConfigRequest) GetAllowDepositWithdrawalNotifications() UpdateFieldBoolean`

GetAllowDepositWithdrawalNotifications returns the AllowDepositWithdrawalNotifications field if non-nil, zero value otherwise.

### GetAllowDepositWithdrawalNotificationsOk

`func (o *UpdateUserConfigRequest) GetAllowDepositWithdrawalNotificationsOk() (*UpdateFieldBoolean, bool)`

GetAllowDepositWithdrawalNotificationsOk returns a tuple with the AllowDepositWithdrawalNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowDepositWithdrawalNotifications

`func (o *UpdateUserConfigRequest) SetAllowDepositWithdrawalNotifications(v UpdateFieldBoolean)`

SetAllowDepositWithdrawalNotifications sets AllowDepositWithdrawalNotifications field to given value.

### HasAllowDepositWithdrawalNotifications

`func (o *UpdateUserConfigRequest) HasAllowDepositWithdrawalNotifications() bool`

HasAllowDepositWithdrawalNotifications returns a boolean if a field has been set.

### GetAllowOrdersNotifications

`func (o *UpdateUserConfigRequest) GetAllowOrdersNotifications() UpdateFieldBoolean`

GetAllowOrdersNotifications returns the AllowOrdersNotifications field if non-nil, zero value otherwise.

### GetAllowOrdersNotificationsOk

`func (o *UpdateUserConfigRequest) GetAllowOrdersNotificationsOk() (*UpdateFieldBoolean, bool)`

GetAllowOrdersNotificationsOk returns a tuple with the AllowOrdersNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowOrdersNotifications

`func (o *UpdateUserConfigRequest) SetAllowOrdersNotifications(v UpdateFieldBoolean)`

SetAllowOrdersNotifications sets AllowOrdersNotifications field to given value.

### HasAllowOrdersNotifications

`func (o *UpdateUserConfigRequest) HasAllowOrdersNotifications() bool`

HasAllowOrdersNotifications returns a boolean if a field has been set.

### GetAllowCopyTrading

`func (o *UpdateUserConfigRequest) GetAllowCopyTrading() UpdateFieldBoolean`

GetAllowCopyTrading returns the AllowCopyTrading field if non-nil, zero value otherwise.

### GetAllowCopyTradingOk

`func (o *UpdateUserConfigRequest) GetAllowCopyTradingOk() (*UpdateFieldBoolean, bool)`

GetAllowCopyTradingOk returns a tuple with the AllowCopyTrading field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowCopyTrading

`func (o *UpdateUserConfigRequest) SetAllowCopyTrading(v UpdateFieldBoolean)`

SetAllowCopyTrading sets AllowCopyTrading field to given value.

### HasAllowCopyTrading

`func (o *UpdateUserConfigRequest) HasAllowCopyTrading() bool`

HasAllowCopyTrading returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


