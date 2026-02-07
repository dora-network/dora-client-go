# StreamUserCouponPaymentsEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Val** | [**UserCouponPayment**](UserCouponPayment.md) |  | 
**Time** | **time.Time** | The timestamp when the data was created | 

## Methods

### NewStreamUserCouponPaymentsEntry

`func NewStreamUserCouponPaymentsEntry(val UserCouponPayment, time time.Time, ) *StreamUserCouponPaymentsEntry`

NewStreamUserCouponPaymentsEntry instantiates a new StreamUserCouponPaymentsEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamUserCouponPaymentsEntryWithDefaults

`func NewStreamUserCouponPaymentsEntryWithDefaults() *StreamUserCouponPaymentsEntry`

NewStreamUserCouponPaymentsEntryWithDefaults instantiates a new StreamUserCouponPaymentsEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVal

`func (o *StreamUserCouponPaymentsEntry) GetVal() UserCouponPayment`

GetVal returns the Val field if non-nil, zero value otherwise.

### GetValOk

`func (o *StreamUserCouponPaymentsEntry) GetValOk() (*UserCouponPayment, bool)`

GetValOk returns a tuple with the Val field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVal

`func (o *StreamUserCouponPaymentsEntry) SetVal(v UserCouponPayment)`

SetVal sets Val field to given value.


### GetTime

`func (o *StreamUserCouponPaymentsEntry) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *StreamUserCouponPaymentsEntry) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *StreamUserCouponPaymentsEntry) SetTime(v time.Time)`

SetTime sets Time field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


