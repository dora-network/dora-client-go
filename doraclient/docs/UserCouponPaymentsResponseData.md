# UserCouponPaymentsResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CouponPayments** | Pointer to [**[]UserCouponPayment**](UserCouponPayment.md) |  | [optional] 
**SummaryByAsset** | Pointer to [**[]UserCouponPaymentAssetSummary**](UserCouponPaymentAssetSummary.md) |  | [optional] 

## Methods

### NewUserCouponPaymentsResponseData

`func NewUserCouponPaymentsResponseData() *UserCouponPaymentsResponseData`

NewUserCouponPaymentsResponseData instantiates a new UserCouponPaymentsResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserCouponPaymentsResponseDataWithDefaults

`func NewUserCouponPaymentsResponseDataWithDefaults() *UserCouponPaymentsResponseData`

NewUserCouponPaymentsResponseDataWithDefaults instantiates a new UserCouponPaymentsResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCouponPayments

`func (o *UserCouponPaymentsResponseData) GetCouponPayments() []UserCouponPayment`

GetCouponPayments returns the CouponPayments field if non-nil, zero value otherwise.

### GetCouponPaymentsOk

`func (o *UserCouponPaymentsResponseData) GetCouponPaymentsOk() (*[]UserCouponPayment, bool)`

GetCouponPaymentsOk returns a tuple with the CouponPayments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCouponPayments

`func (o *UserCouponPaymentsResponseData) SetCouponPayments(v []UserCouponPayment)`

SetCouponPayments sets CouponPayments field to given value.

### HasCouponPayments

`func (o *UserCouponPaymentsResponseData) HasCouponPayments() bool`

HasCouponPayments returns a boolean if a field has been set.

### GetSummaryByAsset

`func (o *UserCouponPaymentsResponseData) GetSummaryByAsset() []UserCouponPaymentAssetSummary`

GetSummaryByAsset returns the SummaryByAsset field if non-nil, zero value otherwise.

### GetSummaryByAssetOk

`func (o *UserCouponPaymentsResponseData) GetSummaryByAssetOk() (*[]UserCouponPaymentAssetSummary, bool)`

GetSummaryByAssetOk returns a tuple with the SummaryByAsset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummaryByAsset

`func (o *UserCouponPaymentsResponseData) SetSummaryByAsset(v []UserCouponPaymentAssetSummary)`

SetSummaryByAsset sets SummaryByAsset field to given value.

### HasSummaryByAsset

`func (o *UserCouponPaymentsResponseData) HasSummaryByAsset() bool`

HasSummaryByAsset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


