# FeeQuoteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WithdrawalId** | **string** | The withdrawal this quote was issued for. The quote token is bound to it and cannot be redeemed against any other withdrawal. | 
**To** | **string** | The withdrawal destination address, read from the withdrawal row. | 
**Quantity** | **string** | Human-decimal USDC withdrawal quantity, read from the withdrawal row. | 
**Fee** | **string** | The estimated network fee, in human USDC. | 
**FeeBaseUnits** | **string** | The estimated network fee, in micro-USDC base units. | 
**ChainId** | **string** | EVM chain ID the quote was computed for. | 
**QuoteToken** | **string** | Signed, TTL-bound quote token to submit to PUT /v1/web3/withdrawals/{withdrawal_id} so the server can validate the fee it quoted. It names the withdrawal it was issued for. | 
**ExpiresAt** | **time.Time** | When the quote token expires. | 

## Methods

### NewFeeQuoteResponse

`func NewFeeQuoteResponse(withdrawalId string, to string, quantity string, fee string, feeBaseUnits string, chainId string, quoteToken string, expiresAt time.Time, ) *FeeQuoteResponse`

NewFeeQuoteResponse instantiates a new FeeQuoteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFeeQuoteResponseWithDefaults

`func NewFeeQuoteResponseWithDefaults() *FeeQuoteResponse`

NewFeeQuoteResponseWithDefaults instantiates a new FeeQuoteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWithdrawalId

`func (o *FeeQuoteResponse) GetWithdrawalId() string`

GetWithdrawalId returns the WithdrawalId field if non-nil, zero value otherwise.

### GetWithdrawalIdOk

`func (o *FeeQuoteResponse) GetWithdrawalIdOk() (*string, bool)`

GetWithdrawalIdOk returns a tuple with the WithdrawalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithdrawalId

`func (o *FeeQuoteResponse) SetWithdrawalId(v string)`

SetWithdrawalId sets WithdrawalId field to given value.


### GetTo

`func (o *FeeQuoteResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *FeeQuoteResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *FeeQuoteResponse) SetTo(v string)`

SetTo sets To field to given value.


### GetQuantity

`func (o *FeeQuoteResponse) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *FeeQuoteResponse) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *FeeQuoteResponse) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetFee

`func (o *FeeQuoteResponse) GetFee() string`

GetFee returns the Fee field if non-nil, zero value otherwise.

### GetFeeOk

`func (o *FeeQuoteResponse) GetFeeOk() (*string, bool)`

GetFeeOk returns a tuple with the Fee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFee

`func (o *FeeQuoteResponse) SetFee(v string)`

SetFee sets Fee field to given value.


### GetFeeBaseUnits

`func (o *FeeQuoteResponse) GetFeeBaseUnits() string`

GetFeeBaseUnits returns the FeeBaseUnits field if non-nil, zero value otherwise.

### GetFeeBaseUnitsOk

`func (o *FeeQuoteResponse) GetFeeBaseUnitsOk() (*string, bool)`

GetFeeBaseUnitsOk returns a tuple with the FeeBaseUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeeBaseUnits

`func (o *FeeQuoteResponse) SetFeeBaseUnits(v string)`

SetFeeBaseUnits sets FeeBaseUnits field to given value.


### GetChainId

`func (o *FeeQuoteResponse) GetChainId() string`

GetChainId returns the ChainId field if non-nil, zero value otherwise.

### GetChainIdOk

`func (o *FeeQuoteResponse) GetChainIdOk() (*string, bool)`

GetChainIdOk returns a tuple with the ChainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChainId

`func (o *FeeQuoteResponse) SetChainId(v string)`

SetChainId sets ChainId field to given value.


### GetQuoteToken

`func (o *FeeQuoteResponse) GetQuoteToken() string`

GetQuoteToken returns the QuoteToken field if non-nil, zero value otherwise.

### GetQuoteTokenOk

`func (o *FeeQuoteResponse) GetQuoteTokenOk() (*string, bool)`

GetQuoteTokenOk returns a tuple with the QuoteToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteToken

`func (o *FeeQuoteResponse) SetQuoteToken(v string)`

SetQuoteToken sets QuoteToken field to given value.


### GetExpiresAt

`func (o *FeeQuoteResponse) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *FeeQuoteResponse) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *FeeQuoteResponse) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


