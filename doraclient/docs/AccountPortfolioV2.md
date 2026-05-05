# AccountPortfolioV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** |  | 
**Accounts** | [**map[string]map[string]AccountV2**](map.md) |  | 
**NetStablecoinEquivalence** | [**TransformedAssets**](TransformedAssets.md) |  | 

## Methods

### NewAccountPortfolioV2

`func NewAccountPortfolioV2(userId string, accounts map[string]map[string]AccountV2, netStablecoinEquivalence TransformedAssets, ) *AccountPortfolioV2`

NewAccountPortfolioV2 instantiates a new AccountPortfolioV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountPortfolioV2WithDefaults

`func NewAccountPortfolioV2WithDefaults() *AccountPortfolioV2`

NewAccountPortfolioV2WithDefaults instantiates a new AccountPortfolioV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *AccountPortfolioV2) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AccountPortfolioV2) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AccountPortfolioV2) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetAccounts

`func (o *AccountPortfolioV2) GetAccounts() map[string]map[string]AccountV2`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *AccountPortfolioV2) GetAccountsOk() (*map[string]map[string]AccountV2, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *AccountPortfolioV2) SetAccounts(v map[string]map[string]AccountV2)`

SetAccounts sets Accounts field to given value.


### GetNetStablecoinEquivalence

`func (o *AccountPortfolioV2) GetNetStablecoinEquivalence() TransformedAssets`

GetNetStablecoinEquivalence returns the NetStablecoinEquivalence field if non-nil, zero value otherwise.

### GetNetStablecoinEquivalenceOk

`func (o *AccountPortfolioV2) GetNetStablecoinEquivalenceOk() (*TransformedAssets, bool)`

GetNetStablecoinEquivalenceOk returns a tuple with the NetStablecoinEquivalence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetStablecoinEquivalence

`func (o *AccountPortfolioV2) SetNetStablecoinEquivalence(v TransformedAssets)`

SetNetStablecoinEquivalence sets NetStablecoinEquivalence field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


