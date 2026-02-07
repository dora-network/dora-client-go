# Margin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | **string** | The total margin available from this position. | 
**Used** | **string** | The amount of margin used from this position. | 
**Remaining** | **string** | The margin remaining available from this position. | 

## Methods

### NewMargin

`func NewMargin(available string, used string, remaining string, ) *Margin`

NewMargin instantiates a new Margin object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMarginWithDefaults

`func NewMarginWithDefaults() *Margin`

NewMarginWithDefaults instantiates a new Margin object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailable

`func (o *Margin) GetAvailable() string`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *Margin) GetAvailableOk() (*string, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *Margin) SetAvailable(v string)`

SetAvailable sets Available field to given value.


### GetUsed

`func (o *Margin) GetUsed() string`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *Margin) GetUsedOk() (*string, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *Margin) SetUsed(v string)`

SetUsed sets Used field to given value.


### GetRemaining

`func (o *Margin) GetRemaining() string`

GetRemaining returns the Remaining field if non-nil, zero value otherwise.

### GetRemainingOk

`func (o *Margin) GetRemainingOk() (*string, bool)`

GetRemainingOk returns a tuple with the Remaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemaining

`func (o *Margin) SetRemaining(v string)`

SetRemaining sets Remaining field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


