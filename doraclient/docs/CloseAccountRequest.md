# CloseAccountRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **string** |  | 
**OrderBookId** | **string** |  | 

## Methods

### NewCloseAccountRequest

`func NewCloseAccountRequest(accountId string, orderBookId string, ) *CloseAccountRequest`

NewCloseAccountRequest instantiates a new CloseAccountRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCloseAccountRequestWithDefaults

`func NewCloseAccountRequestWithDefaults() *CloseAccountRequest`

NewCloseAccountRequestWithDefaults instantiates a new CloseAccountRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *CloseAccountRequest) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *CloseAccountRequest) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *CloseAccountRequest) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.


### GetOrderBookId

`func (o *CloseAccountRequest) GetOrderBookId() string`

GetOrderBookId returns the OrderBookId field if non-nil, zero value otherwise.

### GetOrderBookIdOk

`func (o *CloseAccountRequest) GetOrderBookIdOk() (*string, bool)`

GetOrderBookIdOk returns a tuple with the OrderBookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookId

`func (o *CloseAccountRequest) SetOrderBookId(v string)`

SetOrderBookId sets OrderBookId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


