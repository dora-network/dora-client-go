# LeverageInterestRate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**Utilization** | **float64** |  | 
**AvgUtilization** | **float64** |  | 
**AvgBorrowingYieldRate** | **float64** |  | 
**AvgLendingYieldRate** | **float64** |  | 
**BorrowingYieldRate** | **float64** |  | 
**LendingYieldRate** | **float64** |  | 
**YieldToMaturity** | **float64** |  | 
**StartTime** | **time.Time** |  | 
**EndTime** | **time.Time** |  | 

## Methods

### NewLeverageInterestRate

`func NewLeverageInterestRate(assetId string, utilization float64, avgUtilization float64, avgBorrowingYieldRate float64, avgLendingYieldRate float64, borrowingYieldRate float64, lendingYieldRate float64, yieldToMaturity float64, startTime time.Time, endTime time.Time, ) *LeverageInterestRate`

NewLeverageInterestRate instantiates a new LeverageInterestRate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLeverageInterestRateWithDefaults

`func NewLeverageInterestRateWithDefaults() *LeverageInterestRate`

NewLeverageInterestRateWithDefaults instantiates a new LeverageInterestRate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *LeverageInterestRate) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *LeverageInterestRate) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *LeverageInterestRate) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetUtilization

`func (o *LeverageInterestRate) GetUtilization() float64`

GetUtilization returns the Utilization field if non-nil, zero value otherwise.

### GetUtilizationOk

`func (o *LeverageInterestRate) GetUtilizationOk() (*float64, bool)`

GetUtilizationOk returns a tuple with the Utilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUtilization

`func (o *LeverageInterestRate) SetUtilization(v float64)`

SetUtilization sets Utilization field to given value.


### GetAvgUtilization

`func (o *LeverageInterestRate) GetAvgUtilization() float64`

GetAvgUtilization returns the AvgUtilization field if non-nil, zero value otherwise.

### GetAvgUtilizationOk

`func (o *LeverageInterestRate) GetAvgUtilizationOk() (*float64, bool)`

GetAvgUtilizationOk returns a tuple with the AvgUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgUtilization

`func (o *LeverageInterestRate) SetAvgUtilization(v float64)`

SetAvgUtilization sets AvgUtilization field to given value.


### GetAvgBorrowingYieldRate

`func (o *LeverageInterestRate) GetAvgBorrowingYieldRate() float64`

GetAvgBorrowingYieldRate returns the AvgBorrowingYieldRate field if non-nil, zero value otherwise.

### GetAvgBorrowingYieldRateOk

`func (o *LeverageInterestRate) GetAvgBorrowingYieldRateOk() (*float64, bool)`

GetAvgBorrowingYieldRateOk returns a tuple with the AvgBorrowingYieldRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgBorrowingYieldRate

`func (o *LeverageInterestRate) SetAvgBorrowingYieldRate(v float64)`

SetAvgBorrowingYieldRate sets AvgBorrowingYieldRate field to given value.


### GetAvgLendingYieldRate

`func (o *LeverageInterestRate) GetAvgLendingYieldRate() float64`

GetAvgLendingYieldRate returns the AvgLendingYieldRate field if non-nil, zero value otherwise.

### GetAvgLendingYieldRateOk

`func (o *LeverageInterestRate) GetAvgLendingYieldRateOk() (*float64, bool)`

GetAvgLendingYieldRateOk returns a tuple with the AvgLendingYieldRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgLendingYieldRate

`func (o *LeverageInterestRate) SetAvgLendingYieldRate(v float64)`

SetAvgLendingYieldRate sets AvgLendingYieldRate field to given value.


### GetBorrowingYieldRate

`func (o *LeverageInterestRate) GetBorrowingYieldRate() float64`

GetBorrowingYieldRate returns the BorrowingYieldRate field if non-nil, zero value otherwise.

### GetBorrowingYieldRateOk

`func (o *LeverageInterestRate) GetBorrowingYieldRateOk() (*float64, bool)`

GetBorrowingYieldRateOk returns a tuple with the BorrowingYieldRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowingYieldRate

`func (o *LeverageInterestRate) SetBorrowingYieldRate(v float64)`

SetBorrowingYieldRate sets BorrowingYieldRate field to given value.


### GetLendingYieldRate

`func (o *LeverageInterestRate) GetLendingYieldRate() float64`

GetLendingYieldRate returns the LendingYieldRate field if non-nil, zero value otherwise.

### GetLendingYieldRateOk

`func (o *LeverageInterestRate) GetLendingYieldRateOk() (*float64, bool)`

GetLendingYieldRateOk returns a tuple with the LendingYieldRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLendingYieldRate

`func (o *LeverageInterestRate) SetLendingYieldRate(v float64)`

SetLendingYieldRate sets LendingYieldRate field to given value.


### GetYieldToMaturity

`func (o *LeverageInterestRate) GetYieldToMaturity() float64`

GetYieldToMaturity returns the YieldToMaturity field if non-nil, zero value otherwise.

### GetYieldToMaturityOk

`func (o *LeverageInterestRate) GetYieldToMaturityOk() (*float64, bool)`

GetYieldToMaturityOk returns a tuple with the YieldToMaturity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYieldToMaturity

`func (o *LeverageInterestRate) SetYieldToMaturity(v float64)`

SetYieldToMaturity sets YieldToMaturity field to given value.


### GetStartTime

`func (o *LeverageInterestRate) GetStartTime() time.Time`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *LeverageInterestRate) GetStartTimeOk() (*time.Time, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *LeverageInterestRate) SetStartTime(v time.Time)`

SetStartTime sets StartTime field to given value.


### GetEndTime

`func (o *LeverageInterestRate) GetEndTime() time.Time`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *LeverageInterestRate) GetEndTimeOk() (*time.Time, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *LeverageInterestRate) SetEndTime(v time.Time)`

SetEndTime sets EndTime field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


