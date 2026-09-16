# AffiliateReferralReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** |  | 
**Referrals** | [**[]AffiliateReferral**](AffiliateReferral.md) |  | 
**HasMore** | **bool** |  | 

## Methods

### NewAffiliateReferralReport

`func NewAffiliateReferralReport(date string, referrals []AffiliateReferral, hasMore bool, ) *AffiliateReferralReport`

NewAffiliateReferralReport instantiates a new AffiliateReferralReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAffiliateReferralReportWithDefaults

`func NewAffiliateReferralReportWithDefaults() *AffiliateReferralReport`

NewAffiliateReferralReportWithDefaults instantiates a new AffiliateReferralReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *AffiliateReferralReport) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *AffiliateReferralReport) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *AffiliateReferralReport) SetDate(v string)`

SetDate sets Date field to given value.


### GetReferrals

`func (o *AffiliateReferralReport) GetReferrals() []AffiliateReferral`

GetReferrals returns the Referrals field if non-nil, zero value otherwise.

### GetReferralsOk

`func (o *AffiliateReferralReport) GetReferralsOk() (*[]AffiliateReferral, bool)`

GetReferralsOk returns a tuple with the Referrals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrals

`func (o *AffiliateReferralReport) SetReferrals(v []AffiliateReferral)`

SetReferrals sets Referrals field to given value.


### GetHasMore

`func (o *AffiliateReferralReport) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *AffiliateReferralReport) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *AffiliateReferralReport) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


