# WithdrawalInitiation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WithdrawalId** | **string** |  | 
**UserId** | **string** |  | 
**PositionId** | **string** |  | 
**AssetId** | **string** |  | 
**Quantity** | **string** |  | 
**Status** | [**WithdrawalStatus**](WithdrawalStatus.md) |  | 
**CreatedAt** | **time.Time** |  | 
**CreatedBy** | **string** |  | 
**UpdatedAt** | **time.Time** |  | 
**UpdatedBy** | **string** |  | 
**Reason** | **string** |  | 

## Methods

### NewWithdrawalInitiation

`func NewWithdrawalInitiation(withdrawalId string, userId string, positionId string, assetId string, quantity string, status WithdrawalStatus, createdAt time.Time, createdBy string, updatedAt time.Time, updatedBy string, reason string, ) *WithdrawalInitiation`

NewWithdrawalInitiation instantiates a new WithdrawalInitiation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWithdrawalInitiationWithDefaults

`func NewWithdrawalInitiationWithDefaults() *WithdrawalInitiation`

NewWithdrawalInitiationWithDefaults instantiates a new WithdrawalInitiation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWithdrawalId

`func (o *WithdrawalInitiation) GetWithdrawalId() string`

GetWithdrawalId returns the WithdrawalId field if non-nil, zero value otherwise.

### GetWithdrawalIdOk

`func (o *WithdrawalInitiation) GetWithdrawalIdOk() (*string, bool)`

GetWithdrawalIdOk returns a tuple with the WithdrawalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithdrawalId

`func (o *WithdrawalInitiation) SetWithdrawalId(v string)`

SetWithdrawalId sets WithdrawalId field to given value.


### GetUserId

`func (o *WithdrawalInitiation) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *WithdrawalInitiation) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *WithdrawalInitiation) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetPositionId

`func (o *WithdrawalInitiation) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *WithdrawalInitiation) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *WithdrawalInitiation) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetAssetId

`func (o *WithdrawalInitiation) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *WithdrawalInitiation) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *WithdrawalInitiation) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetQuantity

`func (o *WithdrawalInitiation) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *WithdrawalInitiation) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *WithdrawalInitiation) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetStatus

`func (o *WithdrawalInitiation) GetStatus() WithdrawalStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WithdrawalInitiation) GetStatusOk() (*WithdrawalStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WithdrawalInitiation) SetStatus(v WithdrawalStatus)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *WithdrawalInitiation) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WithdrawalInitiation) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WithdrawalInitiation) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedBy

`func (o *WithdrawalInitiation) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *WithdrawalInitiation) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *WithdrawalInitiation) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetUpdatedAt

`func (o *WithdrawalInitiation) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WithdrawalInitiation) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WithdrawalInitiation) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUpdatedBy

`func (o *WithdrawalInitiation) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *WithdrawalInitiation) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *WithdrawalInitiation) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.


### GetReason

`func (o *WithdrawalInitiation) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *WithdrawalInitiation) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *WithdrawalInitiation) SetReason(v string)`

SetReason sets Reason field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


