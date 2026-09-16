# PnLRankingResponses

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Summary** | [**PnLRankingSummary**](PnLRankingSummary.md) |  | 
**Rankings** | [**[]PnLRankingResponse**](PnLRankingResponse.md) |  | 

## Methods

### NewPnLRankingResponses

`func NewPnLRankingResponses(summary PnLRankingSummary, rankings []PnLRankingResponse, ) *PnLRankingResponses`

NewPnLRankingResponses instantiates a new PnLRankingResponses object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPnLRankingResponsesWithDefaults

`func NewPnLRankingResponsesWithDefaults() *PnLRankingResponses`

NewPnLRankingResponsesWithDefaults instantiates a new PnLRankingResponses object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSummary

`func (o *PnLRankingResponses) GetSummary() PnLRankingSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *PnLRankingResponses) GetSummaryOk() (*PnLRankingSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *PnLRankingResponses) SetSummary(v PnLRankingSummary)`

SetSummary sets Summary field to given value.


### GetRankings

`func (o *PnLRankingResponses) GetRankings() []PnLRankingResponse`

GetRankings returns the Rankings field if non-nil, zero value otherwise.

### GetRankingsOk

`func (o *PnLRankingResponses) GetRankingsOk() (*[]PnLRankingResponse, bool)`

GetRankingsOk returns a tuple with the Rankings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRankings

`func (o *PnLRankingResponses) SetRankings(v []PnLRankingResponse)`

SetRankings sets Rankings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


