# CashReserveBreakdown

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedPac** | **string** | Completed PAC (partially accrued coupon) obligations the user owes, in USD. | 
**OutstandingLai** | **string** | Outstanding LAI (leverage accrued interest) the user owes, in USD. | 
**EstimatedFees** | **string** | Estimated trading fees for the current settlement period, capped at a configured fraction (1% by default) of the user&#39;s traded USD volume since 00:00:00 UTC. | 
**BorrowedPortion** | **string** | Configured fraction (10% by default) of the user&#39;s total outstanding borrowed value, in USD. | 
**Floor** | **string** | Configured absolute minimum requirement, in USD. | 
**Total** | **string** | The amount of USD the user must keep available in their Global Account. | 

## Methods

### NewCashReserveBreakdown

`func NewCashReserveBreakdown(completedPac string, outstandingLai string, estimatedFees string, borrowedPortion string, floor string, total string, ) *CashReserveBreakdown`

NewCashReserveBreakdown instantiates a new CashReserveBreakdown object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCashReserveBreakdownWithDefaults

`func NewCashReserveBreakdownWithDefaults() *CashReserveBreakdown`

NewCashReserveBreakdownWithDefaults instantiates a new CashReserveBreakdown object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedPac

`func (o *CashReserveBreakdown) GetCompletedPac() string`

GetCompletedPac returns the CompletedPac field if non-nil, zero value otherwise.

### GetCompletedPacOk

`func (o *CashReserveBreakdown) GetCompletedPacOk() (*string, bool)`

GetCompletedPacOk returns a tuple with the CompletedPac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedPac

`func (o *CashReserveBreakdown) SetCompletedPac(v string)`

SetCompletedPac sets CompletedPac field to given value.


### GetOutstandingLai

`func (o *CashReserveBreakdown) GetOutstandingLai() string`

GetOutstandingLai returns the OutstandingLai field if non-nil, zero value otherwise.

### GetOutstandingLaiOk

`func (o *CashReserveBreakdown) GetOutstandingLaiOk() (*string, bool)`

GetOutstandingLaiOk returns a tuple with the OutstandingLai field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutstandingLai

`func (o *CashReserveBreakdown) SetOutstandingLai(v string)`

SetOutstandingLai sets OutstandingLai field to given value.


### GetEstimatedFees

`func (o *CashReserveBreakdown) GetEstimatedFees() string`

GetEstimatedFees returns the EstimatedFees field if non-nil, zero value otherwise.

### GetEstimatedFeesOk

`func (o *CashReserveBreakdown) GetEstimatedFeesOk() (*string, bool)`

GetEstimatedFeesOk returns a tuple with the EstimatedFees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedFees

`func (o *CashReserveBreakdown) SetEstimatedFees(v string)`

SetEstimatedFees sets EstimatedFees field to given value.


### GetBorrowedPortion

`func (o *CashReserveBreakdown) GetBorrowedPortion() string`

GetBorrowedPortion returns the BorrowedPortion field if non-nil, zero value otherwise.

### GetBorrowedPortionOk

`func (o *CashReserveBreakdown) GetBorrowedPortionOk() (*string, bool)`

GetBorrowedPortionOk returns a tuple with the BorrowedPortion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowedPortion

`func (o *CashReserveBreakdown) SetBorrowedPortion(v string)`

SetBorrowedPortion sets BorrowedPortion field to given value.


### GetFloor

`func (o *CashReserveBreakdown) GetFloor() string`

GetFloor returns the Floor field if non-nil, zero value otherwise.

### GetFloorOk

`func (o *CashReserveBreakdown) GetFloorOk() (*string, bool)`

GetFloorOk returns a tuple with the Floor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFloor

`func (o *CashReserveBreakdown) SetFloor(v string)`

SetFloor sets Floor field to given value.


### GetTotal

`func (o *CashReserveBreakdown) GetTotal() string`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CashReserveBreakdown) GetTotalOk() (*string, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CashReserveBreakdown) SetTotal(v string)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


