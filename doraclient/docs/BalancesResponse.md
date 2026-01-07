# BalancesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Balances** | Pointer to [**[]Position**](Position.md) |  | [optional] 

## Methods

### NewBalancesResponse

`func NewBalancesResponse() *BalancesResponse`

NewBalancesResponse instantiates a new BalancesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBalancesResponseWithDefaults

`func NewBalancesResponseWithDefaults() *BalancesResponse`

NewBalancesResponseWithDefaults instantiates a new BalancesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalances

`func (o *BalancesResponse) GetBalances() []Position`

GetBalances returns the Balances field if non-nil, zero value otherwise.

### GetBalancesOk

`func (o *BalancesResponse) GetBalancesOk() (*[]Position, bool)`

GetBalancesOk returns a tuple with the Balances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalances

`func (o *BalancesResponse) SetBalances(v []Position)`

SetBalances sets Balances field to given value.

### HasBalances

`func (o *BalancesResponse) HasBalances() bool`

HasBalances returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


