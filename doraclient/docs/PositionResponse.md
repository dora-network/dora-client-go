# PositionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Portfolio** | Pointer to [**Portfolio**](Portfolio.md) |  | [optional] 

## Methods

### NewPositionResponse

`func NewPositionResponse() *PositionResponse`

NewPositionResponse instantiates a new PositionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPositionResponseWithDefaults

`func NewPositionResponseWithDefaults() *PositionResponse`

NewPositionResponseWithDefaults instantiates a new PositionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPortfolio

`func (o *PositionResponse) GetPortfolio() Portfolio`

GetPortfolio returns the Portfolio field if non-nil, zero value otherwise.

### GetPortfolioOk

`func (o *PositionResponse) GetPortfolioOk() (*Portfolio, bool)`

GetPortfolioOk returns a tuple with the Portfolio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortfolio

`func (o *PositionResponse) SetPortfolio(v Portfolio)`

SetPortfolio sets Portfolio field to given value.

### HasPortfolio

`func (o *PositionResponse) HasPortfolio() bool`

HasPortfolio returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


