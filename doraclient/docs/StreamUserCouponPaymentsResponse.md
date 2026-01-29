# StreamUserCouponPaymentsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Entries** | Pointer to [**[]StreamUserCouponPaymentsEntry**](StreamUserCouponPaymentsEntry.md) |  | [optional] 
**SummaryByAsset** | Pointer to [**[]UserCouponPaymentAssetSummary**](UserCouponPaymentAssetSummary.md) |  | [optional] 

## Methods

### NewStreamUserCouponPaymentsResponse

`func NewStreamUserCouponPaymentsResponse() *StreamUserCouponPaymentsResponse`

NewStreamUserCouponPaymentsResponse instantiates a new StreamUserCouponPaymentsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamUserCouponPaymentsResponseWithDefaults

`func NewStreamUserCouponPaymentsResponseWithDefaults() *StreamUserCouponPaymentsResponse`

NewStreamUserCouponPaymentsResponseWithDefaults instantiates a new StreamUserCouponPaymentsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEntries

`func (o *StreamUserCouponPaymentsResponse) GetEntries() []StreamUserCouponPaymentsEntry`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *StreamUserCouponPaymentsResponse) GetEntriesOk() (*[]StreamUserCouponPaymentsEntry, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *StreamUserCouponPaymentsResponse) SetEntries(v []StreamUserCouponPaymentsEntry)`

SetEntries sets Entries field to given value.

### HasEntries

`func (o *StreamUserCouponPaymentsResponse) HasEntries() bool`

HasEntries returns a boolean if a field has been set.

### GetSummaryByAsset

`func (o *StreamUserCouponPaymentsResponse) GetSummaryByAsset() []UserCouponPaymentAssetSummary`

GetSummaryByAsset returns the SummaryByAsset field if non-nil, zero value otherwise.

### GetSummaryByAssetOk

`func (o *StreamUserCouponPaymentsResponse) GetSummaryByAssetOk() (*[]UserCouponPaymentAssetSummary, bool)`

GetSummaryByAssetOk returns a tuple with the SummaryByAsset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummaryByAsset

`func (o *StreamUserCouponPaymentsResponse) SetSummaryByAsset(v []UserCouponPaymentAssetSummary)`

SetSummaryByAsset sets SummaryByAsset field to given value.

### HasSummaryByAsset

`func (o *StreamUserCouponPaymentsResponse) HasSummaryByAsset() bool`

HasSummaryByAsset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


