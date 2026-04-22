# RealizedPnlSettlements

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Settlements** | Pointer to [**[]RealizedPnlSettlement**](RealizedPnlSettlement.md) | A list of realized PnL settlements matching the query parameters of the request | [optional] 
**UserTotals** | Pointer to **map[string]float64** | A map of user IDs to their total realized PnL in USD across all settlements included in the response | [optional] 
**TenantTotals** | Pointer to **map[string]float64** | A map of tenant IDs to their total realized PnL in USD across all settlements included in the response | [optional] 
**UserTotalsUnsettled** | Pointer to **map[string]float64** | A map of user IDs to their total realized PnL in USD across unsettled settlements (where settled_at is null) included in the response | [optional] 
**TenantTotalsUnsettled** | Pointer to **map[string]float64** | A map of tenant IDs to their total realized PnL in USD across unsettled settlements (where settled_at is null) included in the response | [optional] 

## Methods

### NewRealizedPnlSettlements

`func NewRealizedPnlSettlements() *RealizedPnlSettlements`

NewRealizedPnlSettlements instantiates a new RealizedPnlSettlements object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRealizedPnlSettlementsWithDefaults

`func NewRealizedPnlSettlementsWithDefaults() *RealizedPnlSettlements`

NewRealizedPnlSettlementsWithDefaults instantiates a new RealizedPnlSettlements object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSettlements

`func (o *RealizedPnlSettlements) GetSettlements() []RealizedPnlSettlement`

GetSettlements returns the Settlements field if non-nil, zero value otherwise.

### GetSettlementsOk

`func (o *RealizedPnlSettlements) GetSettlementsOk() (*[]RealizedPnlSettlement, bool)`

GetSettlementsOk returns a tuple with the Settlements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlements

`func (o *RealizedPnlSettlements) SetSettlements(v []RealizedPnlSettlement)`

SetSettlements sets Settlements field to given value.

### HasSettlements

`func (o *RealizedPnlSettlements) HasSettlements() bool`

HasSettlements returns a boolean if a field has been set.

### GetUserTotals

`func (o *RealizedPnlSettlements) GetUserTotals() map[string]float64`

GetUserTotals returns the UserTotals field if non-nil, zero value otherwise.

### GetUserTotalsOk

`func (o *RealizedPnlSettlements) GetUserTotalsOk() (*map[string]float64, bool)`

GetUserTotalsOk returns a tuple with the UserTotals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserTotals

`func (o *RealizedPnlSettlements) SetUserTotals(v map[string]float64)`

SetUserTotals sets UserTotals field to given value.

### HasUserTotals

`func (o *RealizedPnlSettlements) HasUserTotals() bool`

HasUserTotals returns a boolean if a field has been set.

### GetTenantTotals

`func (o *RealizedPnlSettlements) GetTenantTotals() map[string]float64`

GetTenantTotals returns the TenantTotals field if non-nil, zero value otherwise.

### GetTenantTotalsOk

`func (o *RealizedPnlSettlements) GetTenantTotalsOk() (*map[string]float64, bool)`

GetTenantTotalsOk returns a tuple with the TenantTotals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantTotals

`func (o *RealizedPnlSettlements) SetTenantTotals(v map[string]float64)`

SetTenantTotals sets TenantTotals field to given value.

### HasTenantTotals

`func (o *RealizedPnlSettlements) HasTenantTotals() bool`

HasTenantTotals returns a boolean if a field has been set.

### GetUserTotalsUnsettled

`func (o *RealizedPnlSettlements) GetUserTotalsUnsettled() map[string]float64`

GetUserTotalsUnsettled returns the UserTotalsUnsettled field if non-nil, zero value otherwise.

### GetUserTotalsUnsettledOk

`func (o *RealizedPnlSettlements) GetUserTotalsUnsettledOk() (*map[string]float64, bool)`

GetUserTotalsUnsettledOk returns a tuple with the UserTotalsUnsettled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserTotalsUnsettled

`func (o *RealizedPnlSettlements) SetUserTotalsUnsettled(v map[string]float64)`

SetUserTotalsUnsettled sets UserTotalsUnsettled field to given value.

### HasUserTotalsUnsettled

`func (o *RealizedPnlSettlements) HasUserTotalsUnsettled() bool`

HasUserTotalsUnsettled returns a boolean if a field has been set.

### GetTenantTotalsUnsettled

`func (o *RealizedPnlSettlements) GetTenantTotalsUnsettled() map[string]float64`

GetTenantTotalsUnsettled returns the TenantTotalsUnsettled field if non-nil, zero value otherwise.

### GetTenantTotalsUnsettledOk

`func (o *RealizedPnlSettlements) GetTenantTotalsUnsettledOk() (*map[string]float64, bool)`

GetTenantTotalsUnsettledOk returns a tuple with the TenantTotalsUnsettled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantTotalsUnsettled

`func (o *RealizedPnlSettlements) SetTenantTotalsUnsettled(v map[string]float64)`

SetTenantTotalsUnsettled sets TenantTotalsUnsettled field to given value.

### HasTenantTotalsUnsettled

`func (o *RealizedPnlSettlements) HasTenantTotalsUnsettled() bool`

HasTenantTotalsUnsettled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


