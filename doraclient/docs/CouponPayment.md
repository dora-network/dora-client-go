# CouponPayment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**AssetId** | Pointer to **string** |  | [optional] 
**Yield** | Pointer to **float32** |  | [optional] 
**StartAt** | Pointer to **time.Time** |  | [optional] 
**EndAt** | Pointer to **time.Time** |  | [optional] 
**PayAt** | Pointer to **time.Time** |  | [optional] 
**AvailableToPay** | Pointer to **string** |  | [optional] 
**CompletedAt** | Pointer to **time.Time** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**ProcessEvery** | Pointer to **int32** | Number of nanoseconds to wait between coupon payment processing, must be at least 1000 (1 microsecond) | [optional] 
**LastProcessedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewCouponPayment

`func NewCouponPayment() *CouponPayment`

NewCouponPayment instantiates a new CouponPayment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCouponPaymentWithDefaults

`func NewCouponPaymentWithDefaults() *CouponPayment`

NewCouponPaymentWithDefaults instantiates a new CouponPayment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CouponPayment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CouponPayment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CouponPayment) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CouponPayment) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAssetId

`func (o *CouponPayment) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *CouponPayment) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *CouponPayment) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.

### HasAssetId

`func (o *CouponPayment) HasAssetId() bool`

HasAssetId returns a boolean if a field has been set.

### GetYield

`func (o *CouponPayment) GetYield() float32`

GetYield returns the Yield field if non-nil, zero value otherwise.

### GetYieldOk

`func (o *CouponPayment) GetYieldOk() (*float32, bool)`

GetYieldOk returns a tuple with the Yield field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYield

`func (o *CouponPayment) SetYield(v float32)`

SetYield sets Yield field to given value.

### HasYield

`func (o *CouponPayment) HasYield() bool`

HasYield returns a boolean if a field has been set.

### GetStartAt

`func (o *CouponPayment) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *CouponPayment) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *CouponPayment) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *CouponPayment) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetEndAt

`func (o *CouponPayment) GetEndAt() time.Time`

GetEndAt returns the EndAt field if non-nil, zero value otherwise.

### GetEndAtOk

`func (o *CouponPayment) GetEndAtOk() (*time.Time, bool)`

GetEndAtOk returns a tuple with the EndAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndAt

`func (o *CouponPayment) SetEndAt(v time.Time)`

SetEndAt sets EndAt field to given value.

### HasEndAt

`func (o *CouponPayment) HasEndAt() bool`

HasEndAt returns a boolean if a field has been set.

### GetPayAt

`func (o *CouponPayment) GetPayAt() time.Time`

GetPayAt returns the PayAt field if non-nil, zero value otherwise.

### GetPayAtOk

`func (o *CouponPayment) GetPayAtOk() (*time.Time, bool)`

GetPayAtOk returns a tuple with the PayAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayAt

`func (o *CouponPayment) SetPayAt(v time.Time)`

SetPayAt sets PayAt field to given value.

### HasPayAt

`func (o *CouponPayment) HasPayAt() bool`

HasPayAt returns a boolean if a field has been set.

### GetAvailableToPay

`func (o *CouponPayment) GetAvailableToPay() string`

GetAvailableToPay returns the AvailableToPay field if non-nil, zero value otherwise.

### GetAvailableToPayOk

`func (o *CouponPayment) GetAvailableToPayOk() (*string, bool)`

GetAvailableToPayOk returns a tuple with the AvailableToPay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableToPay

`func (o *CouponPayment) SetAvailableToPay(v string)`

SetAvailableToPay sets AvailableToPay field to given value.

### HasAvailableToPay

`func (o *CouponPayment) HasAvailableToPay() bool`

HasAvailableToPay returns a boolean if a field has been set.

### GetCompletedAt

`func (o *CouponPayment) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *CouponPayment) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *CouponPayment) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *CouponPayment) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CouponPayment) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CouponPayment) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CouponPayment) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CouponPayment) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetProcessEvery

`func (o *CouponPayment) GetProcessEvery() int32`

GetProcessEvery returns the ProcessEvery field if non-nil, zero value otherwise.

### GetProcessEveryOk

`func (o *CouponPayment) GetProcessEveryOk() (*int32, bool)`

GetProcessEveryOk returns a tuple with the ProcessEvery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessEvery

`func (o *CouponPayment) SetProcessEvery(v int32)`

SetProcessEvery sets ProcessEvery field to given value.

### HasProcessEvery

`func (o *CouponPayment) HasProcessEvery() bool`

HasProcessEvery returns a boolean if a field has been set.

### GetLastProcessedAt

`func (o *CouponPayment) GetLastProcessedAt() time.Time`

GetLastProcessedAt returns the LastProcessedAt field if non-nil, zero value otherwise.

### GetLastProcessedAtOk

`func (o *CouponPayment) GetLastProcessedAtOk() (*time.Time, bool)`

GetLastProcessedAtOk returns a tuple with the LastProcessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastProcessedAt

`func (o *CouponPayment) SetLastProcessedAt(v time.Time)`

SetLastProcessedAt sets LastProcessedAt field to given value.

### HasLastProcessedAt

`func (o *CouponPayment) HasLastProcessedAt() bool`

HasLastProcessedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


