# HistoricalLeverageInterestRate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**UpdatedAt** | **time.Time** |  | 
**Utilization** | **float64** |  | 
**MaximumUtilization** | **float64** |  | 
**MinimumRate** | **float64** |  | 
**KinkRate** | **float64** |  | 
**MaximumRate** | **float64** |  | 
**KinkUtilization** | **float64** |  | 
**BorrowingYieldRate** | **float64** |  | 
**LendingYieldRate** | **float64** |  | 
**YieldToMaturity** | **float64** |  | 

## Methods

### NewHistoricalLeverageInterestRate

`func NewHistoricalLeverageInterestRate(assetId string, updatedAt time.Time, utilization float64, maximumUtilization float64, minimumRate float64, kinkRate float64, maximumRate float64, kinkUtilization float64, borrowingYieldRate float64, lendingYieldRate float64, yieldToMaturity float64, ) *HistoricalLeverageInterestRate`

NewHistoricalLeverageInterestRate instantiates a new HistoricalLeverageInterestRate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoricalLeverageInterestRateWithDefaults

`func NewHistoricalLeverageInterestRateWithDefaults() *HistoricalLeverageInterestRate`

NewHistoricalLeverageInterestRateWithDefaults instantiates a new HistoricalLeverageInterestRate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *HistoricalLeverageInterestRate) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *HistoricalLeverageInterestRate) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *HistoricalLeverageInterestRate) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetUpdatedAt

`func (o *HistoricalLeverageInterestRate) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *HistoricalLeverageInterestRate) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *HistoricalLeverageInterestRate) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUtilization

`func (o *HistoricalLeverageInterestRate) GetUtilization() float64`

GetUtilization returns the Utilization field if non-nil, zero value otherwise.

### GetUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetUtilizationOk() (*float64, bool)`

GetUtilizationOk returns a tuple with the Utilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUtilization

`func (o *HistoricalLeverageInterestRate) SetUtilization(v float64)`

SetUtilization sets Utilization field to given value.


### GetMaximumUtilization

`func (o *HistoricalLeverageInterestRate) GetMaximumUtilization() float64`

GetMaximumUtilization returns the MaximumUtilization field if non-nil, zero value otherwise.

### GetMaximumUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetMaximumUtilizationOk() (*float64, bool)`

GetMaximumUtilizationOk returns a tuple with the MaximumUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumUtilization

`func (o *HistoricalLeverageInterestRate) SetMaximumUtilization(v float64)`

SetMaximumUtilization sets MaximumUtilization field to given value.


### GetMinimumRate

`func (o *HistoricalLeverageInterestRate) GetMinimumRate() float64`

GetMinimumRate returns the MinimumRate field if non-nil, zero value otherwise.

### GetMinimumRateOk

`func (o *HistoricalLeverageInterestRate) GetMinimumRateOk() (*float64, bool)`

GetMinimumRateOk returns a tuple with the MinimumRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumRate

`func (o *HistoricalLeverageInterestRate) SetMinimumRate(v float64)`

SetMinimumRate sets MinimumRate field to given value.


### GetKinkRate

`func (o *HistoricalLeverageInterestRate) GetKinkRate() float64`

GetKinkRate returns the KinkRate field if non-nil, zero value otherwise.

### GetKinkRateOk

`func (o *HistoricalLeverageInterestRate) GetKinkRateOk() (*float64, bool)`

GetKinkRateOk returns a tuple with the KinkRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinkRate

`func (o *HistoricalLeverageInterestRate) SetKinkRate(v float64)`

SetKinkRate sets KinkRate field to given value.


### GetMaximumRate

`func (o *HistoricalLeverageInterestRate) GetMaximumRate() float64`

GetMaximumRate returns the MaximumRate field if non-nil, zero value otherwise.

### GetMaximumRateOk

`func (o *HistoricalLeverageInterestRate) GetMaximumRateOk() (*float64, bool)`

GetMaximumRateOk returns a tuple with the MaximumRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumRate

`func (o *HistoricalLeverageInterestRate) SetMaximumRate(v float64)`

SetMaximumRate sets MaximumRate field to given value.


### GetKinkUtilization

`func (o *HistoricalLeverageInterestRate) GetKinkUtilization() float64`

GetKinkUtilization returns the KinkUtilization field if non-nil, zero value otherwise.

### GetKinkUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetKinkUtilizationOk() (*float64, bool)`

GetKinkUtilizationOk returns a tuple with the KinkUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinkUtilization

`func (o *HistoricalLeverageInterestRate) SetKinkUtilization(v float64)`

SetKinkUtilization sets KinkUtilization field to given value.


### GetBorrowingYieldRate

`func (o *HistoricalLeverageInterestRate) GetBorrowingYieldRate() float64`

GetBorrowingYieldRate returns the BorrowingYieldRate field if non-nil, zero value otherwise.

### GetBorrowingYieldRateOk

`func (o *HistoricalLeverageInterestRate) GetBorrowingYieldRateOk() (*float64, bool)`

GetBorrowingYieldRateOk returns a tuple with the BorrowingYieldRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowingYieldRate

`func (o *HistoricalLeverageInterestRate) SetBorrowingYieldRate(v float64)`

SetBorrowingYieldRate sets BorrowingYieldRate field to given value.


### GetLendingYieldRate

`func (o *HistoricalLeverageInterestRate) GetLendingYieldRate() float64`

GetLendingYieldRate returns the LendingYieldRate field if non-nil, zero value otherwise.

### GetLendingYieldRateOk

`func (o *HistoricalLeverageInterestRate) GetLendingYieldRateOk() (*float64, bool)`

GetLendingYieldRateOk returns a tuple with the LendingYieldRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLendingYieldRate

`func (o *HistoricalLeverageInterestRate) SetLendingYieldRate(v float64)`

SetLendingYieldRate sets LendingYieldRate field to given value.


### GetYieldToMaturity

`func (o *HistoricalLeverageInterestRate) GetYieldToMaturity() float64`

GetYieldToMaturity returns the YieldToMaturity field if non-nil, zero value otherwise.

### GetYieldToMaturityOk

`func (o *HistoricalLeverageInterestRate) GetYieldToMaturityOk() (*float64, bool)`

GetYieldToMaturityOk returns a tuple with the YieldToMaturity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYieldToMaturity

`func (o *HistoricalLeverageInterestRate) SetYieldToMaturity(v float64)`

SetYieldToMaturity sets YieldToMaturity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


