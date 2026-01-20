# PLSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Leverage** | Pointer to **float64** | The leverage used to obtain the position on the isolated account | [optional] 
**AccountEquity** | Pointer to **float64** |  | [optional] 
**Available** | Pointer to **float64** |  | [optional] 
**Health** | Pointer to **float64** |  | [optional] 

## Methods

### NewPLSummary

`func NewPLSummary() *PLSummary`

NewPLSummary instantiates a new PLSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPLSummaryWithDefaults

`func NewPLSummaryWithDefaults() *PLSummary`

NewPLSummaryWithDefaults instantiates a new PLSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLeverage

`func (o *PLSummary) GetLeverage() float64`

GetLeverage returns the Leverage field if non-nil, zero value otherwise.

### GetLeverageOk

`func (o *PLSummary) GetLeverageOk() (*float64, bool)`

GetLeverageOk returns a tuple with the Leverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeverage

`func (o *PLSummary) SetLeverage(v float64)`

SetLeverage sets Leverage field to given value.

### HasLeverage

`func (o *PLSummary) HasLeverage() bool`

HasLeverage returns a boolean if a field has been set.

### GetAccountEquity

`func (o *PLSummary) GetAccountEquity() float64`

GetAccountEquity returns the AccountEquity field if non-nil, zero value otherwise.

### GetAccountEquityOk

`func (o *PLSummary) GetAccountEquityOk() (*float64, bool)`

GetAccountEquityOk returns a tuple with the AccountEquity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountEquity

`func (o *PLSummary) SetAccountEquity(v float64)`

SetAccountEquity sets AccountEquity field to given value.

### HasAccountEquity

`func (o *PLSummary) HasAccountEquity() bool`

HasAccountEquity returns a boolean if a field has been set.

### GetAvailable

`func (o *PLSummary) GetAvailable() float64`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *PLSummary) GetAvailableOk() (*float64, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *PLSummary) SetAvailable(v float64)`

SetAvailable sets Available field to given value.

### HasAvailable

`func (o *PLSummary) HasAvailable() bool`

HasAvailable returns a boolean if a field has been set.

### GetHealth

`func (o *PLSummary) GetHealth() float64`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *PLSummary) GetHealthOk() (*float64, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *PLSummary) SetHealth(v float64)`

SetHealth sets Health field to given value.

### HasHealth

`func (o *PLSummary) HasHealth() bool`

HasHealth returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


