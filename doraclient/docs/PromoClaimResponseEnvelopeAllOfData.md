# PromoClaimResponseEnvelopeAllOfData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**State** | [**PromoClaimState**](PromoClaimState.md) |  | 
**Email** | Pointer to **string** |  | [optional] 
**CampaignName** | Pointer to **string** |  | [optional] 
**PromoCredit** | Pointer to **string** |  | [optional] 
**MinRewardAmount** | Pointer to **string** |  | [optional] 
**MaxRewardAmount** | Pointer to **string** |  | [optional] 
**TargetEquity** | Pointer to **string** |  | [optional] 
**ExpiresAt** | Pointer to **time.Time** |  | [optional] 
**SourceName** | Pointer to **string** |  | [optional] 

## Methods

### NewPromoClaimResponseEnvelopeAllOfData

`func NewPromoClaimResponseEnvelopeAllOfData(state PromoClaimState, ) *PromoClaimResponseEnvelopeAllOfData`

NewPromoClaimResponseEnvelopeAllOfData instantiates a new PromoClaimResponseEnvelopeAllOfData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromoClaimResponseEnvelopeAllOfDataWithDefaults

`func NewPromoClaimResponseEnvelopeAllOfDataWithDefaults() *PromoClaimResponseEnvelopeAllOfData`

NewPromoClaimResponseEnvelopeAllOfDataWithDefaults instantiates a new PromoClaimResponseEnvelopeAllOfData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetState

`func (o *PromoClaimResponseEnvelopeAllOfData) GetState() PromoClaimState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetStateOk() (*PromoClaimState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *PromoClaimResponseEnvelopeAllOfData) SetState(v PromoClaimState)`

SetState sets State field to given value.


### GetEmail

`func (o *PromoClaimResponseEnvelopeAllOfData) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PromoClaimResponseEnvelopeAllOfData) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *PromoClaimResponseEnvelopeAllOfData) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetCampaignName

`func (o *PromoClaimResponseEnvelopeAllOfData) GetCampaignName() string`

GetCampaignName returns the CampaignName field if non-nil, zero value otherwise.

### GetCampaignNameOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetCampaignNameOk() (*string, bool)`

GetCampaignNameOk returns a tuple with the CampaignName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignName

`func (o *PromoClaimResponseEnvelopeAllOfData) SetCampaignName(v string)`

SetCampaignName sets CampaignName field to given value.

### HasCampaignName

`func (o *PromoClaimResponseEnvelopeAllOfData) HasCampaignName() bool`

HasCampaignName returns a boolean if a field has been set.

### GetPromoCredit

`func (o *PromoClaimResponseEnvelopeAllOfData) GetPromoCredit() string`

GetPromoCredit returns the PromoCredit field if non-nil, zero value otherwise.

### GetPromoCreditOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetPromoCreditOk() (*string, bool)`

GetPromoCreditOk returns a tuple with the PromoCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromoCredit

`func (o *PromoClaimResponseEnvelopeAllOfData) SetPromoCredit(v string)`

SetPromoCredit sets PromoCredit field to given value.

### HasPromoCredit

`func (o *PromoClaimResponseEnvelopeAllOfData) HasPromoCredit() bool`

HasPromoCredit returns a boolean if a field has been set.

### GetMinRewardAmount

`func (o *PromoClaimResponseEnvelopeAllOfData) GetMinRewardAmount() string`

GetMinRewardAmount returns the MinRewardAmount field if non-nil, zero value otherwise.

### GetMinRewardAmountOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetMinRewardAmountOk() (*string, bool)`

GetMinRewardAmountOk returns a tuple with the MinRewardAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinRewardAmount

`func (o *PromoClaimResponseEnvelopeAllOfData) SetMinRewardAmount(v string)`

SetMinRewardAmount sets MinRewardAmount field to given value.

### HasMinRewardAmount

`func (o *PromoClaimResponseEnvelopeAllOfData) HasMinRewardAmount() bool`

HasMinRewardAmount returns a boolean if a field has been set.

### GetMaxRewardAmount

`func (o *PromoClaimResponseEnvelopeAllOfData) GetMaxRewardAmount() string`

GetMaxRewardAmount returns the MaxRewardAmount field if non-nil, zero value otherwise.

### GetMaxRewardAmountOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetMaxRewardAmountOk() (*string, bool)`

GetMaxRewardAmountOk returns a tuple with the MaxRewardAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRewardAmount

`func (o *PromoClaimResponseEnvelopeAllOfData) SetMaxRewardAmount(v string)`

SetMaxRewardAmount sets MaxRewardAmount field to given value.

### HasMaxRewardAmount

`func (o *PromoClaimResponseEnvelopeAllOfData) HasMaxRewardAmount() bool`

HasMaxRewardAmount returns a boolean if a field has been set.

### GetTargetEquity

`func (o *PromoClaimResponseEnvelopeAllOfData) GetTargetEquity() string`

GetTargetEquity returns the TargetEquity field if non-nil, zero value otherwise.

### GetTargetEquityOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetTargetEquityOk() (*string, bool)`

GetTargetEquityOk returns a tuple with the TargetEquity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetEquity

`func (o *PromoClaimResponseEnvelopeAllOfData) SetTargetEquity(v string)`

SetTargetEquity sets TargetEquity field to given value.

### HasTargetEquity

`func (o *PromoClaimResponseEnvelopeAllOfData) HasTargetEquity() bool`

HasTargetEquity returns a boolean if a field has been set.

### GetExpiresAt

`func (o *PromoClaimResponseEnvelopeAllOfData) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *PromoClaimResponseEnvelopeAllOfData) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *PromoClaimResponseEnvelopeAllOfData) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetSourceName

`func (o *PromoClaimResponseEnvelopeAllOfData) GetSourceName() string`

GetSourceName returns the SourceName field if non-nil, zero value otherwise.

### GetSourceNameOk

`func (o *PromoClaimResponseEnvelopeAllOfData) GetSourceNameOk() (*string, bool)`

GetSourceNameOk returns a tuple with the SourceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceName

`func (o *PromoClaimResponseEnvelopeAllOfData) SetSourceName(v string)`

SetSourceName sets SourceName field to given value.

### HasSourceName

`func (o *PromoClaimResponseEnvelopeAllOfData) HasSourceName() bool`

HasSourceName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


