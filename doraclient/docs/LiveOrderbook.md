# LiveOrderbook

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bids** | [**[]PriceLevel**](PriceLevel.md) | sorted in desc order by price | 
**Asks** | [**[]PriceLevel**](PriceLevel.md) | sorted in asc order by price | 

## Methods

### NewLiveOrderbook

`func NewLiveOrderbook(bids []PriceLevel, asks []PriceLevel, ) *LiveOrderbook`

NewLiveOrderbook instantiates a new LiveOrderbook object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLiveOrderbookWithDefaults

`func NewLiveOrderbookWithDefaults() *LiveOrderbook`

NewLiveOrderbookWithDefaults instantiates a new LiveOrderbook object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBids

`func (o *LiveOrderbook) GetBids() []PriceLevel`

GetBids returns the Bids field if non-nil, zero value otherwise.

### GetBidsOk

`func (o *LiveOrderbook) GetBidsOk() (*[]PriceLevel, bool)`

GetBidsOk returns a tuple with the Bids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBids

`func (o *LiveOrderbook) SetBids(v []PriceLevel)`

SetBids sets Bids field to given value.


### GetAsks

`func (o *LiveOrderbook) GetAsks() []PriceLevel`

GetAsks returns the Asks field if non-nil, zero value otherwise.

### GetAsksOk

`func (o *LiveOrderbook) GetAsksOk() (*[]PriceLevel, bool)`

GetAsksOk returns a tuple with the Asks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsks

`func (o *LiveOrderbook) SetAsks(v []PriceLevel)`

SetAsks sets Asks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


