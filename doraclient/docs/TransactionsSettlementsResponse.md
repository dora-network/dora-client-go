# TransactionsSettlementsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Settlements** | Pointer to [**[]TransactionsSettlement**](TransactionsSettlement.md) |  | [optional] 
**UserTotals** | Pointer to **map[string]float64** |  | [optional] 
**TenantTotals** | Pointer to **map[string]float64** |  | [optional] 

## Methods

### NewTransactionsSettlementsResponse

`func NewTransactionsSettlementsResponse() *TransactionsSettlementsResponse`

NewTransactionsSettlementsResponse instantiates a new TransactionsSettlementsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransactionsSettlementsResponseWithDefaults

`func NewTransactionsSettlementsResponseWithDefaults() *TransactionsSettlementsResponse`

NewTransactionsSettlementsResponseWithDefaults instantiates a new TransactionsSettlementsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSettlements

`func (o *TransactionsSettlementsResponse) GetSettlements() []TransactionsSettlement`

GetSettlements returns the Settlements field if non-nil, zero value otherwise.

### GetSettlementsOk

`func (o *TransactionsSettlementsResponse) GetSettlementsOk() (*[]TransactionsSettlement, bool)`

GetSettlementsOk returns a tuple with the Settlements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlements

`func (o *TransactionsSettlementsResponse) SetSettlements(v []TransactionsSettlement)`

SetSettlements sets Settlements field to given value.

### HasSettlements

`func (o *TransactionsSettlementsResponse) HasSettlements() bool`

HasSettlements returns a boolean if a field has been set.

### GetUserTotals

`func (o *TransactionsSettlementsResponse) GetUserTotals() map[string]float64`

GetUserTotals returns the UserTotals field if non-nil, zero value otherwise.

### GetUserTotalsOk

`func (o *TransactionsSettlementsResponse) GetUserTotalsOk() (*map[string]float64, bool)`

GetUserTotalsOk returns a tuple with the UserTotals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserTotals

`func (o *TransactionsSettlementsResponse) SetUserTotals(v map[string]float64)`

SetUserTotals sets UserTotals field to given value.

### HasUserTotals

`func (o *TransactionsSettlementsResponse) HasUserTotals() bool`

HasUserTotals returns a boolean if a field has been set.

### GetTenantTotals

`func (o *TransactionsSettlementsResponse) GetTenantTotals() map[string]float64`

GetTenantTotals returns the TenantTotals field if non-nil, zero value otherwise.

### GetTenantTotalsOk

`func (o *TransactionsSettlementsResponse) GetTenantTotalsOk() (*map[string]float64, bool)`

GetTenantTotalsOk returns a tuple with the TenantTotals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantTotals

`func (o *TransactionsSettlementsResponse) SetTenantTotals(v map[string]float64)`

SetTenantTotals sets TenantTotals field to given value.

### HasTenantTotals

`func (o *TransactionsSettlementsResponse) HasTenantTotals() bool`

HasTenantTotals returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


