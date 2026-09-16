# PromoAttributionSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SourceType** | [**PromoSourceType**](PromoSourceType.md) |  | 
**SourceId** | **string** |  | 
**SourceName** | **string** |  | 
**LinksIssued** | **int64** |  | 
**LinksClaimed** | **int64** |  | 
**UsersFunded** | **int64** |  | 
**UsersTraded** | **int64** |  | 
**UsersBusted** | **int64** |  | 
**UsersRewardEligible** | **int64** |  | 
**UsersRewarded** | **int64** |  | 
**TotalVolume** | **string** |  | 
**TotalPnl** | **string** |  | 
**PromoCreditIssued** | **string** |  | 
**RewardsPaid** | **string** |  | 

## Methods

### NewPromoAttributionSource

`func NewPromoAttributionSource(sourceType PromoSourceType, sourceId string, sourceName string, linksIssued int64, linksClaimed int64, usersFunded int64, usersTraded int64, usersBusted int64, usersRewardEligible int64, usersRewarded int64, totalVolume string, totalPnl string, promoCreditIssued string, rewardsPaid string, ) *PromoAttributionSource`

NewPromoAttributionSource instantiates a new PromoAttributionSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromoAttributionSourceWithDefaults

`func NewPromoAttributionSourceWithDefaults() *PromoAttributionSource`

NewPromoAttributionSourceWithDefaults instantiates a new PromoAttributionSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSourceType

`func (o *PromoAttributionSource) GetSourceType() PromoSourceType`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *PromoAttributionSource) GetSourceTypeOk() (*PromoSourceType, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *PromoAttributionSource) SetSourceType(v PromoSourceType)`

SetSourceType sets SourceType field to given value.


### GetSourceId

`func (o *PromoAttributionSource) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *PromoAttributionSource) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *PromoAttributionSource) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.


### GetSourceName

`func (o *PromoAttributionSource) GetSourceName() string`

GetSourceName returns the SourceName field if non-nil, zero value otherwise.

### GetSourceNameOk

`func (o *PromoAttributionSource) GetSourceNameOk() (*string, bool)`

GetSourceNameOk returns a tuple with the SourceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceName

`func (o *PromoAttributionSource) SetSourceName(v string)`

SetSourceName sets SourceName field to given value.


### GetLinksIssued

`func (o *PromoAttributionSource) GetLinksIssued() int64`

GetLinksIssued returns the LinksIssued field if non-nil, zero value otherwise.

### GetLinksIssuedOk

`func (o *PromoAttributionSource) GetLinksIssuedOk() (*int64, bool)`

GetLinksIssuedOk returns a tuple with the LinksIssued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinksIssued

`func (o *PromoAttributionSource) SetLinksIssued(v int64)`

SetLinksIssued sets LinksIssued field to given value.


### GetLinksClaimed

`func (o *PromoAttributionSource) GetLinksClaimed() int64`

GetLinksClaimed returns the LinksClaimed field if non-nil, zero value otherwise.

### GetLinksClaimedOk

`func (o *PromoAttributionSource) GetLinksClaimedOk() (*int64, bool)`

GetLinksClaimedOk returns a tuple with the LinksClaimed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinksClaimed

`func (o *PromoAttributionSource) SetLinksClaimed(v int64)`

SetLinksClaimed sets LinksClaimed field to given value.


### GetUsersFunded

`func (o *PromoAttributionSource) GetUsersFunded() int64`

GetUsersFunded returns the UsersFunded field if non-nil, zero value otherwise.

### GetUsersFundedOk

`func (o *PromoAttributionSource) GetUsersFundedOk() (*int64, bool)`

GetUsersFundedOk returns a tuple with the UsersFunded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsersFunded

`func (o *PromoAttributionSource) SetUsersFunded(v int64)`

SetUsersFunded sets UsersFunded field to given value.


### GetUsersTraded

`func (o *PromoAttributionSource) GetUsersTraded() int64`

GetUsersTraded returns the UsersTraded field if non-nil, zero value otherwise.

### GetUsersTradedOk

`func (o *PromoAttributionSource) GetUsersTradedOk() (*int64, bool)`

GetUsersTradedOk returns a tuple with the UsersTraded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsersTraded

`func (o *PromoAttributionSource) SetUsersTraded(v int64)`

SetUsersTraded sets UsersTraded field to given value.


### GetUsersBusted

`func (o *PromoAttributionSource) GetUsersBusted() int64`

GetUsersBusted returns the UsersBusted field if non-nil, zero value otherwise.

### GetUsersBustedOk

`func (o *PromoAttributionSource) GetUsersBustedOk() (*int64, bool)`

GetUsersBustedOk returns a tuple with the UsersBusted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsersBusted

`func (o *PromoAttributionSource) SetUsersBusted(v int64)`

SetUsersBusted sets UsersBusted field to given value.


### GetUsersRewardEligible

`func (o *PromoAttributionSource) GetUsersRewardEligible() int64`

GetUsersRewardEligible returns the UsersRewardEligible field if non-nil, zero value otherwise.

### GetUsersRewardEligibleOk

`func (o *PromoAttributionSource) GetUsersRewardEligibleOk() (*int64, bool)`

GetUsersRewardEligibleOk returns a tuple with the UsersRewardEligible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsersRewardEligible

`func (o *PromoAttributionSource) SetUsersRewardEligible(v int64)`

SetUsersRewardEligible sets UsersRewardEligible field to given value.


### GetUsersRewarded

`func (o *PromoAttributionSource) GetUsersRewarded() int64`

GetUsersRewarded returns the UsersRewarded field if non-nil, zero value otherwise.

### GetUsersRewardedOk

`func (o *PromoAttributionSource) GetUsersRewardedOk() (*int64, bool)`

GetUsersRewardedOk returns a tuple with the UsersRewarded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsersRewarded

`func (o *PromoAttributionSource) SetUsersRewarded(v int64)`

SetUsersRewarded sets UsersRewarded field to given value.


### GetTotalVolume

`func (o *PromoAttributionSource) GetTotalVolume() string`

GetTotalVolume returns the TotalVolume field if non-nil, zero value otherwise.

### GetTotalVolumeOk

`func (o *PromoAttributionSource) GetTotalVolumeOk() (*string, bool)`

GetTotalVolumeOk returns a tuple with the TotalVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalVolume

`func (o *PromoAttributionSource) SetTotalVolume(v string)`

SetTotalVolume sets TotalVolume field to given value.


### GetTotalPnl

`func (o *PromoAttributionSource) GetTotalPnl() string`

GetTotalPnl returns the TotalPnl field if non-nil, zero value otherwise.

### GetTotalPnlOk

`func (o *PromoAttributionSource) GetTotalPnlOk() (*string, bool)`

GetTotalPnlOk returns a tuple with the TotalPnl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPnl

`func (o *PromoAttributionSource) SetTotalPnl(v string)`

SetTotalPnl sets TotalPnl field to given value.


### GetPromoCreditIssued

`func (o *PromoAttributionSource) GetPromoCreditIssued() string`

GetPromoCreditIssued returns the PromoCreditIssued field if non-nil, zero value otherwise.

### GetPromoCreditIssuedOk

`func (o *PromoAttributionSource) GetPromoCreditIssuedOk() (*string, bool)`

GetPromoCreditIssuedOk returns a tuple with the PromoCreditIssued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromoCreditIssued

`func (o *PromoAttributionSource) SetPromoCreditIssued(v string)`

SetPromoCreditIssued sets PromoCreditIssued field to given value.


### GetRewardsPaid

`func (o *PromoAttributionSource) GetRewardsPaid() string`

GetRewardsPaid returns the RewardsPaid field if non-nil, zero value otherwise.

### GetRewardsPaidOk

`func (o *PromoAttributionSource) GetRewardsPaidOk() (*string, bool)`

GetRewardsPaidOk returns a tuple with the RewardsPaid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRewardsPaid

`func (o *PromoAttributionSource) SetRewardsPaid(v string)`

SetRewardsPaid sets RewardsPaid field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


