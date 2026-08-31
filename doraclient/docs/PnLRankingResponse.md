# PnLRankingResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** |  | 
**FirstName** | **string** |  | 
**TotalPnl** | **string** |  | 
**RealizedPnl** | **string** | Cumulative realized PnL across the user&#39;s full trading lifetime. | 
**TotalTrades** | **int32** |  | 
**WinningTrades** | **int32** |  | 
**LosingTrades** | **int32** |  | 
**WinRate** | **string** |  | 
**DailyTradingVolume** | **string** | Executed trading volume for the current UTC day. | 
**TotalTradingVolume** | **string** | Cumulative executed trading volume across all UTC trading days. | 
**ActiveTradingDays** | **int32** | Number of distinct UTC days on which the user has at least one executed fill. | 
**Activated** | **bool** | True once the user has traded on at least 5 distinct UTC days. | 
**KycApproved** | **bool** | Whether the user is currently considered KYC/verification approved. | 

## Methods

### NewPnLRankingResponse

`func NewPnLRankingResponse(userId string, firstName string, totalPnl string, realizedPnl string, totalTrades int32, winningTrades int32, losingTrades int32, winRate string, dailyTradingVolume string, totalTradingVolume string, activeTradingDays int32, activated bool, kycApproved bool, ) *PnLRankingResponse`

NewPnLRankingResponse instantiates a new PnLRankingResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPnLRankingResponseWithDefaults

`func NewPnLRankingResponseWithDefaults() *PnLRankingResponse`

NewPnLRankingResponseWithDefaults instantiates a new PnLRankingResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *PnLRankingResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *PnLRankingResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *PnLRankingResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetFirstName

`func (o *PnLRankingResponse) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *PnLRankingResponse) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *PnLRankingResponse) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetTotalPnl

`func (o *PnLRankingResponse) GetTotalPnl() string`

GetTotalPnl returns the TotalPnl field if non-nil, zero value otherwise.

### GetTotalPnlOk

`func (o *PnLRankingResponse) GetTotalPnlOk() (*string, bool)`

GetTotalPnlOk returns a tuple with the TotalPnl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPnl

`func (o *PnLRankingResponse) SetTotalPnl(v string)`

SetTotalPnl sets TotalPnl field to given value.


### GetRealizedPnl

`func (o *PnLRankingResponse) GetRealizedPnl() string`

GetRealizedPnl returns the RealizedPnl field if non-nil, zero value otherwise.

### GetRealizedPnlOk

`func (o *PnLRankingResponse) GetRealizedPnlOk() (*string, bool)`

GetRealizedPnlOk returns a tuple with the RealizedPnl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealizedPnl

`func (o *PnLRankingResponse) SetRealizedPnl(v string)`

SetRealizedPnl sets RealizedPnl field to given value.


### GetTotalTrades

`func (o *PnLRankingResponse) GetTotalTrades() int32`

GetTotalTrades returns the TotalTrades field if non-nil, zero value otherwise.

### GetTotalTradesOk

`func (o *PnLRankingResponse) GetTotalTradesOk() (*int32, bool)`

GetTotalTradesOk returns a tuple with the TotalTrades field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTrades

`func (o *PnLRankingResponse) SetTotalTrades(v int32)`

SetTotalTrades sets TotalTrades field to given value.


### GetWinningTrades

`func (o *PnLRankingResponse) GetWinningTrades() int32`

GetWinningTrades returns the WinningTrades field if non-nil, zero value otherwise.

### GetWinningTradesOk

`func (o *PnLRankingResponse) GetWinningTradesOk() (*int32, bool)`

GetWinningTradesOk returns a tuple with the WinningTrades field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinningTrades

`func (o *PnLRankingResponse) SetWinningTrades(v int32)`

SetWinningTrades sets WinningTrades field to given value.


### GetLosingTrades

`func (o *PnLRankingResponse) GetLosingTrades() int32`

GetLosingTrades returns the LosingTrades field if non-nil, zero value otherwise.

### GetLosingTradesOk

`func (o *PnLRankingResponse) GetLosingTradesOk() (*int32, bool)`

GetLosingTradesOk returns a tuple with the LosingTrades field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLosingTrades

`func (o *PnLRankingResponse) SetLosingTrades(v int32)`

SetLosingTrades sets LosingTrades field to given value.


### GetWinRate

`func (o *PnLRankingResponse) GetWinRate() string`

GetWinRate returns the WinRate field if non-nil, zero value otherwise.

### GetWinRateOk

`func (o *PnLRankingResponse) GetWinRateOk() (*string, bool)`

GetWinRateOk returns a tuple with the WinRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinRate

`func (o *PnLRankingResponse) SetWinRate(v string)`

SetWinRate sets WinRate field to given value.


### GetDailyTradingVolume

`func (o *PnLRankingResponse) GetDailyTradingVolume() string`

GetDailyTradingVolume returns the DailyTradingVolume field if non-nil, zero value otherwise.

### GetDailyTradingVolumeOk

`func (o *PnLRankingResponse) GetDailyTradingVolumeOk() (*string, bool)`

GetDailyTradingVolumeOk returns a tuple with the DailyTradingVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyTradingVolume

`func (o *PnLRankingResponse) SetDailyTradingVolume(v string)`

SetDailyTradingVolume sets DailyTradingVolume field to given value.


### GetTotalTradingVolume

`func (o *PnLRankingResponse) GetTotalTradingVolume() string`

GetTotalTradingVolume returns the TotalTradingVolume field if non-nil, zero value otherwise.

### GetTotalTradingVolumeOk

`func (o *PnLRankingResponse) GetTotalTradingVolumeOk() (*string, bool)`

GetTotalTradingVolumeOk returns a tuple with the TotalTradingVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTradingVolume

`func (o *PnLRankingResponse) SetTotalTradingVolume(v string)`

SetTotalTradingVolume sets TotalTradingVolume field to given value.


### GetActiveTradingDays

`func (o *PnLRankingResponse) GetActiveTradingDays() int32`

GetActiveTradingDays returns the ActiveTradingDays field if non-nil, zero value otherwise.

### GetActiveTradingDaysOk

`func (o *PnLRankingResponse) GetActiveTradingDaysOk() (*int32, bool)`

GetActiveTradingDaysOk returns a tuple with the ActiveTradingDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveTradingDays

`func (o *PnLRankingResponse) SetActiveTradingDays(v int32)`

SetActiveTradingDays sets ActiveTradingDays field to given value.


### GetActivated

`func (o *PnLRankingResponse) GetActivated() bool`

GetActivated returns the Activated field if non-nil, zero value otherwise.

### GetActivatedOk

`func (o *PnLRankingResponse) GetActivatedOk() (*bool, bool)`

GetActivatedOk returns a tuple with the Activated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivated

`func (o *PnLRankingResponse) SetActivated(v bool)`

SetActivated sets Activated field to given value.


### GetKycApproved

`func (o *PnLRankingResponse) GetKycApproved() bool`

GetKycApproved returns the KycApproved field if non-nil, zero value otherwise.

### GetKycApprovedOk

`func (o *PnLRankingResponse) GetKycApprovedOk() (*bool, bool)`

GetKycApprovedOk returns a tuple with the KycApproved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycApproved

`func (o *PnLRankingResponse) SetKycApproved(v bool)`

SetKycApproved sets KycApproved field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


