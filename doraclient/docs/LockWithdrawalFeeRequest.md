# LockWithdrawalFeeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**QuoteToken** | **string** | The signed quote token returned by GET /v1/web3/withdrawals/fee-quote. It must still be within its TTL and must have been issued for this withdrawal&#39;s destination, quantity, and chain. | 

## Methods

### NewLockWithdrawalFeeRequest

`func NewLockWithdrawalFeeRequest(quoteToken string, ) *LockWithdrawalFeeRequest`

NewLockWithdrawalFeeRequest instantiates a new LockWithdrawalFeeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLockWithdrawalFeeRequestWithDefaults

`func NewLockWithdrawalFeeRequestWithDefaults() *LockWithdrawalFeeRequest`

NewLockWithdrawalFeeRequestWithDefaults instantiates a new LockWithdrawalFeeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuoteToken

`func (o *LockWithdrawalFeeRequest) GetQuoteToken() string`

GetQuoteToken returns the QuoteToken field if non-nil, zero value otherwise.

### GetQuoteTokenOk

`func (o *LockWithdrawalFeeRequest) GetQuoteTokenOk() (*string, bool)`

GetQuoteTokenOk returns a tuple with the QuoteToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteToken

`func (o *LockWithdrawalFeeRequest) SetQuoteToken(v string)`

SetQuoteToken sets QuoteToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


