# UserCouponPayment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** |  | 
**PositionId** | **string** |  | 
**AssetId** | **string** |  | 
**CouponPaymentId** | **string** |  | 
**Seq** | **int64** |  | 
**Pending** | **string** |  | 
**Completed** | **string** |  | 
**StartedAt** | **time.Time** |  | 
**EndedAt** | **time.Time** |  | 

## Methods

### NewUserCouponPayment

`func NewUserCouponPayment(userId string, positionId string, assetId string, couponPaymentId string, seq int64, pending string, completed string, startedAt time.Time, endedAt time.Time, ) *UserCouponPayment`

NewUserCouponPayment instantiates a new UserCouponPayment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserCouponPaymentWithDefaults

`func NewUserCouponPaymentWithDefaults() *UserCouponPayment`

NewUserCouponPaymentWithDefaults instantiates a new UserCouponPayment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *UserCouponPayment) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UserCouponPayment) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UserCouponPayment) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetPositionId

`func (o *UserCouponPayment) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *UserCouponPayment) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *UserCouponPayment) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetAssetId

`func (o *UserCouponPayment) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *UserCouponPayment) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *UserCouponPayment) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetCouponPaymentId

`func (o *UserCouponPayment) GetCouponPaymentId() string`

GetCouponPaymentId returns the CouponPaymentId field if non-nil, zero value otherwise.

### GetCouponPaymentIdOk

`func (o *UserCouponPayment) GetCouponPaymentIdOk() (*string, bool)`

GetCouponPaymentIdOk returns a tuple with the CouponPaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCouponPaymentId

`func (o *UserCouponPayment) SetCouponPaymentId(v string)`

SetCouponPaymentId sets CouponPaymentId field to given value.


### GetSeq

`func (o *UserCouponPayment) GetSeq() int64`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *UserCouponPayment) GetSeqOk() (*int64, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *UserCouponPayment) SetSeq(v int64)`

SetSeq sets Seq field to given value.


### GetPending

`func (o *UserCouponPayment) GetPending() string`

GetPending returns the Pending field if non-nil, zero value otherwise.

### GetPendingOk

`func (o *UserCouponPayment) GetPendingOk() (*string, bool)`

GetPendingOk returns a tuple with the Pending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPending

`func (o *UserCouponPayment) SetPending(v string)`

SetPending sets Pending field to given value.


### GetCompleted

`func (o *UserCouponPayment) GetCompleted() string`

GetCompleted returns the Completed field if non-nil, zero value otherwise.

### GetCompletedOk

`func (o *UserCouponPayment) GetCompletedOk() (*string, bool)`

GetCompletedOk returns a tuple with the Completed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleted

`func (o *UserCouponPayment) SetCompleted(v string)`

SetCompleted sets Completed field to given value.


### GetStartedAt

`func (o *UserCouponPayment) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *UserCouponPayment) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *UserCouponPayment) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### GetEndedAt

`func (o *UserCouponPayment) GetEndedAt() time.Time`

GetEndedAt returns the EndedAt field if non-nil, zero value otherwise.

### GetEndedAtOk

`func (o *UserCouponPayment) GetEndedAtOk() (*time.Time, bool)`

GetEndedAtOk returns a tuple with the EndedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndedAt

`func (o *UserCouponPayment) SetEndedAt(v time.Time)`

SetEndedAt sets EndedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


