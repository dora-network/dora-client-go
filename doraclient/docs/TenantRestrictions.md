# TenantRestrictions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | **string** | Tenant ID | 
**DepositLimit** | **float64** | Maximum allowed deposit for the tenant. | 
**TradeLimit** | **float64** | Maximum allowed trade amount for the tenant. | 
**UpdatedAt** | **time.Time** | Last update timestamp for the restrictions. | 

## Methods

### NewTenantRestrictions

`func NewTenantRestrictions(tenantId string, depositLimit float64, tradeLimit float64, updatedAt time.Time, ) *TenantRestrictions`

NewTenantRestrictions instantiates a new TenantRestrictions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTenantRestrictionsWithDefaults

`func NewTenantRestrictionsWithDefaults() *TenantRestrictions`

NewTenantRestrictionsWithDefaults instantiates a new TenantRestrictions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *TenantRestrictions) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *TenantRestrictions) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *TenantRestrictions) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetDepositLimit

`func (o *TenantRestrictions) GetDepositLimit() float64`

GetDepositLimit returns the DepositLimit field if non-nil, zero value otherwise.

### GetDepositLimitOk

`func (o *TenantRestrictions) GetDepositLimitOk() (*float64, bool)`

GetDepositLimitOk returns a tuple with the DepositLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositLimit

`func (o *TenantRestrictions) SetDepositLimit(v float64)`

SetDepositLimit sets DepositLimit field to given value.


### GetTradeLimit

`func (o *TenantRestrictions) GetTradeLimit() float64`

GetTradeLimit returns the TradeLimit field if non-nil, zero value otherwise.

### GetTradeLimitOk

`func (o *TenantRestrictions) GetTradeLimitOk() (*float64, bool)`

GetTradeLimitOk returns a tuple with the TradeLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradeLimit

`func (o *TenantRestrictions) SetTradeLimit(v float64)`

SetTradeLimit sets TradeLimit field to given value.


### GetUpdatedAt

`func (o *TenantRestrictions) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TenantRestrictions) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TenantRestrictions) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


