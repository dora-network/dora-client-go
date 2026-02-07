# LeverageModuleResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Balances** | [**map[string]ModuleBalance**](ModuleBalance.md) | A map of asset IDs to their module balances | 

## Methods

### NewLeverageModuleResponse

`func NewLeverageModuleResponse(balances map[string]ModuleBalance, ) *LeverageModuleResponse`

NewLeverageModuleResponse instantiates a new LeverageModuleResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLeverageModuleResponseWithDefaults

`func NewLeverageModuleResponseWithDefaults() *LeverageModuleResponse`

NewLeverageModuleResponseWithDefaults instantiates a new LeverageModuleResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalances

`func (o *LeverageModuleResponse) GetBalances() map[string]ModuleBalance`

GetBalances returns the Balances field if non-nil, zero value otherwise.

### GetBalancesOk

`func (o *LeverageModuleResponse) GetBalancesOk() (*map[string]ModuleBalance, bool)`

GetBalancesOk returns a tuple with the Balances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalances

`func (o *LeverageModuleResponse) SetBalances(v map[string]ModuleBalance)`

SetBalances sets Balances field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


