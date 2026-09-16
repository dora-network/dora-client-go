# \DefaultAPI

All URIs are relative to *https://staging.dora.co*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddTradingChallengeUsers**](DefaultAPI.md#AddTradingChallengeUsers) | **Put** /v1/trading_challenges/add_users | Add users to a trading challenge
[**ApproveLedgerWithdrawRequest**](DefaultAPI.md#ApproveLedgerWithdrawRequest) | **Post** /v1/ledger/withdraw/requests/{withdrawal_id}/approve | Approve a pending withdrawal request
[**ApproveTradingChallengeRegistrationRequest**](DefaultAPI.md#ApproveTradingChallengeRegistrationRequest) | **Post** /v1/trading_challenges/registration_requests/{request_id}/approve | Approve a trading challenge registration request
[**AssignAffiliateReferral**](DefaultAPI.md#AssignAffiliateReferral) | **Post** /v1/affiliate_referrals/self | Assign your affiliate referrer
[**CancelAllOpenOrders**](DefaultAPI.md#CancelAllOpenOrders) | **Delete** /v1/orders | Cancel all open orders, if user passes orderbook or account_id on query params it will cancel all orders on specific orderbook or account, admin can cancel user&#39;s orders on specific orderbook
[**CancelLedgerWithdrawRequest**](DefaultAPI.md#CancelLedgerWithdrawRequest) | **Post** /v1/ledger/withdraw/requests/{withdrawal_id}/cancel | Cancel a pending withdrawal request
[**CancelOrderById**](DefaultAPI.md#CancelOrderById) | **Delete** /v1/orders/{order_id} | Cancel an order by ID
[**ClaimLeverageGetAccruedInterest**](DefaultAPI.md#ClaimLeverageGetAccruedInterest) | **Post** /v1/leverage/accrued_interest/claim | Claim current accrued leverage interest for a specific user
[**ClaimPromoLink**](DefaultAPI.md#ClaimPromoLink) | **Post** /v1/promo/claim/{token} | Claim a public QR promotion link
[**ClaimTradingChallengePrize**](DefaultAPI.md#ClaimTradingChallengePrize) | **Post** /v1/trading_challenges/{trading_challenge_id}/claim | Claim challenge prize
[**CloseIsolatedAccountV2**](DefaultAPI.md#CloseIsolatedAccountV2) | **Post** /v2/accounts/close | Close an isolated account, repaying the borrowed
[**CloseIsolatedPosition**](DefaultAPI.md#CloseIsolatedPosition) | **Post** /v1/positions/close | Close isolated positions, repaying the borrowed
[**CreateAPIKeyForUser**](DefaultAPI.md#CreateAPIKeyForUser) | **Post** /v1/user/apikey | Create apikey for a user
[**CreateAPIKeyForUserID**](DefaultAPI.md#CreateAPIKeyForUserID) | **Post** /v1/user/{user_id}/apikey | Create apikey for a user
[**CreateAffiliateProgram**](DefaultAPI.md#CreateAffiliateProgram) | **Post** /v1/affiliate_programs | Create an affiliate program
[**CreateConditionalOrder**](DefaultAPI.md#CreateConditionalOrder) | **Post** /v1/orders/conditional | Create a new conditional orders
[**CreateOrder**](DefaultAPI.md#CreateOrder) | **Post** /v1/orders | Create a new order
[**CreateTradingChallenge**](DefaultAPI.md#CreateTradingChallenge) | **Post** /v1/trading_challenges | Create a trading challenge
[**CreateUser**](DefaultAPI.md#CreateUser) | **Post** /v1/integrators/user | Create a new user
[**CreateWithdrawal**](DefaultAPI.md#CreateWithdrawal) | **Post** /v1/web3/withdrawals | Create a USDC withdrawal request
[**DeleteUser**](DefaultAPI.md#DeleteUser) | **Delete** /v1/user/{user_id} | Delete user by ID
[**ExportPromoLinksCSV**](DefaultAPI.md#ExportPromoLinksCSV) | **Get** /v1/link_batches/{batch_id}/links.csv | Export promotional links as CSV
[**GetAPIKeysForUserID**](DefaultAPI.md#GetAPIKeysForUserID) | **Get** /v1/user/{user_id}/apikey | Get user&#39;s api keys: admin or integrator only
[**GetAffiliateProgram**](DefaultAPI.md#GetAffiliateProgram) | **Get** /v1/affiliate_programs/{program_id} | Get an affiliate program
[**GetAllAssetPrices**](DefaultAPI.md#GetAllAssetPrices) | **Get** /v1/price | Get the current price of all assets
[**GetAllPositions**](DefaultAPI.md#GetAllPositions) | **Get** /v1/ledger/positions | Get all users&#39; positions
[**GetAllWithdrawalRequests**](DefaultAPI.md#GetAllWithdrawalRequests) | **Get** /v1/ledger/withdraw/requests | Get all withdrawal requests
[**GetAssetById**](DefaultAPI.md#GetAssetById) | **Get** /v1/assets/{asset_id} | Get asset by ID
[**GetAssetPrice**](DefaultAPI.md#GetAssetPrice) | **Get** /v1/price/asset/{asset_id} | Get the current price of an asset
[**GetAssetYTMById**](DefaultAPI.md#GetAssetYTMById) | **Get** /v1/assets/{asset_id}/ytm | Get annualized yield to maturity for a bond asset
[**GetAssetYieldData**](DefaultAPI.md#GetAssetYieldData) | **Get** /v1/charts/{asset_id}/yield | Get yield chart data for an asset
[**GetAssetsStream**](DefaultAPI.md#GetAssetsStream) | **Get** /v1/assets/stream | Get all inserts or updates for assets
[**GetCandleData**](DefaultAPI.md#GetCandleData) | **Get** /v1/charts/{order_book_id}/candle | Get candlestick data for an orderbook
[**GetCashReserveByUserID**](DefaultAPI.md#GetCashReserveByUserID) | **Get** /v1/accounts/{user_id}/cash_reserve | Get the minimum USD cash reserve requirement for the given user
[**GetCashReserveSelf**](DefaultAPI.md#GetCashReserveSelf) | **Get** /v1/accounts/self/cash_reserve | Get the minimum USD cash reserve requirement for the logged in user
[**GetCopyTraders**](DefaultAPI.md#GetCopyTraders) | **Get** /v1/user/copy_traders | Get list of users with copy trading enabled
[**GetCouponPaymentsByAssetId**](DefaultAPI.md#GetCouponPaymentsByAssetId) | **Get** /v1/assets/{asset_id}/coupon_payments | Get coupon payments for a bond asset
[**GetDepositInstructions**](DefaultAPI.md#GetDepositInstructions) | **Get** /v1/web3/deposit-instructions | Get per-chain instructions for depositing USDC into the Dora vault
[**GetL1Depth**](DefaultAPI.md#GetL1Depth) | **Get** /v1/orderbooks/{order_book_id}/L1 | Get the top price levels for a specific orderbook (L1 market depth)
[**GetL2Depth**](DefaultAPI.md#GetL2Depth) | **Get** /v1/orderbooks/{order_book_id}/L2 | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetL3Depth**](DefaultAPI.md#GetL3Depth) | **Get** /v1/orderbooks/{order_book_id}/L3 | Get all open orders for a specific orderbook (L3 market depth)
[**GetLedgerAccountsSelfV2**](DefaultAPI.md#GetLedgerAccountsSelfV2) | **Get** /v2/ledger/accounts/self | Get your own accounts
[**GetLedgerBalancesSelf**](DefaultAPI.md#GetLedgerBalancesSelf) | **Get** /v1/ledger/balances/self | Get your own available, locked, and borrowed assets
[**GetLedgerInterestSelf**](DefaultAPI.md#GetLedgerInterestSelf) | **Get** /v1/ledger/interest/self | Get your own interest
[**GetLedgerModule**](DefaultAPI.md#GetLedgerModule) | **Get** /v1/ledger/module | Get the entire module object, including unborrowed leverage assets and total leverage trackers
[**GetLedgerModuleByAsset**](DefaultAPI.md#GetLedgerModuleByAsset) | **Get** /v1/ledger/module/{asset_id} | Get the module object for a single asset ID
[**GetLedgerPositionsSelf**](DefaultAPI.md#GetLedgerPositionsSelf) | **Get** /v1/ledger/positions/self | Get your own positions
[**GetLedgerValueSelf**](DefaultAPI.md#GetLedgerValueSelf) | **Get** /v1/ledger/value/self | Get your own available, locked, and borrowed USD value; and realized and unrealized PnL
[**GetLedgerWithdrawRequestsBySelf**](DefaultAPI.md#GetLedgerWithdrawRequestsBySelf) | **Get** /v1/ledger/withdraw/requests/self | Get all pending withdrawal requests for the logged in user
[**GetLedgerWithdrawRequestsByUserID**](DefaultAPI.md#GetLedgerWithdrawRequestsByUserID) | **Get** /v1/ledger/withdraw/requests/{user_id} | Get all pending withdrawal requests for this user
[**GetOrderById**](DefaultAPI.md#GetOrderById) | **Get** /v1/orders/{order_id} | Get order by ID
[**GetOrderbookById**](DefaultAPI.md#GetOrderbookById) | **Get** /v1/orderbooks/{order_book_id} | Get orderbook by ID
[**GetOrderbookDepth**](DefaultAPI.md#GetOrderbookDepth) | **Get** /v1/orderbooks/{order_book_id}/depth | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetOrderbookOrders**](DefaultAPI.md#GetOrderbookOrders) | **Get** /v1/orderbooks/{order_book_id}/orders | Get all open orders for a specific orderbook (L3 market depth)
[**GetOrderbookStats**](DefaultAPI.md#GetOrderbookStats) | **Get** /v1/orderbooks/{order_book_id}/stats | Get orderbook stats
[**GetOrderbookStatsStream**](DefaultAPI.md#GetOrderbookStatsStream) | **Get** /v1/orderbooks/{order_book_id}/stats/stream | Orderbook stats stream
[**GetOrderbookSummary**](DefaultAPI.md#GetOrderbookSummary) | **Get** /v1/orderbooks/{order_book_id}/summary | Get summary of an orderbook
[**GetOrderbookTop**](DefaultAPI.md#GetOrderbookTop) | **Get** /v1/orderbooks/{order_book_id}/top | Get the top price levels for a specific orderbook (L1 market depth)
[**GetPLForSelfByAccount**](DefaultAPI.md#GetPLForSelfByAccount) | **Get** /v1/pl/self | Get account-by-account PL breakdown for the logged in user
[**GetPoolPrice**](DefaultAPI.md#GetPoolPrice) | **Get** /v1/price/pool/{pool_id} | Get the current price of a pool
[**GetPromoAttribution**](DefaultAPI.md#GetPromoAttribution) | **Get** /v1/trading_challenges/{trading_challenge_id}/attribution | Get promotional source attribution
[**GetRealizedPnlSettlements**](DefaultAPI.md#GetRealizedPnlSettlements) | **Get** /v1/realized_pnl_settlements | Get realized P&amp;L settlements with filters
[**GetTopTradersByPnL**](DefaultAPI.md#GetTopTradersByPnL) | **Get** /v1/user/ranking | Get top traders by PnL
[**GetTradeById**](DefaultAPI.md#GetTradeById) | **Get** /v1/trades/{trade_id} | Get a trade by ID
[**GetTrades**](DefaultAPI.md#GetTrades) | **Get** /v1/trades | Get a filtered, paginated list of trades
[**GetTradingChallengeByID**](DefaultAPI.md#GetTradingChallengeByID) | **Get** /v1/trading_challenges/{trading_challenge_id} | Get trading challenge by ID
[**GetTradingChallengeDailySnapshots**](DefaultAPI.md#GetTradingChallengeDailySnapshots) | **Get** /v1/trading_challenges/{trading_challenge_id}/daily_snapshots | Get trading challenge daily snapshots
[**GetTradingChallengeResults**](DefaultAPI.md#GetTradingChallengeResults) | **Get** /v1/trading_challenges/{trading_challenge_id}/results | Get trading challenge results
[**GetTransactionById**](DefaultAPI.md#GetTransactionById) | **Get** /v1/transactions/{transaction_id} | Get a transaction by ID
[**GetTransactions**](DefaultAPI.md#GetTransactions) | **Get** /v1/transactions | Get a filtered, paginated list of transactions
[**GetTransactionsSettlements**](DefaultAPI.md#GetTransactionsSettlements) | **Get** /v1/transactions/settlements | Get transactions settlements with filters
[**GetTransactionsStream**](DefaultAPI.md#GetTransactionsStream) | **Get** /v1/transactions/stream | Get transactions since a specific time, and open a stream for further updates
[**GetUserById**](DefaultAPI.md#GetUserById) | **Get** /v1/user/{user_id} | Get user by ID (admin only)
[**GetUserCouponPaymentsStream**](DefaultAPI.md#GetUserCouponPaymentsStream) | **Get** /v1/user/{user_id}/coupon_payments/stream | Stream user&#39;s coupon payment accruals in real time
[**GetUserDeactivation**](DefaultAPI.md#GetUserDeactivation) | **Get** /v1/user/{user_id}/deactivation | Get the latest account deactivation request for a user
[**GetUserLedgerStream**](DefaultAPI.md#GetUserLedgerStream) | **Get** /v1/user/{user_id}/ledger/stream | Get a snapshot of user&#39;s ledger updates since a specific time, and opens a stream for further updates
[**GetUserLeverageAccruedInterestStream**](DefaultAPI.md#GetUserLeverageAccruedInterestStream) | **Get** /v1/user/{user_id}/leverage/accrued_interest/stream | Stream user&#39;s current leverage accrued interest in real time
[**GetUserOrderUpdatesStream**](DefaultAPI.md#GetUserOrderUpdatesStream) | **Get** /v1/user/{user_id}/orders/{order_book_id}/updates/stream | Get a snapshot of user&#39;s order updates for the given order book since a specific time, and opens a stream for further updates
[**GetUserOrdersUpdatesStreamAll**](DefaultAPI.md#GetUserOrdersUpdatesStreamAll) | **Get** /v1/user/{user_id}/orders/all/updates/stream | Get a snapshot of user&#39;s order updates across all order books since a specific time, and opens a stream for further updates
[**GetUserSelf**](DefaultAPI.md#GetUserSelf) | **Get** /v1/user/self | Get user details for the authenticated user
[**GetUserTransactionsStream**](DefaultAPI.md#GetUserTransactionsStream) | **Get** /v1/user/{user_id}/transactions/stream | Get a snapshot of user&#39;s executed transactions since a specific time, and opens a stream for further updates
[**GetUsers**](DefaultAPI.md#GetUsers) | **Get** /v1/user | Get all users (admin only)
[**GetUsersAPIKeys**](DefaultAPI.md#GetUsersAPIKeys) | **Get** /v1/user/apikey | Get user&#39;s api keys
[**GetWithdrawal**](DefaultAPI.md#GetWithdrawal) | **Get** /v1/web3/withdrawals/{withdrawal_id} | Get a USDC withdrawal by ID
[**GetWithdrawalFeeQuote**](DefaultAPI.md#GetWithdrawalFeeQuote) | **Get** /v1/web3/withdrawals/fee-quote | Estimate the network fee to withdraw USDC via web3
[**IssuePromoLinkBatch**](DefaultAPI.md#IssuePromoLinkBatch) | **Post** /v1/trading_challenges/{trading_challenge_id}/link_batches | Issue a promotional link batch
[**LedgerDeposit**](DefaultAPI.md#LedgerDeposit) | **Post** /v1/ledger/deposit/{user_id} | Deposit assets into this user&#39;s account from the outside world
[**LedgerWithdraw**](DefaultAPI.md#LedgerWithdraw) | **Post** /v1/ledger/withdraw/{user_id} | Withdraw assets from this user to the outside world
[**LedgerWithdrawRequest**](DefaultAPI.md#LedgerWithdrawRequest) | **Post** /v1/ledger/withdraw/requests/{user_id} | Initiate a withdrawal request for this user to the outside world
[**LedgerWithdrawRequestSelf**](DefaultAPI.md#LedgerWithdrawRequestSelf) | **Post** /v1/ledger/withdraw/requests/self | Initiate a withdrawal request for the logged in user to the outside world
[**LeverageGetAccruedInterestByUser**](DefaultAPI.md#LeverageGetAccruedInterestByUser) | **Get** /v1/leverage/accrued_interest/self | Get current accrued leverage interest for the user
[**LeverageGetHistoricalInterestRates**](DefaultAPI.md#LeverageGetHistoricalInterestRates) | **Get** /v1/leverage/interest_rate/{asset_id}/historical | Get historical leverage borrowing and lending yields for a specific asset
[**LeverageGetInterestRate**](DefaultAPI.md#LeverageGetInterestRate) | **Get** /v1/leverage/interest_rate/{asset_id} | Get leverage borrowing and lending yields for a specific asset
[**LeverageIsolateCollateral**](DefaultAPI.md#LeverageIsolateCollateral) | **Post** /v1/leverage/isolate_collateral | Create an isolated position by transferring collateral to the position from the user&#39;s global collateral
[**LeverageSupply**](DefaultAPI.md#LeverageSupply) | **Post** /v1/leverage/supply | Supply leverage for a specific asset
[**LeverageUnite**](DefaultAPI.md#LeverageUnite) | **Post** /v1/leverage/unite | Combines all isolated positions into a single global position
[**LeverageWithdraw**](DefaultAPI.md#LeverageWithdraw) | **Post** /v1/leverage/withdraw | Withdraw leverage for a specific asset
[**LiquidityAdd**](DefaultAPI.md#LiquidityAdd) | **Post** /v1/liquidity/pool/{pool_id}/add | Add liquidity to a pool
[**LiquiditySubtract**](DefaultAPI.md#LiquiditySubtract) | **Post** /v1/liquidity/pool/{pool_id}/remove | Subtract liquidity from a pool
[**ListAccountsSelfV2**](DefaultAPI.md#ListAccountsSelfV2) | **Get** /v2/user/self/accounts | List all accounts for the authenticated user
[**ListAffiliateCashFlows**](DefaultAPI.md#ListAffiliateCashFlows) | **Get** /v1/affiliate_programs/{program_id}/referrals/{user_id}/cash_flows | List a referred user&#39;s customer cash flows
[**ListAffiliatePrograms**](DefaultAPI.md#ListAffiliatePrograms) | **Get** /v1/affiliate_programs | List affiliate programs
[**ListAffiliateReferrals**](DefaultAPI.md#ListAffiliateReferrals) | **Get** /v1/affiliate_programs/{program_id}/referrals | List referred users and activity
[**ListAffiliateReferrers**](DefaultAPI.md#ListAffiliateReferrers) | **Get** /v1/affiliate_programs/{program_id}/referrers | List program referrers
[**ListAssets**](DefaultAPI.md#ListAssets) | **Get** /v1/assets | List assets
[**ListDeposits**](DefaultAPI.md#ListDeposits) | **Get** /v1/web3/deposits | List USDC deposits
[**ListOrderBooks**](DefaultAPI.md#ListOrderBooks) | **Get** /v1/orderbooks | List order books
[**ListOrders**](DefaultAPI.md#ListOrders) | **Get** /v1/orders | List all orders
[**ListOwnAffiliateMemberships**](DefaultAPI.md#ListOwnAffiliateMemberships) | **Get** /v1/affiliate_referrers/self | List your affiliate memberships
[**ListPositionAccountsSelf**](DefaultAPI.md#ListPositionAccountsSelf) | **Get** /v1/user/self/position_accounts | List all position accounts for the authenticated user
[**ListPromoLinkBatches**](DefaultAPI.md#ListPromoLinkBatches) | **Get** /v1/trading_challenges/{trading_challenge_id}/link_batches | List promotional link batches
[**ListPromoLinks**](DefaultAPI.md#ListPromoLinks) | **Get** /v1/link_batches/{batch_id}/links | List promotional links
[**ListTradingChallengeRegistrationRequests**](DefaultAPI.md#ListTradingChallengeRegistrationRequests) | **Get** /v1/trading_challenges/registration_requests | List trading challenge registration requests
[**ListTradingChallenges**](DefaultAPI.md#ListTradingChallenges) | **Get** /v1/trading_challenges | List trading challenges
[**ListUserDeactivations**](DefaultAPI.md#ListUserDeactivations) | **Get** /v1/user/deactivations | Get the current deactivation status across all users
[**ListWithdrawals**](DefaultAPI.md#ListWithdrawals) | **Get** /v1/web3/withdrawals | List USDC withdrawals
[**LookupAffiliateCode**](DefaultAPI.md#LookupAffiliateCode) | **Get** /v1/affiliate_codes/{code} | Look up a reusable referral code
[**PayLeverageGetAccruedInterest**](DefaultAPI.md#PayLeverageGetAccruedInterest) | **Post** /v1/leverage/accrued_interest/pay | Pay current accrued leverage interest for a specific user
[**RegisterAffiliateReferrer**](DefaultAPI.md#RegisterAffiliateReferrer) | **Post** /v1/affiliate_programs/{program_id}/referrers | Register an existing user as a referrer
[**RejectLedgerWithdrawRequest**](DefaultAPI.md#RejectLedgerWithdrawRequest) | **Post** /v1/ledger/withdraw/requests/{withdrawal_id}/reject | Reject a pending withdrawal request
[**RejectTradingChallengeRegistrationRequest**](DefaultAPI.md#RejectTradingChallengeRegistrationRequest) | **Post** /v1/trading_challenges/registration_requests/{request_id}/reject | Reject a trading challenge registration request
[**RemoveTradingChallengeUsers**](DefaultAPI.md#RemoveTradingChallengeUsers) | **Put** /v1/trading_challenges/remove_users | Remove users from a trading challenge
[**RenderPromoLinkQR**](DefaultAPI.md#RenderPromoLinkQR) | **Get** /v1/promo_links/{link_id}/qr | Render a promotional link QR code
[**RepayUSD**](DefaultAPI.md#RepayUSD) | **Post** /v1/positions/repay_usd | Repay borrowed USD, then accrue and pay leverage interest
[**ResolvePromoClaim**](DefaultAPI.md#ResolvePromoClaim) | **Get** /v1/promo/claim/{token} | Resolve a public QR promotion claim link
[**RevokeAPIKeyForUser**](DefaultAPI.md#RevokeAPIKeyForUser) | **Put** /v1/user/apikey/{key_id}/revoke | Revoke apikey for a user
[**RevokeAPIKeyForUserID**](DefaultAPI.md#RevokeAPIKeyForUserID) | **Put** /v1/user/{user_id}/apikey/{key_id}/revoke | Revoke apikey for a user: admin or integrator only
[**RevokePromoLink**](DefaultAPI.md#RevokePromoLink) | **Post** /v1/promo_links/{link_id}/revoke | Revoke a promotional link
[**SettleLeverageAccruedInterest**](DefaultAPI.md#SettleLeverageAccruedInterest) | **Post** /v1/leverage/accrued_interest/settle | Settle current accrued leverage interest for a specific user
[**SettleRealizedPnlRecord**](DefaultAPI.md#SettleRealizedPnlRecord) | **Put** /v1/realized_pnl_settlements/{settlement_id} | Mark a realized P&amp;L settlement as settled
[**SettleTransactionsSettlements**](DefaultAPI.md#SettleTransactionsSettlements) | **Put** /v1/transactions/settlements | Settle multiple transactions settlements in batch
[**StreamAssetPrices**](DefaultAPI.md#StreamAssetPrices) | **Get** /v1/prices/stream | Stream real-time asset prices as map objects
[**StreamCandleData**](DefaultAPI.md#StreamCandleData) | **Get** /v1/charts/{order_book_id}/candle/stream | Get a snapshot of candlestick data from date provided, and open a stream for real-time updates
[**StreamOrderBookBalances**](DefaultAPI.md#StreamOrderBookBalances) | **Get** /v1/orderbooks/{order_book_id}/balances/stream | Get a snapshot of base and quote balances for an order book and open a stream for real-time updates
[**StreamOrderbookOpenOrders**](DefaultAPI.md#StreamOrderbookOpenOrders) | **Get** /v1/orderbooks/{order_book_id}/open/stream | Get a snapshot of open orders in an order book and open a stream for real-time updates
[**StreamTrades**](DefaultAPI.md#StreamTrades) | **Get** /v1/trades/{order_book_id}/stream | Get a snapshot of trades executed on the given order book from a specific date and open a stream for real-time updates
[**TerminateOwnTradingChallengeParticipation**](DefaultAPI.md#TerminateOwnTradingChallengeParticipation) | **Post** /v1/trading_challenges/{trading_challenge_id}/participants/self/terminate | Leave a trading challenge
[**TerminateTradingChallengeParticipation**](DefaultAPI.md#TerminateTradingChallengeParticipation) | **Post** /v1/trading_challenges/{trading_challenge_id}/participants/{user_id}/terminate | Terminate a participation in a trading challenge
[**TransferAccountBalancesV2**](DefaultAPI.md#TransferAccountBalancesV2) | **Post** /v2/accounts/transfer_balances | Transfer available balance between a user&#39;s accounts
[**TransferAvailableBalances**](DefaultAPI.md#TransferAvailableBalances) | **Post** /v1/positions/transfer_balances | Transfer available balance between a user&#39;s accounts (e.g. global to isolated position)
[**UpdateAffiliateProgram**](DefaultAPI.md#UpdateAffiliateProgram) | **Put** /v1/affiliate_programs/{program_id} | Update an affiliate program
[**UpdateTradingChallenge**](DefaultAPI.md#UpdateTradingChallenge) | **Put** /v1/trading_challenges/{trading_challenge_id} | Update a trading challenge
[**UpdateUserConfig**](DefaultAPI.md#UpdateUserConfig) | **Put** /v1/user/{user_id}/config | Update user configuration by ID
[**UpdateUserConfigSelf**](DefaultAPI.md#UpdateUserConfigSelf) | **Put** /v1/user/config/self | Update user configuration for the authenticated user
[**UpdateUserKYC**](DefaultAPI.md#UpdateUserKYC) | **Post** /v1/integrators/user/{user_id}/kyc | Set or clear a user&#39;s KYC completion timestamp
[**ValidateSubmitOrder**](DefaultAPI.md#ValidateSubmitOrder) | **Post** /v1/orders/validate | Validate submit order request data
[**VerifyUser**](DefaultAPI.md#VerifyUser) | **Put** /v1/user/{user_id}/verify | Verify a user by ID



## AddTradingChallengeUsers

> TradingChallengeResponseEnvelope AddTradingChallengeUsers(ctx).AddTradingChallengeUsersRequest(addTradingChallengeUsersRequest).Execute()

Add users to a trading challenge



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	addTradingChallengeUsersRequest := *openapiclient.NewAddTradingChallengeUsersRequest("TradingChallengeId_example") // AddTradingChallengeUsersRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.AddTradingChallengeUsers(context.Background()).AddTradingChallengeUsersRequest(addTradingChallengeUsersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.AddTradingChallengeUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddTradingChallengeUsers`: TradingChallengeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.AddTradingChallengeUsers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAddTradingChallengeUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addTradingChallengeUsersRequest** | [**AddTradingChallengeUsersRequest**](AddTradingChallengeUsersRequest.md) |  | 

### Return type

[**TradingChallengeResponseEnvelope**](TradingChallengeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApproveLedgerWithdrawRequest

> WithdrawalInitiationResponseEnvelope ApproveLedgerWithdrawRequest(ctx, withdrawalId).WithdrawalRequestReason(withdrawalRequestReason).Execute()

Approve a pending withdrawal request



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	withdrawalId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	withdrawalRequestReason := *openapiclient.NewWithdrawalRequestReason("Reason_example") // WithdrawalRequestReason |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ApproveLedgerWithdrawRequest(context.Background(), withdrawalId).WithdrawalRequestReason(withdrawalRequestReason).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ApproveLedgerWithdrawRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveLedgerWithdrawRequest`: WithdrawalInitiationResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ApproveLedgerWithdrawRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**withdrawalId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApproveLedgerWithdrawRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **withdrawalRequestReason** | [**WithdrawalRequestReason**](WithdrawalRequestReason.md) |  | 

### Return type

[**WithdrawalInitiationResponseEnvelope**](WithdrawalInitiationResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApproveTradingChallengeRegistrationRequest

> TradingChallengeRegistrationRequestResponseEnvelope ApproveTradingChallengeRegistrationRequest(ctx, requestId).ReviewTradingChallengeRegistrationRequest(reviewTradingChallengeRegistrationRequest).Execute()

Approve a trading challenge registration request



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	requestId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	reviewTradingChallengeRegistrationRequest := *openapiclient.NewReviewTradingChallengeRegistrationRequest() // ReviewTradingChallengeRegistrationRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ApproveTradingChallengeRegistrationRequest(context.Background(), requestId).ReviewTradingChallengeRegistrationRequest(reviewTradingChallengeRegistrationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ApproveTradingChallengeRegistrationRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveTradingChallengeRegistrationRequest`: TradingChallengeRegistrationRequestResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ApproveTradingChallengeRegistrationRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**requestId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApproveTradingChallengeRegistrationRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **reviewTradingChallengeRegistrationRequest** | [**ReviewTradingChallengeRegistrationRequest**](ReviewTradingChallengeRegistrationRequest.md) |  | 

### Return type

[**TradingChallengeRegistrationRequestResponseEnvelope**](TradingChallengeRegistrationRequestResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AssignAffiliateReferral

> AffiliateAttributionEnvelope AssignAffiliateReferral(ctx).AssignAffiliateReferralRequest(assignAffiliateReferralRequest).Execute()

Assign your affiliate referrer



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assignAffiliateReferralRequest := *openapiclient.NewAssignAffiliateReferralRequest("TEAM-42") // AssignAffiliateReferralRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.AssignAffiliateReferral(context.Background()).AssignAffiliateReferralRequest(assignAffiliateReferralRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.AssignAffiliateReferral``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AssignAffiliateReferral`: AffiliateAttributionEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.AssignAffiliateReferral`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAssignAffiliateReferralRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assignAffiliateReferralRequest** | [**AssignAffiliateReferralRequest**](AssignAffiliateReferralRequest.md) |  | 

### Return type

[**AffiliateAttributionEnvelope**](AffiliateAttributionEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelAllOpenOrders

> ListOrdersResponseEnvelope CancelAllOpenOrders(ctx).OrderBookId(orderBookId).UserId(userId).AccountId(accountId).OrderKind(orderKind).Execute()

Cancel all open orders, if user passes orderbook or account_id on query params it will cancel all orders on specific orderbook or account, admin can cancel user's orders on specific orderbook

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "orderBookId_example" // string |  (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	accountId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	orderKind := openapiclient.OrderKind("LIMIT") // OrderKind |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CancelAllOpenOrders(context.Background()).OrderBookId(orderBookId).UserId(userId).AccountId(accountId).OrderKind(orderKind).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CancelAllOpenOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelAllOpenOrders`: ListOrdersResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CancelAllOpenOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCancelAllOpenOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orderBookId** | **string** |  | 
 **userId** | **string** |  | 
 **accountId** | **string** |  | 
 **orderKind** | [**OrderKind**](OrderKind.md) |  | 

### Return type

[**ListOrdersResponseEnvelope**](ListOrdersResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelLedgerWithdrawRequest

> WithdrawalInitiationResponseEnvelope CancelLedgerWithdrawRequest(ctx, withdrawalId).WithdrawalRequestReason(withdrawalRequestReason).Execute()

Cancel a pending withdrawal request



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	withdrawalId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	withdrawalRequestReason := *openapiclient.NewWithdrawalRequestReason("Reason_example") // WithdrawalRequestReason |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CancelLedgerWithdrawRequest(context.Background(), withdrawalId).WithdrawalRequestReason(withdrawalRequestReason).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CancelLedgerWithdrawRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelLedgerWithdrawRequest`: WithdrawalInitiationResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CancelLedgerWithdrawRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**withdrawalId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelLedgerWithdrawRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **withdrawalRequestReason** | [**WithdrawalRequestReason**](WithdrawalRequestReason.md) |  | 

### Return type

[**WithdrawalInitiationResponseEnvelope**](WithdrawalInitiationResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelOrderById

> CancelOrderResponseEnvelope CancelOrderById(ctx, orderId).Execute()

Cancel an order by ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CancelOrderById(context.Background(), orderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CancelOrderById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelOrderById`: CancelOrderResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CancelOrderById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelOrderByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CancelOrderResponseEnvelope**](CancelOrderResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClaimLeverageGetAccruedInterest

> ClaimLeverageAccruedInterestResponseEnvelope ClaimLeverageGetAccruedInterest(ctx).ClaimLeverageAccruedInterestRequest(claimLeverageAccruedInterestRequest).Execute()

Claim current accrued leverage interest for a specific user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	claimLeverageAccruedInterestRequest := *openapiclient.NewClaimLeverageAccruedInterestRequest("AssetId_example", "PositionId_example") // ClaimLeverageAccruedInterestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ClaimLeverageGetAccruedInterest(context.Background()).ClaimLeverageAccruedInterestRequest(claimLeverageAccruedInterestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ClaimLeverageGetAccruedInterest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClaimLeverageGetAccruedInterest`: ClaimLeverageAccruedInterestResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ClaimLeverageGetAccruedInterest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiClaimLeverageGetAccruedInterestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **claimLeverageAccruedInterestRequest** | [**ClaimLeverageAccruedInterestRequest**](ClaimLeverageAccruedInterestRequest.md) |  | 

### Return type

[**ClaimLeverageAccruedInterestResponseEnvelope**](ClaimLeverageAccruedInterestResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClaimPromoLink

> PromoClaimResponseEnvelope ClaimPromoLink(ctx, token).ClaimPromoLinkRequest(claimPromoLinkRequest).Execute()

Claim a public QR promotion link

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	token := "token_example" // string | Opaque bearer claim token
	claimPromoLinkRequest := *openapiclient.NewClaimPromoLinkRequest("Email_example") // ClaimPromoLinkRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ClaimPromoLink(context.Background(), token).ClaimPromoLinkRequest(claimPromoLinkRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ClaimPromoLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClaimPromoLink`: PromoClaimResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ClaimPromoLink`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**token** | **string** | Opaque bearer claim token | 

### Other Parameters

Other parameters are passed through a pointer to a apiClaimPromoLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **claimPromoLinkRequest** | [**ClaimPromoLinkRequest**](ClaimPromoLinkRequest.md) |  | 

### Return type

[**PromoClaimResponseEnvelope**](PromoClaimResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClaimTradingChallengePrize

> ClaimTradingChallengeResponseEnvelope ClaimTradingChallengePrize(ctx, tradingChallengeId).Execute()

Claim challenge prize



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ClaimTradingChallengePrize(context.Background(), tradingChallengeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ClaimTradingChallengePrize``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClaimTradingChallengePrize`: ClaimTradingChallengeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ClaimTradingChallengePrize`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiClaimTradingChallengePrizeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ClaimTradingChallengeResponseEnvelope**](ClaimTradingChallengeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CloseIsolatedAccountV2

> ClosePositionResponseEnvelope CloseIsolatedAccountV2(ctx).CloseAccountRequest(closeAccountRequest).Execute()

Close an isolated account, repaying the borrowed

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	closeAccountRequest := *openapiclient.NewCloseAccountRequest("AccountId_example", "OrderBookId_example") // CloseAccountRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CloseIsolatedAccountV2(context.Background()).CloseAccountRequest(closeAccountRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CloseIsolatedAccountV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CloseIsolatedAccountV2`: ClosePositionResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CloseIsolatedAccountV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCloseIsolatedAccountV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **closeAccountRequest** | [**CloseAccountRequest**](CloseAccountRequest.md) |  | 

### Return type

[**ClosePositionResponseEnvelope**](ClosePositionResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CloseIsolatedPosition

> ClosePositionResponseEnvelope CloseIsolatedPosition(ctx).ClosePositionRequest(closePositionRequest).Execute()

Close isolated positions, repaying the borrowed

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	closePositionRequest := *openapiclient.NewClosePositionRequest("PositionId_example", "OrderBookId_example") // ClosePositionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CloseIsolatedPosition(context.Background()).ClosePositionRequest(closePositionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CloseIsolatedPosition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CloseIsolatedPosition`: ClosePositionResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CloseIsolatedPosition`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCloseIsolatedPositionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **closePositionRequest** | [**ClosePositionRequest**](ClosePositionRequest.md) |  | 

### Return type

[**ClosePositionResponseEnvelope**](ClosePositionResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAPIKeyForUser

> CreateAPIKeyResponseEnvelope CreateAPIKeyForUser(ctx).CreateAPIKeyRequest(createAPIKeyRequest).Execute()

Create apikey for a user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	createAPIKeyRequest := *openapiclient.NewCreateAPIKeyRequest("Label_example") // CreateAPIKeyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateAPIKeyForUser(context.Background()).CreateAPIKeyRequest(createAPIKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateAPIKeyForUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAPIKeyForUser`: CreateAPIKeyResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateAPIKeyForUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAPIKeyForUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAPIKeyRequest** | [**CreateAPIKeyRequest**](CreateAPIKeyRequest.md) |  | 

### Return type

[**CreateAPIKeyResponseEnvelope**](CreateAPIKeyResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAPIKeyForUserID

> CreateAPIKeyResponseEnvelope CreateAPIKeyForUserID(ctx, userId).CreateAPIKeyRequest(createAPIKeyRequest).Execute()

Create apikey for a user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "userId_example" // string | 
	createAPIKeyRequest := *openapiclient.NewCreateAPIKeyRequest("Label_example") // CreateAPIKeyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateAPIKeyForUserID(context.Background(), userId).CreateAPIKeyRequest(createAPIKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateAPIKeyForUserID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAPIKeyForUserID`: CreateAPIKeyResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateAPIKeyForUserID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateAPIKeyForUserIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createAPIKeyRequest** | [**CreateAPIKeyRequest**](CreateAPIKeyRequest.md) |  | 

### Return type

[**CreateAPIKeyResponseEnvelope**](CreateAPIKeyResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAffiliateProgram

> AffiliateProgramEnvelope CreateAffiliateProgram(ctx).CreateAffiliateProgramRequest(createAffiliateProgramRequest).Execute()

Create an affiliate program



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	createAffiliateProgramRequest := *openapiclient.NewCreateAffiliateProgramRequest("TenantId_example", "Name_example") // CreateAffiliateProgramRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateAffiliateProgram(context.Background()).CreateAffiliateProgramRequest(createAffiliateProgramRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateAffiliateProgram``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAffiliateProgram`: AffiliateProgramEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateAffiliateProgram`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAffiliateProgramRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAffiliateProgramRequest** | [**CreateAffiliateProgramRequest**](CreateAffiliateProgramRequest.md) |  | 

### Return type

[**AffiliateProgramEnvelope**](AffiliateProgramEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateConditionalOrder

> CreateConditionalOrderResponseEnvelope CreateConditionalOrder(ctx).CreateConditionalOrderRequest(createConditionalOrderRequest).Execute()

Create a new conditional orders

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	createConditionalOrderRequest := *openapiclient.NewCreateConditionalOrderRequest("Price_example", "OrderBookId_example", "PositionId_example", "AssetId_example") // CreateConditionalOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateConditionalOrder(context.Background()).CreateConditionalOrderRequest(createConditionalOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateConditionalOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateConditionalOrder`: CreateConditionalOrderResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateConditionalOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateConditionalOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createConditionalOrderRequest** | [**CreateConditionalOrderRequest**](CreateConditionalOrderRequest.md) |  | 

### Return type

[**CreateConditionalOrderResponseEnvelope**](CreateConditionalOrderResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateOrder

> CreateOrderResponseEnvelope CreateOrder(ctx).CreateOrderRequest(createOrderRequest).Execute()

Create a new order

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	createOrderRequest := *openapiclient.NewCreateOrderRequest("Quantity_example", "InverseLeverage_example", openapiclient.OrderKind("LIMIT"), openapiclient.Side("BUY"), false, "OrderBookId_example") // CreateOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateOrder(context.Background()).CreateOrderRequest(createOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOrder`: CreateOrderResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrderRequest** | [**CreateOrderRequest**](CreateOrderRequest.md) |  | 

### Return type

[**CreateOrderResponseEnvelope**](CreateOrderResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateTradingChallenge

> TradingChallengeResponseEnvelope CreateTradingChallenge(ctx).CreateTradingChallengeRequest(createTradingChallengeRequest).Execute()

Create a trading challenge



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	createTradingChallengeRequest := *openapiclient.NewCreateTradingChallengeRequest("TenantId_example", "Name_example", openapiclient.TradingChallengeType("TOURNAMENT"), int32(123), time.Now(), time.Now(), "InitialUserBalance_example") // CreateTradingChallengeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateTradingChallenge(context.Background()).CreateTradingChallengeRequest(createTradingChallengeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateTradingChallenge``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTradingChallenge`: TradingChallengeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateTradingChallenge`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTradingChallengeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createTradingChallengeRequest** | [**CreateTradingChallengeRequest**](CreateTradingChallengeRequest.md) |  | 

### Return type

[**TradingChallengeResponseEnvelope**](TradingChallengeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateUser

> UserCreatedResponseEnvelope CreateUser(ctx).CreateIntegratorUserRequest(createIntegratorUserRequest).Execute()

Create a new user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	createIntegratorUserRequest := *openapiclient.NewCreateIntegratorUserRequest() // CreateIntegratorUserRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateUser(context.Background()).CreateIntegratorUserRequest(createIntegratorUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUser`: UserCreatedResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createIntegratorUserRequest** | [**CreateIntegratorUserRequest**](CreateIntegratorUserRequest.md) |  | 

### Return type

[**UserCreatedResponseEnvelope**](UserCreatedResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateWithdrawal

> WithdrawalResponseEnvelope CreateWithdrawal(ctx).CreateWithdrawalRequest(createWithdrawalRequest).Execute()

Create a USDC withdrawal request



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	createWithdrawalRequest := *openapiclient.NewCreateWithdrawalRequest("WithdrawalId_example", "ToAddress_example", "Quantity_example") // CreateWithdrawalRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateWithdrawal(context.Background()).CreateWithdrawalRequest(createWithdrawalRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateWithdrawal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWithdrawal`: WithdrawalResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateWithdrawal`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateWithdrawalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createWithdrawalRequest** | [**CreateWithdrawalRequest**](CreateWithdrawalRequest.md) |  | 

### Return type

[**WithdrawalResponseEnvelope**](WithdrawalResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteUser

> UserDeletedResponseEnvelope DeleteUser(ctx, userId).Execute()

Delete user by ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.DeleteUser(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.DeleteUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteUser`: UserDeletedResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.DeleteUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserDeletedResponseEnvelope**](UserDeletedResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportPromoLinksCSV

> string ExportPromoLinksCSV(ctx, batchId).Execute()

Export promotional links as CSV



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	batchId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ExportPromoLinksCSV(context.Background(), batchId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ExportPromoLinksCSV``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportPromoLinksCSV`: string
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ExportPromoLinksCSV`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**batchId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiExportPromoLinksCSVRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAPIKeysForUserID

> APIKeyResponseEnvelope GetAPIKeysForUserID(ctx, userId).Execute()

Get user's api keys: admin or integrator only

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "userId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAPIKeysForUserID(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAPIKeysForUserID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAPIKeysForUserID`: APIKeyResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAPIKeysForUserID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAPIKeysForUserIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**APIKeyResponseEnvelope**](APIKeyResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAffiliateProgram

> AffiliateProgramEnvelope GetAffiliateProgram(ctx, programId).Execute()

Get an affiliate program



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	programId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAffiliateProgram(context.Background(), programId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAffiliateProgram``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAffiliateProgram`: AffiliateProgramEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAffiliateProgram`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**programId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAffiliateProgramRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AffiliateProgramEnvelope**](AffiliateProgramEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllAssetPrices

> ListAssetPriceResponseEnvelope GetAllAssetPrices(ctx).Execute()

Get the current price of all assets

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAllAssetPrices(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAllAssetPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllAssetPrices`: ListAssetPriceResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAllAssetPrices`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAllAssetPricesRequest struct via the builder pattern


### Return type

[**ListAssetPriceResponseEnvelope**](ListAssetPriceResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllPositions

> AllPositionsResponseEnvelope GetAllPositions(ctx).Execute()

Get all users' positions

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAllPositions(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAllPositions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllPositions`: AllPositionsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAllPositions`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAllPositionsRequest struct via the builder pattern


### Return type

[**AllPositionsResponseEnvelope**](AllPositionsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllWithdrawalRequests

> AllWithdrawalInitiationsResponseEnvelope GetAllWithdrawalRequests(ctx).Status(status).Execute()

Get all withdrawal requests

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAllWithdrawalRequests(context.Background()).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAllWithdrawalRequests``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllWithdrawalRequests`: AllWithdrawalInitiationsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAllWithdrawalRequests`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllWithdrawalRequestsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** |  | 

### Return type

[**AllWithdrawalInitiationsResponseEnvelope**](AllWithdrawalInitiationsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetById

> GetAssetByIDResponseEnvelope GetAssetById(ctx, assetId).Execute()

Get asset by ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAssetById(context.Background(), assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAssetById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetById`: GetAssetByIDResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAssetById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetAssetByIDResponseEnvelope**](GetAssetByIDResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetPrice

> AssetPriceResponseEnvelope GetAssetPrice(ctx, assetId).Execute()

Get the current price of an asset

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAssetPrice(context.Background(), assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAssetPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetPrice`: AssetPriceResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAssetPrice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AssetPriceResponseEnvelope**](AssetPriceResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetYTMById

> GetAssetYTMByIDResponseEnvelope GetAssetYTMById(ctx, assetId).Execute()

Get annualized yield to maturity for a bond asset

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAssetYTMById(context.Background(), assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAssetYTMById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetYTMById`: GetAssetYTMByIDResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAssetYTMById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetYTMByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetAssetYTMByIDResponseEnvelope**](GetAssetYTMByIDResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetYieldData

> ListAssetYieldResponseEnvelope GetAssetYieldData(ctx, assetId).Start(start).End(end).Resolution(resolution).Execute()

Get yield chart data for an asset



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	start := time.Now() // time.Time | 
	end := time.Now() // time.Time | 
	resolution := openapiclient.AssetYieldResolution("1h") // AssetYieldResolution | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAssetYieldData(context.Background(), assetId).Start(start).End(end).Resolution(resolution).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAssetYieldData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetYieldData`: ListAssetYieldResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAssetYieldData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetYieldDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **start** | **time.Time** |  | 
 **end** | **time.Time** |  | 
 **resolution** | [**AssetYieldResolution**](AssetYieldResolution.md) |  | 

### Return type

[**ListAssetYieldResponseEnvelope**](ListAssetYieldResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetsStream

> []StreamAssetsEntry GetAssetsStream(ctx).Since(since).Until(until).Execute()

Get all inserts or updates for assets

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	since := time.Now() // time.Time |  (optional)
	until := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetAssetsStream(context.Background()).Since(since).Until(until).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetAssetsStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetsStream`: []StreamAssetsEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetAssetsStream`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetsStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **since** | **time.Time** |  | 
 **until** | **time.Time** |  | 

### Return type

[**[]StreamAssetsEntry**](StreamAssetsEntry.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCandleData

> ListCandlesResponseEnvelope GetCandleData(ctx, orderBookId).Start(start).End(end).Resolution(resolution).Execute()

Get candlestick data for an orderbook



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "orderBookId_example" // string | 
	start := time.Now() // time.Time | 
	end := time.Now() // time.Time | 
	resolution := openapiclient.CandleResolution("1m") // CandleResolution |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetCandleData(context.Background(), orderBookId).Start(start).End(end).Resolution(resolution).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetCandleData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCandleData`: ListCandlesResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetCandleData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCandleDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **start** | **time.Time** |  | 
 **end** | **time.Time** |  | 
 **resolution** | [**CandleResolution**](CandleResolution.md) |  | 

### Return type

[**ListCandlesResponseEnvelope**](ListCandlesResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCashReserveByUserID

> CashReserveResponseEnvelope GetCashReserveByUserID(ctx, userId).Execute()

Get the minimum USD cash reserve requirement for the given user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetCashReserveByUserID(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetCashReserveByUserID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCashReserveByUserID`: CashReserveResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetCashReserveByUserID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCashReserveByUserIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CashReserveResponseEnvelope**](CashReserveResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCashReserveSelf

> CashReserveResponseEnvelope GetCashReserveSelf(ctx).Execute()

Get the minimum USD cash reserve requirement for the logged in user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetCashReserveSelf(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetCashReserveSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCashReserveSelf`: CashReserveResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetCashReserveSelf`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCashReserveSelfRequest struct via the builder pattern


### Return type

[**CashReserveResponseEnvelope**](CashReserveResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCopyTraders

> GetCopyTradersResponse GetCopyTraders(ctx).Page(page).Limit(limit).Execute()

Get list of users with copy trading enabled

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetCopyTraders(context.Background()).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetCopyTraders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCopyTraders`: GetCopyTradersResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetCopyTraders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCopyTradersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | [default to 1]
 **limit** | **int32** |  | [default to 100]

### Return type

[**GetCopyTradersResponse**](GetCopyTradersResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCouponPaymentsByAssetId

> ListCouponPaymentsResponseEnvelope GetCouponPaymentsByAssetId(ctx, assetId).Execute()

Get coupon payments for a bond asset

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetCouponPaymentsByAssetId(context.Background(), assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetCouponPaymentsByAssetId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCouponPaymentsByAssetId`: ListCouponPaymentsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetCouponPaymentsByAssetId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCouponPaymentsByAssetIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListCouponPaymentsResponseEnvelope**](ListCouponPaymentsResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDepositInstructions

> DepositInstructionsResponseEnvelope GetDepositInstructions(ctx).Quantity(quantity).OwnerAddress(ownerAddress).Nonce(nonce).ClientReferenceId(clientReferenceId).Execute()

Get per-chain instructions for depositing USDC into the Dora vault



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	quantity := "quantity_example" // string | Human-decimal USDC quantity to deposit, e.g. '100.50'. Must be positive, with at most 6 decimal places.
	ownerAddress := "ownerAddress_example" // string | The user's wallet address as a 0x-prefixed 20-byte hex string. Used as the permit owner.
	nonce := "nonce_example" // string | The owner's current USDC permit nonce (read client-side), as a non-negative decimal string. It belongs to the single supported chain.
	clientReferenceId := "clientReferenceId_example" // string | Optional client-supplied reference as a hex string (0x prefix optional), at most 32 bytes. Left-aligned into the deposit call's bytes32 argument. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetDepositInstructions(context.Background()).Quantity(quantity).OwnerAddress(ownerAddress).Nonce(nonce).ClientReferenceId(clientReferenceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetDepositInstructions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDepositInstructions`: DepositInstructionsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetDepositInstructions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDepositInstructionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **quantity** | **string** | Human-decimal USDC quantity to deposit, e.g. &#39;100.50&#39;. Must be positive, with at most 6 decimal places. | 
 **ownerAddress** | **string** | The user&#39;s wallet address as a 0x-prefixed 20-byte hex string. Used as the permit owner. | 
 **nonce** | **string** | The owner&#39;s current USDC permit nonce (read client-side), as a non-negative decimal string. It belongs to the single supported chain. | 
 **clientReferenceId** | **string** | Optional client-supplied reference as a hex string (0x prefix optional), at most 32 bytes. Left-aligned into the deposit call&#39;s bytes32 argument. | 

### Return type

[**DepositInstructionsResponseEnvelope**](DepositInstructionsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetL1Depth

> GetTopOfBookResponseEnvelope GetL1Depth(ctx, orderBookId).Execute()

Get the top price levels for a specific orderbook (L1 market depth)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetL1Depth(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetL1Depth``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetL1Depth`: GetTopOfBookResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetL1Depth`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetL1DepthRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetTopOfBookResponseEnvelope**](GetTopOfBookResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetL2Depth

> ListOrderBookDepthResponseEnvelope GetL2Depth(ctx, orderBookId).Execute()

Get the aggregated price levels for a specific orderbook (L2 market depth)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetL2Depth(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetL2Depth``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetL2Depth`: ListOrderBookDepthResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetL2Depth`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetL2DepthRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListOrderBookDepthResponseEnvelope**](ListOrderBookDepthResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetL3Depth

> ListOrdersResponseEnvelope GetL3Depth(ctx, orderBookId).Execute()

Get all open orders for a specific orderbook (L3 market depth)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetL3Depth(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetL3Depth``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetL3Depth`: ListOrdersResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetL3Depth`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetL3DepthRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListOrdersResponseEnvelope**](ListOrdersResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerAccountsSelfV2

> LedgerAccountsResponseV2Envelope GetLedgerAccountsSelfV2(ctx).Execute()

Get your own accounts

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerAccountsSelfV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerAccountsSelfV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerAccountsSelfV2`: LedgerAccountsResponseV2Envelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerAccountsSelfV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerAccountsSelfV2Request struct via the builder pattern


### Return type

[**LedgerAccountsResponseV2Envelope**](LedgerAccountsResponseV2Envelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerBalancesSelf

> UserBalanceResponseEnvelope GetLedgerBalancesSelf(ctx).Execute()

Get your own available, locked, and borrowed assets

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerBalancesSelf(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerBalancesSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerBalancesSelf`: UserBalanceResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerBalancesSelf`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerBalancesSelfRequest struct via the builder pattern


### Return type

[**UserBalanceResponseEnvelope**](UserBalanceResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerInterestSelf

> UserInterestResponseEnvelope GetLedgerInterestSelf(ctx).Execute()

Get your own interest

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerInterestSelf(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerInterestSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerInterestSelf`: UserInterestResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerInterestSelf`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerInterestSelfRequest struct via the builder pattern


### Return type

[**UserInterestResponseEnvelope**](UserInterestResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerModule

> LedgerModuleResponseEnvelope GetLedgerModule(ctx).Execute()

Get the entire module object, including unborrowed leverage assets and total leverage trackers

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerModule(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerModule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerModule`: LedgerModuleResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerModule`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerModuleRequest struct via the builder pattern


### Return type

[**LedgerModuleResponseEnvelope**](LedgerModuleResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerModuleByAsset

> LedgerModuleByAssetResponseEnvelope GetLedgerModuleByAsset(ctx, assetId).Execute()

Get the module object for a single asset ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerModuleByAsset(context.Background(), assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerModuleByAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerModuleByAsset`: LedgerModuleByAssetResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerModuleByAsset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerModuleByAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LedgerModuleByAssetResponseEnvelope**](LedgerModuleByAssetResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerPositionsSelf

> UserPositionResponseEnvelope GetLedgerPositionsSelf(ctx).Execute()

Get your own positions

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerPositionsSelf(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerPositionsSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerPositionsSelf`: UserPositionResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerPositionsSelf`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerPositionsSelfRequest struct via the builder pattern


### Return type

[**UserPositionResponseEnvelope**](UserPositionResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerValueSelf

> UserValueResponseEnvelope GetLedgerValueSelf(ctx).Execute()

Get your own available, locked, and borrowed USD value; and realized and unrealized PnL

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerValueSelf(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerValueSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerValueSelf`: UserValueResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerValueSelf`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerValueSelfRequest struct via the builder pattern


### Return type

[**UserValueResponseEnvelope**](UserValueResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerWithdrawRequestsBySelf

> AllWithdrawalInitiationsResponseEnvelope GetLedgerWithdrawRequestsBySelf(ctx).Status(status).Execute()

Get all pending withdrawal requests for the logged in user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerWithdrawRequestsBySelf(context.Background()).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerWithdrawRequestsBySelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerWithdrawRequestsBySelf`: AllWithdrawalInitiationsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerWithdrawRequestsBySelf`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerWithdrawRequestsBySelfRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** |  | 

### Return type

[**AllWithdrawalInitiationsResponseEnvelope**](AllWithdrawalInitiationsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLedgerWithdrawRequestsByUserID

> AllWithdrawalInitiationsResponseEnvelope GetLedgerWithdrawRequestsByUserID(ctx, userId).Status(status).Execute()

Get all pending withdrawal requests for this user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetLedgerWithdrawRequestsByUserID(context.Background(), userId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetLedgerWithdrawRequestsByUserID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLedgerWithdrawRequestsByUserID`: AllWithdrawalInitiationsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetLedgerWithdrawRequestsByUserID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetLedgerWithdrawRequestsByUserIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **status** | **string** |  | 

### Return type

[**AllWithdrawalInitiationsResponseEnvelope**](AllWithdrawalInitiationsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderById

> OrderResponseEnvelope GetOrderById(ctx, orderId).Execute()

Get order by ID



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrderById(context.Background(), orderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrderById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderById`: OrderResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrderById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrderResponseEnvelope**](OrderResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderbookById

> OrderBookResponseEnvelope GetOrderbookById(ctx, orderBookId).Execute()

Get orderbook by ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrderbookById(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrderbookById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderbookById`: OrderBookResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrderbookById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderbookByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrderBookResponseEnvelope**](OrderBookResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderbookDepth

> ListOrderBookDepthResponseEnvelope GetOrderbookDepth(ctx, orderBookId).Execute()

Get the aggregated price levels for a specific orderbook (L2 market depth)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrderbookDepth(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrderbookDepth``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderbookDepth`: ListOrderBookDepthResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrderbookDepth`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderbookDepthRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListOrderBookDepthResponseEnvelope**](ListOrderBookDepthResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderbookOrders

> ListOrdersResponseEnvelope GetOrderbookOrders(ctx, orderBookId).Execute()

Get all open orders for a specific orderbook (L3 market depth)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrderbookOrders(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrderbookOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderbookOrders`: ListOrdersResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrderbookOrders`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderbookOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListOrdersResponseEnvelope**](ListOrdersResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderbookStats

> OrderbookStatsResponseEnvelope GetOrderbookStats(ctx, orderBookId).Execute()

Get orderbook stats

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrderbookStats(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrderbookStats``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderbookStats`: OrderbookStatsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrderbookStats`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderbookStatsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrderbookStatsResponseEnvelope**](OrderbookStatsResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderbookStatsStream

> OrderbookStats GetOrderbookStatsStream(ctx, orderBookId).Execute()

Orderbook stats stream

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrderbookStatsStream(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrderbookStatsStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderbookStatsStream`: OrderbookStats
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrderbookStatsStream`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderbookStatsStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrderbookStats**](OrderbookStats.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderbookSummary

> OrderBookSummaryResponseEnvelope GetOrderbookSummary(ctx, orderBookId).Execute()

Get summary of an orderbook

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrderbookSummary(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrderbookSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderbookSummary`: OrderBookSummaryResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrderbookSummary`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderbookSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrderBookSummaryResponseEnvelope**](OrderBookSummaryResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderbookTop

> GetTopOfBookResponseEnvelope GetOrderbookTop(ctx, orderBookId).Execute()

Get the top price levels for a specific orderbook (L1 market depth)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrderbookTop(context.Background(), orderBookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrderbookTop``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderbookTop`: GetTopOfBookResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrderbookTop`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderbookTopRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetTopOfBookResponseEnvelope**](GetTopOfBookResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPLForSelfByAccount

> PLResponseEnvelope GetPLForSelfByAccount(ctx).Execute()

Get account-by-account PL breakdown for the logged in user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetPLForSelfByAccount(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetPLForSelfByAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPLForSelfByAccount`: PLResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetPLForSelfByAccount`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetPLForSelfByAccountRequest struct via the builder pattern


### Return type

[**PLResponseEnvelope**](PLResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPoolPrice

> PoolPriceResponseEnvelope GetPoolPrice(ctx, poolId).Execute()

Get the current price of a pool

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	poolId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetPoolPrice(context.Background(), poolId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetPoolPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPoolPrice`: PoolPriceResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetPoolPrice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPoolPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PoolPriceResponseEnvelope**](PoolPriceResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPromoAttribution

> PromoAttributionResponse GetPromoAttribution(ctx, tradingChallengeId).Execute()

Get promotional source attribution



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetPromoAttribution(context.Background(), tradingChallengeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetPromoAttribution``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPromoAttribution`: PromoAttributionResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetPromoAttribution`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPromoAttributionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PromoAttributionResponse**](PromoAttributionResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRealizedPnlSettlements

> GetRealizedPnlSettlementsResponseEnvelope GetRealizedPnlSettlements(ctx).UserId(userId).TenantId(tenantId).PositionId(positionId).CreatedAfter(createdAfter).CreatedBefore(createdBefore).SettledAfter(settledAfter).SettledBefore(settledBefore).IsSettled(isSettled).Execute()

Get realized P&L settlements with filters

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	tenantId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	positionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	createdAfter := time.Now() // time.Time |  (optional)
	createdBefore := time.Now() // time.Time |  (optional)
	settledAfter := time.Now() // time.Time |  (optional)
	settledBefore := time.Now() // time.Time |  (optional)
	isSettled := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetRealizedPnlSettlements(context.Background()).UserId(userId).TenantId(tenantId).PositionId(positionId).CreatedAfter(createdAfter).CreatedBefore(createdBefore).SettledAfter(settledAfter).SettledBefore(settledBefore).IsSettled(isSettled).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetRealizedPnlSettlements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRealizedPnlSettlements`: GetRealizedPnlSettlementsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetRealizedPnlSettlements`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetRealizedPnlSettlementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **string** |  | 
 **tenantId** | **string** |  | 
 **positionId** | **string** |  | 
 **createdAfter** | **time.Time** |  | 
 **createdBefore** | **time.Time** |  | 
 **settledAfter** | **time.Time** |  | 
 **settledBefore** | **time.Time** |  | 
 **isSettled** | **bool** |  | 

### Return type

[**GetRealizedPnlSettlementsResponseEnvelope**](GetRealizedPnlSettlementsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTopTradersByPnL

> GetPnLRankingResponse GetTopTradersByPnL(ctx).Start(start).End(end).Page(page).Limit(limit).All(all).Execute()

Get top traders by PnL



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	start := time.Now() // time.Time | Start timestamp (inclusive) in RFC3339 format.
	end := time.Now() // time.Time | End timestamp (exclusive) in RFC3339 format.
	page := int32(56) // int32 | 1-based page number for pagination. (optional) (default to 1)
	limit := int32(56) // int32 | Number of records per page (max 100). Defaults to 100. (optional) (default to 100)
	all := true // bool | When true, includes users with allow_copy_trading=false. Requires admin role. (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTopTradersByPnL(context.Background()).Start(start).End(end).Page(page).Limit(limit).All(all).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTopTradersByPnL``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTopTradersByPnL`: GetPnLRankingResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTopTradersByPnL`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTopTradersByPnLRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **start** | **time.Time** | Start timestamp (inclusive) in RFC3339 format. | 
 **end** | **time.Time** | End timestamp (exclusive) in RFC3339 format. | 
 **page** | **int32** | 1-based page number for pagination. | [default to 1]
 **limit** | **int32** | Number of records per page (max 100). Defaults to 100. | [default to 100]
 **all** | **bool** | When true, includes users with allow_copy_trading&#x3D;false. Requires admin role. | [default to false]

### Return type

[**GetPnLRankingResponse**](GetPnLRankingResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTradeById

> TradeResponseEnvelope GetTradeById(ctx, tradeId).Execute()

Get a trade by ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTradeById(context.Background(), tradeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTradeById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTradeById`: TradeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTradeById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTradeByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TradeResponseEnvelope**](TradeResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTrades

> ListTradeResponseEnvelope GetTrades(ctx).OrderBookIds(orderBookIds).UserIds(userIds).Start(start).End(end).Page(page).Limit(limit).Execute()

Get a filtered, paginated list of trades

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookIds := []string{"Inner_example"} // []string |  (optional)
	userIds := []string{"Inner_example"} // []string |  (optional)
	start := time.Now() // time.Time |  (optional)
	end := time.Now() // time.Time |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTrades(context.Background()).OrderBookIds(orderBookIds).UserIds(userIds).Start(start).End(end).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTrades``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTrades`: ListTradeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTrades`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTradesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orderBookIds** | **[]string** |  | 
 **userIds** | **[]string** |  | 
 **start** | **time.Time** |  | 
 **end** | **time.Time** |  | 
 **page** | **int32** |  | [default to 1]
 **limit** | **int32** |  | [default to 100]

### Return type

[**ListTradeResponseEnvelope**](ListTradeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTradingChallengeByID

> TradingChallengeResponseEnvelope GetTradingChallengeByID(ctx, tradingChallengeId).Execute()

Get trading challenge by ID



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTradingChallengeByID(context.Background(), tradingChallengeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTradingChallengeByID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTradingChallengeByID`: TradingChallengeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTradingChallengeByID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTradingChallengeByIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TradingChallengeResponseEnvelope**](TradingChallengeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTradingChallengeDailySnapshots

> TradingChallengeDailySnapshotsResponseEnvelope GetTradingChallengeDailySnapshots(ctx, tradingChallengeId).Execute()

Get trading challenge daily snapshots



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTradingChallengeDailySnapshots(context.Background(), tradingChallengeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTradingChallengeDailySnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTradingChallengeDailySnapshots`: TradingChallengeDailySnapshotsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTradingChallengeDailySnapshots`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTradingChallengeDailySnapshotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TradingChallengeDailySnapshotsResponseEnvelope**](TradingChallengeDailySnapshotsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTradingChallengeResults

> TradingChallengeResultsResponseEnvelope GetTradingChallengeResults(ctx, tradingChallengeId).Board(board).Execute()

Get trading challenge results



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	board := "board_example" // string | Leaderboard board selector. Defaults to TOP_PNL. (optional) (default to "TOP_PNL")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTradingChallengeResults(context.Background(), tradingChallengeId).Board(board).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTradingChallengeResults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTradingChallengeResults`: TradingChallengeResultsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTradingChallengeResults`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTradingChallengeResultsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **board** | **string** | Leaderboard board selector. Defaults to TOP_PNL. | [default to &quot;TOP_PNL&quot;]

### Return type

[**TradingChallengeResultsResponseEnvelope**](TradingChallengeResultsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTransactionById

> TransactionResponseEnvelope GetTransactionById(ctx, transactionId).Execute()

Get a transaction by ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	transactionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTransactionById(context.Background(), transactionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTransactionById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTransactionById`: TransactionResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTransactionById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**transactionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTransactionByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TransactionResponseEnvelope**](TransactionResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTransactions

> ListTransactionsResponseEnvelope GetTransactions(ctx).Pools(pools).UserIds(userIds).TxKinds(txKinds).Start(start).End(end).TenantId(tenantId).Page(page).Limit(limit).Execute()

Get a filtered, paginated list of transactions

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	pools := []string{"Inner_example"} // []string |  (optional)
	userIds := []string{"Inner_example"} // []string |  (optional)
	txKinds := []openapiclient.TransactionKind{openapiclient.TransactionKind("ACCRUE_INTEREST")} // []TransactionKind |  (optional)
	start := time.Now() // time.Time |  (optional)
	end := time.Now() // time.Time |  (optional)
	tenantId := "tenantId_example" // string |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTransactions(context.Background()).Pools(pools).UserIds(userIds).TxKinds(txKinds).Start(start).End(end).TenantId(tenantId).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTransactions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTransactions`: ListTransactionsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTransactions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTransactionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pools** | **[]string** |  | 
 **userIds** | **[]string** |  | 
 **txKinds** | [**[]TransactionKind**](TransactionKind.md) |  | 
 **start** | **time.Time** |  | 
 **end** | **time.Time** |  | 
 **tenantId** | **string** |  | 
 **page** | **int32** |  | [default to 1]
 **limit** | **int32** |  | [default to 100]

### Return type

[**ListTransactionsResponseEnvelope**](ListTransactionsResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTransactionsSettlements

> TransactionsSettlementsResponseEnvelope GetTransactionsSettlements(ctx).TenantId(tenantId).UserId(userId).PositionId(positionId).TxKind(txKind).CreatedAfter(createdAfter).CreatedBefore(createdBefore).SettledAfter(settledAfter).SettledBefore(settledBefore).IsSettled(isSettled).Execute()

Get transactions settlements with filters

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tenantId := "tenantId_example" // string | Tenant ID to filter settlements (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | User ID to filter settlements (optional)
	positionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Position ID to filter settlements (optional)
	txKind := "txKind_example" // string | Transaction kind to filter settlements (optional)
	createdAfter := time.Now() // time.Time | Filter settlements created after this time (optional)
	createdBefore := time.Now() // time.Time | Filter settlements created before this time (optional)
	settledAfter := time.Now() // time.Time | Filter settlements settled after this time (optional)
	settledBefore := time.Now() // time.Time | Filter settlements settled before this time (optional)
	isSettled := true // bool | Filter settlements by settlement status (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTransactionsSettlements(context.Background()).TenantId(tenantId).UserId(userId).PositionId(positionId).TxKind(txKind).CreatedAfter(createdAfter).CreatedBefore(createdBefore).SettledAfter(settledAfter).SettledBefore(settledBefore).IsSettled(isSettled).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTransactionsSettlements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTransactionsSettlements`: TransactionsSettlementsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTransactionsSettlements`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTransactionsSettlementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tenantId** | **string** | Tenant ID to filter settlements | 
 **userId** | **string** | User ID to filter settlements | 
 **positionId** | **string** | Position ID to filter settlements | 
 **txKind** | **string** | Transaction kind to filter settlements | 
 **createdAfter** | **time.Time** | Filter settlements created after this time | 
 **createdBefore** | **time.Time** | Filter settlements created before this time | 
 **settledAfter** | **time.Time** | Filter settlements settled after this time | 
 **settledBefore** | **time.Time** | Filter settlements settled before this time | 
 **isSettled** | **bool** | Filter settlements by settlement status | 

### Return type

[**TransactionsSettlementsResponseEnvelope**](TransactionsSettlementsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTransactionsStream

> []StreamTransactionsEntry GetTransactionsStream(ctx).Since(since).Execute()

Get transactions since a specific time, and open a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	since := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTransactionsStream(context.Background()).Since(since).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetTransactionsStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTransactionsStream`: []StreamTransactionsEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetTransactionsStream`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTransactionsStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **since** | **time.Time** |  | 

### Return type

[**[]StreamTransactionsEntry**](StreamTransactionsEntry.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserById

> UserEnvelope GetUserById(ctx, userId).Execute()

Get user by ID (admin only)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserById(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserById`: UserEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserEnvelope**](UserEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserCouponPaymentsStream

> StreamUserCouponPaymentsResponse GetUserCouponPaymentsStream(ctx, userId).Execute()

Stream user's coupon payment accruals in real time

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserCouponPaymentsStream(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserCouponPaymentsStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserCouponPaymentsStream`: StreamUserCouponPaymentsResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserCouponPaymentsStream`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserCouponPaymentsStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StreamUserCouponPaymentsResponse**](StreamUserCouponPaymentsResponse.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserDeactivation

> UserDeactivationResponseEnvelope GetUserDeactivation(ctx, userId).Execute()

Get the latest account deactivation request for a user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserDeactivation(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserDeactivation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserDeactivation`: UserDeactivationResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserDeactivation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserDeactivationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserDeactivationResponseEnvelope**](UserDeactivationResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserLedgerStream

> []StreamPositionsEntry GetUserLedgerStream(ctx, userId).Execute()

Get a snapshot of user's ledger updates since a specific time, and opens a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserLedgerStream(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserLedgerStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserLedgerStream`: []StreamPositionsEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserLedgerStream`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserLedgerStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]StreamPositionsEntry**](StreamPositionsEntry.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserLeverageAccruedInterestStream

> StreamCurrentLeverageAccruedInterestResponse GetUserLeverageAccruedInterestStream(ctx, userId).Execute()

Stream user's current leverage accrued interest in real time

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserLeverageAccruedInterestStream(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserLeverageAccruedInterestStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserLeverageAccruedInterestStream`: StreamCurrentLeverageAccruedInterestResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserLeverageAccruedInterestStream`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserLeverageAccruedInterestStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StreamCurrentLeverageAccruedInterestResponse**](StreamCurrentLeverageAccruedInterestResponse.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserOrderUpdatesStream

> []StreamOrderUpdatesEntry GetUserOrderUpdatesStream(ctx, userId, orderBookId).Since(since).Execute()

Get a snapshot of user's order updates for the given order book since a specific time, and opens a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	since := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserOrderUpdatesStream(context.Background(), userId, orderBookId).Since(since).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserOrderUpdatesStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserOrderUpdatesStream`: []StreamOrderUpdatesEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserOrderUpdatesStream`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserOrderUpdatesStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **since** | **time.Time** |  | 

### Return type

[**[]StreamOrderUpdatesEntry**](StreamOrderUpdatesEntry.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserOrdersUpdatesStreamAll

> []StreamOrderUpdatesEntry GetUserOrdersUpdatesStreamAll(ctx, userId).Since(since).Execute()

Get a snapshot of user's order updates across all order books since a specific time, and opens a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	since := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserOrdersUpdatesStreamAll(context.Background(), userId).Since(since).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserOrdersUpdatesStreamAll``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserOrdersUpdatesStreamAll`: []StreamOrderUpdatesEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserOrdersUpdatesStreamAll`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserOrdersUpdatesStreamAllRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **time.Time** |  | 

### Return type

[**[]StreamOrderUpdatesEntry**](StreamOrderUpdatesEntry.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserSelf

> UserEnvelope GetUserSelf(ctx).Execute()

Get user details for the authenticated user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserSelf(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserSelf`: UserEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserSelf`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserSelfRequest struct via the builder pattern


### Return type

[**UserEnvelope**](UserEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserTransactionsStream

> []StreamTransactionsEntry GetUserTransactionsStream(ctx, userId).Since(since).Execute()

Get a snapshot of user's executed transactions since a specific time, and opens a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	since := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUserTransactionsStream(context.Background(), userId).Since(since).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUserTransactionsStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserTransactionsStream`: []StreamTransactionsEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUserTransactionsStream`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserTransactionsStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **time.Time** |  | 

### Return type

[**[]StreamTransactionsEntry**](StreamTransactionsEntry.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUsers

> ListUsersResponseEnvelope GetUsers(ctx).Id(id).Limit(limit).Offset(offset).Email(email).FirstName(firstName).LastName(lastName).CountryOfDomicile(countryOfDomicile).Execute()

Get all users (admin only)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 100)
	offset := int32(56) // int32 |  (optional) (default to 0)
	email := "email_example" // string |  (optional)
	firstName := "firstName_example" // string |  (optional)
	lastName := "lastName_example" // string |  (optional)
	countryOfDomicile := openapiclient.CountryCode("AF") // CountryCode |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUsers(context.Background()).Id(id).Limit(limit).Offset(offset).Email(email).FirstName(firstName).LastName(lastName).CountryOfDomicile(countryOfDomicile).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsers`: ListUsersResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUsers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** |  | 
 **limit** | **int32** |  | [default to 100]
 **offset** | **int32** |  | [default to 0]
 **email** | **string** |  | 
 **firstName** | **string** |  | 
 **lastName** | **string** |  | 
 **countryOfDomicile** | [**CountryCode**](CountryCode.md) |  | 

### Return type

[**ListUsersResponseEnvelope**](ListUsersResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUsersAPIKeys

> APIKeyResponseEnvelope GetUsersAPIKeys(ctx).Execute()

Get user's api keys

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetUsersAPIKeys(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetUsersAPIKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsersAPIKeys`: APIKeyResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetUsersAPIKeys`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUsersAPIKeysRequest struct via the builder pattern


### Return type

[**APIKeyResponseEnvelope**](APIKeyResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWithdrawal

> WithdrawalResponseEnvelope GetWithdrawal(ctx, withdrawalId).Execute()

Get a USDC withdrawal by ID



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	withdrawalId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The withdrawal ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetWithdrawal(context.Background(), withdrawalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetWithdrawal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWithdrawal`: WithdrawalResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetWithdrawal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**withdrawalId** | **string** | The withdrawal ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetWithdrawalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**WithdrawalResponseEnvelope**](WithdrawalResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWithdrawalFeeQuote

> FeeQuoteResponseEnvelope GetWithdrawalFeeQuote(ctx).To(to).Quantity(quantity).Execute()

Estimate the network fee to withdraw USDC via web3



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	to := "to_example" // string | The destination wallet address as a 0x-prefixed 20-byte hex string. Must not be the zero address.
	quantity := "quantity_example" // string | Human-decimal USDC quantity to withdraw, e.g. '100.50'. Must be positive.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetWithdrawalFeeQuote(context.Background()).To(to).Quantity(quantity).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetWithdrawalFeeQuote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWithdrawalFeeQuote`: FeeQuoteResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetWithdrawalFeeQuote`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetWithdrawalFeeQuoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **to** | **string** | The destination wallet address as a 0x-prefixed 20-byte hex string. Must not be the zero address. | 
 **quantity** | **string** | Human-decimal USDC quantity to withdraw, e.g. &#39;100.50&#39;. Must be positive. | 

### Return type

[**FeeQuoteResponseEnvelope**](FeeQuoteResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IssuePromoLinkBatch

> IssuePromoLinkBatchResponse IssuePromoLinkBatch(ctx, tradingChallengeId).IdempotencyKey(idempotencyKey).IssuePromoLinkBatchRequest(issuePromoLinkBatchRequest).Execute()

Issue a promotional link batch



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	idempotencyKey := "idempotencyKey_example" // string | 
	issuePromoLinkBatchRequest := *openapiclient.NewIssuePromoLinkBatchRequest(openapiclient.PromoSourceType("KOL"), "SourceId_example", int32(123)) // IssuePromoLinkBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.IssuePromoLinkBatch(context.Background(), tradingChallengeId).IdempotencyKey(idempotencyKey).IssuePromoLinkBatchRequest(issuePromoLinkBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.IssuePromoLinkBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IssuePromoLinkBatch`: IssuePromoLinkBatchResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.IssuePromoLinkBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiIssuePromoLinkBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** |  | 
 **issuePromoLinkBatchRequest** | [**IssuePromoLinkBatchRequest**](IssuePromoLinkBatchRequest.md) |  | 

### Return type

[**IssuePromoLinkBatchResponse**](IssuePromoLinkBatchResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LedgerDeposit

> FundUserResponseEnvelope LedgerDeposit(ctx, userId).FundUserRequest(fundUserRequest).Execute()

Deposit assets into this user's account from the outside world



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	fundUserRequest := *openapiclient.NewFundUserRequest("AssetId_example", "Quantity_example") // FundUserRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LedgerDeposit(context.Background(), userId).FundUserRequest(fundUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LedgerDeposit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LedgerDeposit`: FundUserResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LedgerDeposit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLedgerDepositRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **fundUserRequest** | [**FundUserRequest**](FundUserRequest.md) |  | 

### Return type

[**FundUserResponseEnvelope**](FundUserResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LedgerWithdraw

> FundUserResponseEnvelope LedgerWithdraw(ctx, userId).DefundUserRequest(defundUserRequest).Status(status).Execute()

Withdraw assets from this user to the outside world



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	defundUserRequest := *openapiclient.NewDefundUserRequest("AssetId_example", "Quantity_example") // DefundUserRequest | 
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LedgerWithdraw(context.Background(), userId).DefundUserRequest(defundUserRequest).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LedgerWithdraw``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LedgerWithdraw`: FundUserResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LedgerWithdraw`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLedgerWithdrawRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defundUserRequest** | [**DefundUserRequest**](DefundUserRequest.md) |  | 
 **status** | **string** |  | 

### Return type

[**FundUserResponseEnvelope**](FundUserResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LedgerWithdrawRequest

> WithdrawalInitiationResponseEnvelope LedgerWithdrawRequest(ctx, userId).DefundUserRequest(defundUserRequest).Execute()

Initiate a withdrawal request for this user to the outside world



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	defundUserRequest := *openapiclient.NewDefundUserRequest("AssetId_example", "Quantity_example") // DefundUserRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LedgerWithdrawRequest(context.Background(), userId).DefundUserRequest(defundUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LedgerWithdrawRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LedgerWithdrawRequest`: WithdrawalInitiationResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LedgerWithdrawRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLedgerWithdrawRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defundUserRequest** | [**DefundUserRequest**](DefundUserRequest.md) |  | 

### Return type

[**WithdrawalInitiationResponseEnvelope**](WithdrawalInitiationResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LedgerWithdrawRequestSelf

> WithdrawalInitiationResponseEnvelope LedgerWithdrawRequestSelf(ctx, userId).DefundUserRequest(defundUserRequest).Execute()

Initiate a withdrawal request for the logged in user to the outside world



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	defundUserRequest := *openapiclient.NewDefundUserRequest("AssetId_example", "Quantity_example") // DefundUserRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LedgerWithdrawRequestSelf(context.Background(), userId).DefundUserRequest(defundUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LedgerWithdrawRequestSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LedgerWithdrawRequestSelf`: WithdrawalInitiationResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LedgerWithdrawRequestSelf`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLedgerWithdrawRequestSelfRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defundUserRequest** | [**DefundUserRequest**](DefundUserRequest.md) |  | 

### Return type

[**WithdrawalInitiationResponseEnvelope**](WithdrawalInitiationResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeverageGetAccruedInterestByUser

> CurrentLeverageAccruedInterestResponseEnvelope LeverageGetAccruedInterestByUser(ctx).PositionId(positionId).AssetId(assetId).Execute()

Get current accrued leverage interest for the user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	positionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LeverageGetAccruedInterestByUser(context.Background()).PositionId(positionId).AssetId(assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LeverageGetAccruedInterestByUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LeverageGetAccruedInterestByUser`: CurrentLeverageAccruedInterestResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LeverageGetAccruedInterestByUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLeverageGetAccruedInterestByUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **positionId** | **string** |  | 
 **assetId** | **string** |  | 

### Return type

[**CurrentLeverageAccruedInterestResponseEnvelope**](CurrentLeverageAccruedInterestResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeverageGetHistoricalInterestRates

> HistoricalLeverageInterestRatesResponseEnvelope LeverageGetHistoricalInterestRates(ctx, assetId).Start(start).End(end).Execute()

Get historical leverage borrowing and lending yields for a specific asset

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	start := time.Now() // time.Time |  (optional)
	end := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LeverageGetHistoricalInterestRates(context.Background(), assetId).Start(start).End(end).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LeverageGetHistoricalInterestRates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LeverageGetHistoricalInterestRates`: HistoricalLeverageInterestRatesResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LeverageGetHistoricalInterestRates`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLeverageGetHistoricalInterestRatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **start** | **time.Time** |  | 
 **end** | **time.Time** |  | 

### Return type

[**HistoricalLeverageInterestRatesResponseEnvelope**](HistoricalLeverageInterestRatesResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeverageGetInterestRate

> LeverageInterestRateResponseEnvelope LeverageGetInterestRate(ctx, assetId).Start(start).End(end).Execute()

Get leverage borrowing and lending yields for a specific asset

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	start := time.Now() // time.Time |  (optional)
	end := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LeverageGetInterestRate(context.Background(), assetId).Start(start).End(end).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LeverageGetInterestRate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LeverageGetInterestRate`: LeverageInterestRateResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LeverageGetInterestRate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLeverageGetInterestRateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **start** | **time.Time** |  | 
 **end** | **time.Time** |  | 

### Return type

[**LeverageInterestRateResponseEnvelope**](LeverageInterestRateResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeverageIsolateCollateral

> IsolateCollateralResponse LeverageIsolateCollateral(ctx).IsolateCollateralRequest(isolateCollateralRequest).Execute()

Create an isolated position by transferring collateral to the position from the user's global collateral

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	isolateCollateralRequest := *openapiclient.NewIsolateCollateralRequest("GlobalPositionId_example", "AssetId_example", "Quantity_example") // IsolateCollateralRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LeverageIsolateCollateral(context.Background()).IsolateCollateralRequest(isolateCollateralRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LeverageIsolateCollateral``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LeverageIsolateCollateral`: IsolateCollateralResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LeverageIsolateCollateral`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLeverageIsolateCollateralRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **isolateCollateralRequest** | [**IsolateCollateralRequest**](IsolateCollateralRequest.md) |  | 

### Return type

[**IsolateCollateralResponse**](IsolateCollateralResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeverageSupply

> SupplyResponseEnvelope LeverageSupply(ctx).SupplyRequest(supplyRequest).Execute()

Supply leverage for a specific asset

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	supplyRequest := *openapiclient.NewSupplyRequest("PositionId_example", "AssetId_example", "Quantity_example") // SupplyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LeverageSupply(context.Background()).SupplyRequest(supplyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LeverageSupply``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LeverageSupply`: SupplyResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LeverageSupply`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLeverageSupplyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **supplyRequest** | [**SupplyRequest**](SupplyRequest.md) |  | 

### Return type

[**SupplyResponseEnvelope**](SupplyResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeverageUnite

> UnitePositionResponseEnvelope LeverageUnite(ctx).UnitePositionRequest(unitePositionRequest).Execute()

Combines all isolated positions into a single global position



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	unitePositionRequest := *openapiclient.NewUnitePositionRequest("GlobalPositionId_example") // UnitePositionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LeverageUnite(context.Background()).UnitePositionRequest(unitePositionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LeverageUnite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LeverageUnite`: UnitePositionResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LeverageUnite`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLeverageUniteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **unitePositionRequest** | [**UnitePositionRequest**](UnitePositionRequest.md) |  | 

### Return type

[**UnitePositionResponseEnvelope**](UnitePositionResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeverageWithdraw

> WithdrawResponseEnvelope LeverageWithdraw(ctx).WithdrawRequest(withdrawRequest).Execute()

Withdraw leverage for a specific asset

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	withdrawRequest := *openapiclient.NewWithdrawRequest("PositionId_example", "AssetId_example", "Quantity_example") // WithdrawRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LeverageWithdraw(context.Background()).WithdrawRequest(withdrawRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LeverageWithdraw``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LeverageWithdraw`: WithdrawResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LeverageWithdraw`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLeverageWithdrawRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **withdrawRequest** | [**WithdrawRequest**](WithdrawRequest.md) |  | 

### Return type

[**WithdrawResponseEnvelope**](WithdrawResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LiquidityAdd

> LiquidityResponseEnvelope LiquidityAdd(ctx, poolId).LiquidityRequest(liquidityRequest).Execute()

Add liquidity to a pool

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	poolId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	liquidityRequest := *openapiclient.NewLiquidityRequest("PositionId_example", "Quantity_example") // LiquidityRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LiquidityAdd(context.Background(), poolId).LiquidityRequest(liquidityRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LiquidityAdd``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LiquidityAdd`: LiquidityResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LiquidityAdd`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLiquidityAddRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **liquidityRequest** | [**LiquidityRequest**](LiquidityRequest.md) |  | 

### Return type

[**LiquidityResponseEnvelope**](LiquidityResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LiquiditySubtract

> LiquidityResponseEnvelope LiquiditySubtract(ctx, poolId).LiquidityRequest(liquidityRequest).Execute()

Subtract liquidity from a pool

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	poolId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	liquidityRequest := *openapiclient.NewLiquidityRequest("PositionId_example", "Quantity_example") // LiquidityRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LiquiditySubtract(context.Background(), poolId).LiquidityRequest(liquidityRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LiquiditySubtract``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LiquiditySubtract`: LiquidityResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LiquiditySubtract`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLiquiditySubtractRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **liquidityRequest** | [**LiquidityRequest**](LiquidityRequest.md) |  | 

### Return type

[**LiquidityResponseEnvelope**](LiquidityResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAccountsSelfV2

> ListAccountsResponseV2Envelope ListAccountsSelfV2(ctx).Execute()

List all accounts for the authenticated user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListAccountsSelfV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListAccountsSelfV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAccountsSelfV2`: ListAccountsResponseV2Envelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListAccountsSelfV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListAccountsSelfV2Request struct via the builder pattern


### Return type

[**ListAccountsResponseV2Envelope**](ListAccountsResponseV2Envelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAffiliateCashFlows

> AffiliateCashFlowReportEnvelope ListAffiliateCashFlows(ctx, programId, userId).Limit(limit).Page(page).Execute()

List a referred user's customer cash flows



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	programId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	limit := int32(56) // int32 |  (optional) (default to 100)
	page := int32(56) // int32 | One-based page; the resulting offset must not exceed 2147483647. Results sort by created_at then id descending. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListAffiliateCashFlows(context.Background(), programId, userId).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListAffiliateCashFlows``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAffiliateCashFlows`: AffiliateCashFlowReportEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListAffiliateCashFlows`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**programId** | **string** |  | 
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAffiliateCashFlowsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **limit** | **int32** |  | [default to 100]
 **page** | **int32** | One-based page; the resulting offset must not exceed 2147483647. Results sort by created_at then id descending. | [default to 1]

### Return type

[**AffiliateCashFlowReportEnvelope**](AffiliateCashFlowReportEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAffiliatePrograms

> AffiliateProgramListEnvelope ListAffiliatePrograms(ctx).TenantId(tenantId).Limit(limit).Page(page).Execute()

List affiliate programs



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tenantId := "tenantId_example" // string | Integrators default to their own tenant and cannot select another. Admins may select any tenant. (optional)
	limit := int32(56) // int32 |  (optional) (default to 100)
	page := int32(56) // int32 | One-based page; the resulting offset must not exceed 2147483647. Results sort by created_at then id descending. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListAffiliatePrograms(context.Background()).TenantId(tenantId).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListAffiliatePrograms``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAffiliatePrograms`: AffiliateProgramListEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListAffiliatePrograms`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAffiliateProgramsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tenantId** | **string** | Integrators default to their own tenant and cannot select another. Admins may select any tenant. | 
 **limit** | **int32** |  | [default to 100]
 **page** | **int32** | One-based page; the resulting offset must not exceed 2147483647. Results sort by created_at then id descending. | [default to 1]

### Return type

[**AffiliateProgramListEnvelope**](AffiliateProgramListEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAffiliateReferrals

> AffiliateReferralReportEnvelope ListAffiliateReferrals(ctx, programId).Date(date).ReferrerId(referrerId).Limit(limit).Page(page).Execute()

List referred users and activity



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	programId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	date := time.Now() // string |  (optional)
	referrerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 100)
	page := int32(56) // int32 | One-based page; the resulting offset must not exceed 2147483647. Results sort by attribution created_at then user_id descending. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListAffiliateReferrals(context.Background(), programId).Date(date).ReferrerId(referrerId).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListAffiliateReferrals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAffiliateReferrals`: AffiliateReferralReportEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListAffiliateReferrals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**programId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAffiliateReferralsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **date** | **string** |  | 
 **referrerId** | **string** |  | 
 **limit** | **int32** |  | [default to 100]
 **page** | **int32** | One-based page; the resulting offset must not exceed 2147483647. Results sort by attribution created_at then user_id descending. | [default to 1]

### Return type

[**AffiliateReferralReportEnvelope**](AffiliateReferralReportEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAffiliateReferrers

> AffiliateReferrerListEnvelope ListAffiliateReferrers(ctx, programId).Limit(limit).Page(page).Execute()

List program referrers



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	programId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	limit := int32(56) // int32 |  (optional) (default to 100)
	page := int32(56) // int32 | One-based page; the resulting offset must not exceed 2147483647. Results sort by created_at then id descending. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListAffiliateReferrers(context.Background(), programId).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListAffiliateReferrers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAffiliateReferrers`: AffiliateReferrerListEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListAffiliateReferrers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**programId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAffiliateReferrersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** |  | [default to 100]
 **page** | **int32** | One-based page; the resulting offset must not exceed 2147483647. Results sort by created_at then id descending. | [default to 1]

### Return type

[**AffiliateReferrerListEnvelope**](AffiliateReferrerListEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAssets

> ResponseEnvelopeOfListAssets ListAssets(ctx).CreatedAfter(createdAfter).CreatedBefore(createdBefore).AssetKind(assetKind).CanAddLiquidity(canAddLiquidity).CanDirectBorrow(canDirectBorrow).CanOnboard(canOnboard).CanTrade(canTrade).CanVirtualBorrow(canVirtualBorrow).Page(page).Limit(limit).Execute()

List assets

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	createdAfter := time.Now() // time.Time |  (optional)
	createdBefore := time.Now() // time.Time |  (optional)
	assetKind := openapiclient.AssetKind("BOND") // AssetKind | Asset kind (BOND, CURRENCY, INTEREST, POOL_SHARE) (optional)
	canAddLiquidity := true // bool |  (optional)
	canDirectBorrow := true // bool |  (optional)
	canOnboard := true // bool |  (optional)
	canTrade := true // bool |  (optional)
	canVirtualBorrow := true // bool |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListAssets(context.Background()).CreatedAfter(createdAfter).CreatedBefore(createdBefore).AssetKind(assetKind).CanAddLiquidity(canAddLiquidity).CanDirectBorrow(canDirectBorrow).CanOnboard(canOnboard).CanTrade(canTrade).CanVirtualBorrow(canVirtualBorrow).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAssets`: ResponseEnvelopeOfListAssets
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createdAfter** | **time.Time** |  | 
 **createdBefore** | **time.Time** |  | 
 **assetKind** | [**AssetKind**](AssetKind.md) | Asset kind (BOND, CURRENCY, INTEREST, POOL_SHARE) | 
 **canAddLiquidity** | **bool** |  | 
 **canDirectBorrow** | **bool** |  | 
 **canOnboard** | **bool** |  | 
 **canTrade** | **bool** |  | 
 **canVirtualBorrow** | **bool** |  | 
 **page** | **int32** |  | [default to 1]
 **limit** | **int32** |  | [default to 100]

### Return type

[**ResponseEnvelopeOfListAssets**](ResponseEnvelopeOfListAssets.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeposits

> ListDepositsResponseEnvelope ListDeposits(ctx).UserId(userId).Page(page).Limit(limit).Execute()

List USDC deposits



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter by user ID. Non-admin callers may only specify their own user ID. (optional)
	page := int64(789) // int64 |  (optional) (default to 1)
	limit := int64(789) // int64 |  (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListDeposits(context.Background()).UserId(userId).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListDeposits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeposits`: ListDepositsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListDeposits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDepositsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **string** | Filter by user ID. Non-admin callers may only specify their own user ID. | 
 **page** | **int64** |  | [default to 1]
 **limit** | **int64** |  | [default to 50]

### Return type

[**ListDepositsResponseEnvelope**](ListDepositsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOrderBooks

> ListOrderbookResponseEnvelope ListOrderBooks(ctx).Status(status).BaseAssetId(baseAssetId).QuoteAssetId(quoteAssetId).Page(page).Limit(limit).Execute()

List order books

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	status := []openapiclient.OrderBookStatus{openapiclient.OrderBookStatus("CLOSED")} // []OrderBookStatus |  (optional)
	baseAssetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	quoteAssetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListOrderBooks(context.Background()).Status(status).BaseAssetId(baseAssetId).QuoteAssetId(quoteAssetId).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListOrderBooks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOrderBooks`: ListOrderbookResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListOrderBooks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOrderBooksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | [**[]OrderBookStatus**](OrderBookStatus.md) |  | 
 **baseAssetId** | **string** |  | 
 **quoteAssetId** | **string** |  | 
 **page** | **int32** |  | [default to 1]
 **limit** | **int32** |  | [default to 100]

### Return type

[**ListOrderbookResponseEnvelope**](ListOrderbookResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOrders

> ListOrdersResponseEnvelope ListOrders(ctx).UserId(userId).OrderBookId(orderBookId).Kind(kind).Status(status).Side(side).From(from).To(to).Page(page).Limit(limit).ClientOrderId(clientOrderId).Execute()

List all orders

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter by user ID (only allowed if the user has copy trading enabled, or if the requester is an Admin or Integrator within the same tenant) (optional)
	orderBookId := []string{"Inner_example"} // []string |  (optional)
	kind := []openapiclient.OrderKind{openapiclient.OrderKind("LIMIT")} // []OrderKind |  (optional)
	status := []openapiclient.OrderStatus{openapiclient.OrderStatus("OPEN")} // []OrderStatus |  (optional)
	side := openapiclient.Side("BUY") // Side |  (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 100)
	clientOrderId := "clientOrderId_example" // string | Filter by client order ID prefix (max 256 characters) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListOrders(context.Background()).UserId(userId).OrderBookId(orderBookId).Kind(kind).Status(status).Side(side).From(from).To(to).Page(page).Limit(limit).ClientOrderId(clientOrderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOrders`: ListOrdersResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **string** | Filter by user ID (only allowed if the user has copy trading enabled, or if the requester is an Admin or Integrator within the same tenant) | 
 **orderBookId** | **[]string** |  | 
 **kind** | [**[]OrderKind**](OrderKind.md) |  | 
 **status** | [**[]OrderStatus**](OrderStatus.md) |  | 
 **side** | [**Side**](Side.md) |  | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** |  | 
 **page** | **int32** |  | [default to 1]
 **limit** | **int32** |  | [default to 100]
 **clientOrderId** | **string** | Filter by client order ID prefix (max 256 characters) | 

### Return type

[**ListOrdersResponseEnvelope**](ListOrdersResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOwnAffiliateMemberships

> AffiliateMembershipListEnvelope ListOwnAffiliateMemberships(ctx).Limit(limit).Page(page).Execute()

List your affiliate memberships



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	limit := int32(56) // int32 |  (optional) (default to 100)
	page := int32(56) // int32 | One-based page; the resulting offset must not exceed 2147483647. Results sort by created_at then id descending. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListOwnAffiliateMemberships(context.Background()).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListOwnAffiliateMemberships``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOwnAffiliateMemberships`: AffiliateMembershipListEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListOwnAffiliateMemberships`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOwnAffiliateMembershipsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 100]
 **page** | **int32** | One-based page; the resulting offset must not exceed 2147483647. Results sort by created_at then id descending. | [default to 1]

### Return type

[**AffiliateMembershipListEnvelope**](AffiliateMembershipListEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPositionAccountsSelf

> ListPositionAccountsResponseEnvelope ListPositionAccountsSelf(ctx).Execute()

List all position accounts for the authenticated user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListPositionAccountsSelf(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListPositionAccountsSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPositionAccountsSelf`: ListPositionAccountsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListPositionAccountsSelf`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPositionAccountsSelfRequest struct via the builder pattern


### Return type

[**ListPositionAccountsResponseEnvelope**](ListPositionAccountsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPromoLinkBatches

> PromoLinkBatchListResponse ListPromoLinkBatches(ctx, tradingChallengeId).Execute()

List promotional link batches



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListPromoLinkBatches(context.Background(), tradingChallengeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListPromoLinkBatches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPromoLinkBatches`: PromoLinkBatchListResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListPromoLinkBatches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPromoLinkBatchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PromoLinkBatchListResponse**](PromoLinkBatchListResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPromoLinks

> PromoLinkListResponse ListPromoLinks(ctx, batchId).Limit(limit).Cursor(cursor).Status(status).Reveal(reveal).Execute()

List promotional links



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	batchId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	limit := int32(56) // int32 |  (optional) (default to 100)
	cursor := "cursor_example" // string |  (optional)
	status := openapiclient.PromoLinkStatus("ISSUED") // PromoLinkStatus |  (optional)
	reveal := true // bool |  (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListPromoLinks(context.Background(), batchId).Limit(limit).Cursor(cursor).Status(status).Reveal(reveal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListPromoLinks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPromoLinks`: PromoLinkListResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListPromoLinks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**batchId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPromoLinksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** |  | [default to 100]
 **cursor** | **string** |  | 
 **status** | [**PromoLinkStatus**](PromoLinkStatus.md) |  | 
 **reveal** | **bool** |  | [default to false]

### Return type

[**PromoLinkListResponse**](PromoLinkListResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTradingChallengeRegistrationRequests

> TradingChallengeRegistrationRequestListResponseEnvelope ListTradingChallengeRegistrationRequests(ctx).TradingChallengeId(tradingChallengeId).UserId(userId).Status(status).TenantId(tenantId).Limit(limit).Offset(offset).Execute()

List trading challenge registration requests



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Only requests for this challenge. (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Only requests from this user. (optional)
	status := "status_example" // string | Only requests in this state. (optional)
	tenantId := "tenantId_example" // string | Admins only; an integrator may only name their own tenant. (optional)
	limit := int32(56) // int32 | Page size, capped at 1000. (optional) (default to 100)
	offset := int32(56) // int32 | Rows to skip. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListTradingChallengeRegistrationRequests(context.Background()).TradingChallengeId(tradingChallengeId).UserId(userId).Status(status).TenantId(tenantId).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListTradingChallengeRegistrationRequests``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTradingChallengeRegistrationRequests`: TradingChallengeRegistrationRequestListResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListTradingChallengeRegistrationRequests`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTradingChallengeRegistrationRequestsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tradingChallengeId** | **string** | Only requests for this challenge. | 
 **userId** | **string** | Only requests from this user. | 
 **status** | **string** | Only requests in this state. | 
 **tenantId** | **string** | Admins only; an integrator may only name their own tenant. | 
 **limit** | **int32** | Page size, capped at 1000. | [default to 100]
 **offset** | **int32** | Rows to skip. | [default to 0]

### Return type

[**TradingChallengeRegistrationRequestListResponseEnvelope**](TradingChallengeRegistrationRequestListResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTradingChallenges

> TradingChallengeListResponseEnvelope ListTradingChallenges(ctx).TenantId(tenantId).Type_(type_).Status(status).Start(start).End(end).Execute()

List trading challenges



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tenantId := "tenantId_example" // string |  (optional)
	type_ := openapiclient.TradingChallengeType("TOURNAMENT") // TradingChallengeType |  (optional)
	status := openapiclient.TradingChallengeStatus("PENDING") // TradingChallengeStatus |  (optional)
	start := time.Now() // time.Time |  (optional)
	end := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListTradingChallenges(context.Background()).TenantId(tenantId).Type_(type_).Status(status).Start(start).End(end).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListTradingChallenges``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTradingChallenges`: TradingChallengeListResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListTradingChallenges`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTradingChallengesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tenantId** | **string** |  | 
 **type_** | [**TradingChallengeType**](TradingChallengeType.md) |  | 
 **status** | [**TradingChallengeStatus**](TradingChallengeStatus.md) |  | 
 **start** | **time.Time** |  | 
 **end** | **time.Time** |  | 

### Return type

[**TradingChallengeListResponseEnvelope**](TradingChallengeListResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListUserDeactivations

> UserDeactivationListResponseEnvelope ListUserDeactivations(ctx).Status(status).TenantId(tenantId).TradingChallengeId(tradingChallengeId).UserIds(userIds).Execute()

Get the current deactivation status across all users



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	status := "status_example" // string | Only return users whose latest request has this status. (optional)
	tenantId := "tenantId_example" // string | Only return users belonging to this tenant. At most one of tenant_id, trading_challenge_id and user_ids may be passed; combining them is rejected. An integrator whose tenant is not global may only pass their own tenant. (optional)
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Only return participants of this trading challenge. Mutually exclusive with tenant_id and user_ids. (optional)
	userIds := "userIds_example" // string | Comma-separated user IDs to return. Mutually exclusive with tenant_id and trading_challenge_id. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListUserDeactivations(context.Background()).Status(status).TenantId(tenantId).TradingChallengeId(tradingChallengeId).UserIds(userIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListUserDeactivations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListUserDeactivations`: UserDeactivationListResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListUserDeactivations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListUserDeactivationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** | Only return users whose latest request has this status. | 
 **tenantId** | **string** | Only return users belonging to this tenant. At most one of tenant_id, trading_challenge_id and user_ids may be passed; combining them is rejected. An integrator whose tenant is not global may only pass their own tenant. | 
 **tradingChallengeId** | **string** | Only return participants of this trading challenge. Mutually exclusive with tenant_id and user_ids. | 
 **userIds** | **string** | Comma-separated user IDs to return. Mutually exclusive with tenant_id and trading_challenge_id. | 

### Return type

[**UserDeactivationListResponseEnvelope**](UserDeactivationListResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWithdrawals

> ListWithdrawalsResponseEnvelope ListWithdrawals(ctx).UserId(userId).Status(status).Page(page).Limit(limit).Execute()

List USDC withdrawals



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter by user ID. Non-admin callers may only specify their own user ID. (optional)
	status := openapiclient.Web3WithdrawalStatus("PENDING") // Web3WithdrawalStatus | Filter by withdrawal status. (optional)
	page := int64(789) // int64 |  (optional) (default to 1)
	limit := int64(789) // int64 |  (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListWithdrawals(context.Background()).UserId(userId).Status(status).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListWithdrawals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWithdrawals`: ListWithdrawalsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListWithdrawals`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListWithdrawalsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **string** | Filter by user ID. Non-admin callers may only specify their own user ID. | 
 **status** | [**Web3WithdrawalStatus**](Web3WithdrawalStatus.md) | Filter by withdrawal status. | 
 **page** | **int64** |  | [default to 1]
 **limit** | **int64** |  | [default to 50]

### Return type

[**ListWithdrawalsResponseEnvelope**](ListWithdrawalsResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LookupAffiliateCode

> AffiliateReferrerEnvelope LookupAffiliateCode(ctx, code).TenantId(tenantId).Execute()

Look up a reusable referral code



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	code := "code_example" // string | 
	tenantId := "tenantId_example" // string | Integrators default to their own tenant and cannot select another. Admins may select any tenant. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.LookupAffiliateCode(context.Background(), code).TenantId(tenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.LookupAffiliateCode``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LookupAffiliateCode`: AffiliateReferrerEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.LookupAffiliateCode`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**code** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiLookupAffiliateCodeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **tenantId** | **string** | Integrators default to their own tenant and cannot select another. Admins may select any tenant. | 

### Return type

[**AffiliateReferrerEnvelope**](AffiliateReferrerEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayLeverageGetAccruedInterest

> PayLeverageAccruedInterestResponseEnvelope PayLeverageGetAccruedInterest(ctx).PayLeverageAccruedInterestRequest(payLeverageAccruedInterestRequest).Execute()

Pay current accrued leverage interest for a specific user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	payLeverageAccruedInterestRequest := *openapiclient.NewPayLeverageAccruedInterestRequest("AssetId_example", "PositionId_example") // PayLeverageAccruedInterestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.PayLeverageGetAccruedInterest(context.Background()).PayLeverageAccruedInterestRequest(payLeverageAccruedInterestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.PayLeverageGetAccruedInterest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayLeverageGetAccruedInterest`: PayLeverageAccruedInterestResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.PayLeverageGetAccruedInterest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPayLeverageGetAccruedInterestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **payLeverageAccruedInterestRequest** | [**PayLeverageAccruedInterestRequest**](PayLeverageAccruedInterestRequest.md) |  | 

### Return type

[**PayLeverageAccruedInterestResponseEnvelope**](PayLeverageAccruedInterestResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegisterAffiliateReferrer

> AffiliateReferrerEnvelope RegisterAffiliateReferrer(ctx, programId).RegisterAffiliateReferrerRequest(registerAffiliateReferrerRequest).Execute()

Register an existing user as a referrer



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	programId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	registerAffiliateReferrerRequest := *openapiclient.NewRegisterAffiliateReferrerRequest("UserId_example") // RegisterAffiliateReferrerRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RegisterAffiliateReferrer(context.Background(), programId).RegisterAffiliateReferrerRequest(registerAffiliateReferrerRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RegisterAffiliateReferrer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegisterAffiliateReferrer`: AffiliateReferrerEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RegisterAffiliateReferrer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**programId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegisterAffiliateReferrerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **registerAffiliateReferrerRequest** | [**RegisterAffiliateReferrerRequest**](RegisterAffiliateReferrerRequest.md) |  | 

### Return type

[**AffiliateReferrerEnvelope**](AffiliateReferrerEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RejectLedgerWithdrawRequest

> WithdrawalInitiationResponseEnvelope RejectLedgerWithdrawRequest(ctx, withdrawalId).WithdrawalRequestReason(withdrawalRequestReason).Execute()

Reject a pending withdrawal request



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	withdrawalId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	withdrawalRequestReason := *openapiclient.NewWithdrawalRequestReason("Reason_example") // WithdrawalRequestReason | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RejectLedgerWithdrawRequest(context.Background(), withdrawalId).WithdrawalRequestReason(withdrawalRequestReason).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RejectLedgerWithdrawRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RejectLedgerWithdrawRequest`: WithdrawalInitiationResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RejectLedgerWithdrawRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**withdrawalId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRejectLedgerWithdrawRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **withdrawalRequestReason** | [**WithdrawalRequestReason**](WithdrawalRequestReason.md) |  | 

### Return type

[**WithdrawalInitiationResponseEnvelope**](WithdrawalInitiationResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RejectTradingChallengeRegistrationRequest

> TradingChallengeRegistrationRequestResponseEnvelope RejectTradingChallengeRegistrationRequest(ctx, requestId).ReviewTradingChallengeRegistrationRequest(reviewTradingChallengeRegistrationRequest).Execute()

Reject a trading challenge registration request



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	requestId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	reviewTradingChallengeRegistrationRequest := *openapiclient.NewReviewTradingChallengeRegistrationRequest() // ReviewTradingChallengeRegistrationRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RejectTradingChallengeRegistrationRequest(context.Background(), requestId).ReviewTradingChallengeRegistrationRequest(reviewTradingChallengeRegistrationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RejectTradingChallengeRegistrationRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RejectTradingChallengeRegistrationRequest`: TradingChallengeRegistrationRequestResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RejectTradingChallengeRegistrationRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**requestId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRejectTradingChallengeRegistrationRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **reviewTradingChallengeRegistrationRequest** | [**ReviewTradingChallengeRegistrationRequest**](ReviewTradingChallengeRegistrationRequest.md) |  | 

### Return type

[**TradingChallengeRegistrationRequestResponseEnvelope**](TradingChallengeRegistrationRequestResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveTradingChallengeUsers

> TradingChallengeResponseEnvelope RemoveTradingChallengeUsers(ctx).RemoveTradingChallengeUsersRequest(removeTradingChallengeUsersRequest).Execute()

Remove users from a trading challenge



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	removeTradingChallengeUsersRequest := *openapiclient.NewRemoveTradingChallengeUsersRequest("TradingChallengeId_example") // RemoveTradingChallengeUsersRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RemoveTradingChallengeUsers(context.Background()).RemoveTradingChallengeUsersRequest(removeTradingChallengeUsersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RemoveTradingChallengeUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveTradingChallengeUsers`: TradingChallengeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RemoveTradingChallengeUsers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRemoveTradingChallengeUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **removeTradingChallengeUsersRequest** | [**RemoveTradingChallengeUsersRequest**](RemoveTradingChallengeUsersRequest.md) |  | 

### Return type

[**TradingChallengeResponseEnvelope**](TradingChallengeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RenderPromoLinkQR

> string RenderPromoLinkQR(ctx, linkId).Size(size).Format(format).Ec(ec).Execute()

Render a promotional link QR code



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	linkId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	size := int32(56) // int32 |  (optional) (default to 512)
	format := "format_example" // string |  (optional) (default to "png")
	ec := "ec_example" // string |  (optional) (default to "M")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RenderPromoLinkQR(context.Background(), linkId).Size(size).Format(format).Ec(ec).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RenderPromoLinkQR``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RenderPromoLinkQR`: string
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RenderPromoLinkQR`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**linkId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRenderPromoLinkQRRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **size** | **int32** |  | [default to 512]
 **format** | **string** |  | [default to &quot;png&quot;]
 **ec** | **string** |  | [default to &quot;M&quot;]

### Return type

**string**

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: image/png

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RepayUSD

> RepayUSDResponseEnvelope RepayUSD(ctx).RepayUSDRequest(repayUSDRequest).Execute()

Repay borrowed USD, then accrue and pay leverage interest

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	repayUSDRequest := *openapiclient.NewRepayUSDRequest("PositionId_example") // RepayUSDRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RepayUSD(context.Background()).RepayUSDRequest(repayUSDRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RepayUSD``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepayUSD`: RepayUSDResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RepayUSD`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRepayUSDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **repayUSDRequest** | [**RepayUSDRequest**](RepayUSDRequest.md) |  | 

### Return type

[**RepayUSDResponseEnvelope**](RepayUSDResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolvePromoClaim

> PromoClaimResponseEnvelope ResolvePromoClaim(ctx, token).Execute()

Resolve a public QR promotion claim link

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	token := "token_example" // string | Opaque bearer claim token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ResolvePromoClaim(context.Background(), token).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ResolvePromoClaim``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolvePromoClaim`: PromoClaimResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ResolvePromoClaim`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**token** | **string** | Opaque bearer claim token | 

### Other Parameters

Other parameters are passed through a pointer to a apiResolvePromoClaimRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PromoClaimResponseEnvelope**](PromoClaimResponseEnvelope.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeAPIKeyForUser

> RevokeAPIKeyResponseEnvelope RevokeAPIKeyForUser(ctx, keyId).Execute()

Revoke apikey for a user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	keyId := "keyId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RevokeAPIKeyForUser(context.Background(), keyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RevokeAPIKeyForUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeAPIKeyForUser`: RevokeAPIKeyResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RevokeAPIKeyForUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeAPIKeyForUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RevokeAPIKeyResponseEnvelope**](RevokeAPIKeyResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeAPIKeyForUserID

> RevokeAPIKeyResponseEnvelope RevokeAPIKeyForUserID(ctx, userId, keyId).Execute()

Revoke apikey for a user: admin or integrator only

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "userId_example" // string | 
	keyId := "keyId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RevokeAPIKeyForUserID(context.Background(), userId, keyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RevokeAPIKeyForUserID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeAPIKeyForUserID`: RevokeAPIKeyResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RevokeAPIKeyForUserID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 
**keyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeAPIKeyForUserIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**RevokeAPIKeyResponseEnvelope**](RevokeAPIKeyResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokePromoLink

> RevokePromoLinkResponse RevokePromoLink(ctx, linkId).RevokePromoLinkRequest(revokePromoLinkRequest).Execute()

Revoke a promotional link



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	linkId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	revokePromoLinkRequest := *openapiclient.NewRevokePromoLinkRequest("Reason_example") // RevokePromoLinkRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RevokePromoLink(context.Background(), linkId).RevokePromoLinkRequest(revokePromoLinkRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RevokePromoLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokePromoLink`: RevokePromoLinkResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RevokePromoLink`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**linkId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokePromoLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **revokePromoLinkRequest** | [**RevokePromoLinkRequest**](RevokePromoLinkRequest.md) |  | 

### Return type

[**RevokePromoLinkResponse**](RevokePromoLinkResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SettleLeverageAccruedInterest

> SettleLeverageAccruedInterestResponseEnvelope SettleLeverageAccruedInterest(ctx).SettleLeverageAccruedInterestRequest(settleLeverageAccruedInterestRequest).Execute()

Settle current accrued leverage interest for a specific user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	settleLeverageAccruedInterestRequest := *openapiclient.NewSettleLeverageAccruedInterestRequest() // SettleLeverageAccruedInterestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.SettleLeverageAccruedInterest(context.Background()).SettleLeverageAccruedInterestRequest(settleLeverageAccruedInterestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.SettleLeverageAccruedInterest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SettleLeverageAccruedInterest`: SettleLeverageAccruedInterestResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.SettleLeverageAccruedInterest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSettleLeverageAccruedInterestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **settleLeverageAccruedInterestRequest** | [**SettleLeverageAccruedInterestRequest**](SettleLeverageAccruedInterestRequest.md) |  | 

### Return type

[**SettleLeverageAccruedInterestResponseEnvelope**](SettleLeverageAccruedInterestResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SettleRealizedPnlRecord

> SettleRealizedPnlRecordResponseEnvelope SettleRealizedPnlRecord(ctx, settlementId).Execute()

Mark a realized P&L settlement as settled

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	settlementId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.SettleRealizedPnlRecord(context.Background(), settlementId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.SettleRealizedPnlRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SettleRealizedPnlRecord`: SettleRealizedPnlRecordResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.SettleRealizedPnlRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**settlementId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSettleRealizedPnlRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SettleRealizedPnlRecordResponseEnvelope**](SettleRealizedPnlRecordResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SettleTransactionsSettlements

> TransactionsSettlementsResponse SettleTransactionsSettlements(ctx).TransactionsSettlementRequest(transactionsSettlementRequest).Execute()

Settle multiple transactions settlements in batch

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	transactionsSettlementRequest := *openapiclient.NewTransactionsSettlementRequest() // TransactionsSettlementRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.SettleTransactionsSettlements(context.Background()).TransactionsSettlementRequest(transactionsSettlementRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.SettleTransactionsSettlements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SettleTransactionsSettlements`: TransactionsSettlementsResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.SettleTransactionsSettlements`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSettleTransactionsSettlementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **transactionsSettlementRequest** | [**TransactionsSettlementRequest**](TransactionsSettlementRequest.md) |  | 

### Return type

[**TransactionsSettlementsResponse**](TransactionsSettlementsResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamAssetPrices

> map[string]AssetPrice StreamAssetPrices(ctx).AssetId(assetId).Execute()

Stream real-time asset prices as map objects



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.StreamAssetPrices(context.Background()).AssetId(assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.StreamAssetPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamAssetPrices`: map[string]AssetPrice
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.StreamAssetPrices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStreamAssetPricesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetId** | **string** |  | 

### Return type

[**map[string]AssetPrice**](AssetPrice.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamCandleData

> []StreamCandlesEntry StreamCandleData(ctx, orderBookId).Since(since).Resolution(resolution).Execute()

Get a snapshot of candlestick data from date provided, and open a stream for real-time updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "orderBookId_example" // string | 
	since := time.Now() // time.Time |  (optional)
	resolution := openapiclient.CandleResolution("1m") // CandleResolution |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.StreamCandleData(context.Background(), orderBookId).Since(since).Resolution(resolution).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.StreamCandleData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamCandleData`: []StreamCandlesEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.StreamCandleData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStreamCandleDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **time.Time** |  | 
 **resolution** | [**CandleResolution**](CandleResolution.md) |  | 

### Return type

[**[]StreamCandlesEntry**](StreamCandlesEntry.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamOrderBookBalances

> []StreamOrderBookBalanceEntry StreamOrderBookBalances(ctx, orderBookId).Since(since).Execute()

Get a snapshot of base and quote balances for an order book and open a stream for real-time updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	since := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.StreamOrderBookBalances(context.Background(), orderBookId).Since(since).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.StreamOrderBookBalances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamOrderBookBalances`: []StreamOrderBookBalanceEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.StreamOrderBookBalances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStreamOrderBookBalancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **time.Time** |  | 

### Return type

[**[]StreamOrderBookBalanceEntry**](StreamOrderBookBalanceEntry.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamOrderbookOpenOrders

> LiveOrderbook StreamOrderbookOpenOrders(ctx, orderBookId).Since(since).Execute()

Get a snapshot of open orders in an order book and open a stream for real-time updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	since := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.StreamOrderbookOpenOrders(context.Background(), orderBookId).Since(since).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.StreamOrderbookOpenOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamOrderbookOpenOrders`: LiveOrderbook
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.StreamOrderbookOpenOrders`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStreamOrderbookOpenOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **time.Time** |  | 

### Return type

[**LiveOrderbook**](LiveOrderbook.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamTrades

> []StreamTradesEntry StreamTrades(ctx, orderBookId).Since(since).Execute()

Get a snapshot of trades executed on the given order book from a specific date and open a stream for real-time updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	orderBookId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	since := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.StreamTrades(context.Background(), orderBookId).Since(since).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.StreamTrades``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamTrades`: []StreamTradesEntry
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.StreamTrades`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderBookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStreamTradesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **time.Time** |  | 

### Return type

[**[]StreamTradesEntry**](StreamTradesEntry.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TerminateOwnTradingChallengeParticipation

> TerminateTradingChallengeResponseEnvelope TerminateOwnTradingChallengeParticipation(ctx, tradingChallengeId).Execute()

Leave a trading challenge



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.TerminateOwnTradingChallengeParticipation(context.Background(), tradingChallengeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.TerminateOwnTradingChallengeParticipation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TerminateOwnTradingChallengeParticipation`: TerminateTradingChallengeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.TerminateOwnTradingChallengeParticipation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTerminateOwnTradingChallengeParticipationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TerminateTradingChallengeResponseEnvelope**](TerminateTradingChallengeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TerminateTradingChallengeParticipation

> TerminateTradingChallengeResponseEnvelope TerminateTradingChallengeParticipation(ctx, tradingChallengeId, userId).Execute()

Terminate a participation in a trading challenge



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.TerminateTradingChallengeParticipation(context.Background(), tradingChallengeId, userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.TerminateTradingChallengeParticipation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TerminateTradingChallengeParticipation`: TerminateTradingChallengeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.TerminateTradingChallengeParticipation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTerminateTradingChallengeParticipationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**TerminateTradingChallengeResponseEnvelope**](TerminateTradingChallengeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TransferAccountBalancesV2

> TransferAccountBalancesResponseEnvelope TransferAccountBalancesV2(ctx).TransferAccountBalancesRequest(transferAccountBalancesRequest).Execute()

Transfer available balance between a user's accounts

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	transferAccountBalancesRequest := *openapiclient.NewTransferAccountBalancesRequest("FromAccountId_example", "ToAccountId_example", "AssetId_example", "Quantity_example") // TransferAccountBalancesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.TransferAccountBalancesV2(context.Background()).TransferAccountBalancesRequest(transferAccountBalancesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.TransferAccountBalancesV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TransferAccountBalancesV2`: TransferAccountBalancesResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.TransferAccountBalancesV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTransferAccountBalancesV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **transferAccountBalancesRequest** | [**TransferAccountBalancesRequest**](TransferAccountBalancesRequest.md) |  | 

### Return type

[**TransferAccountBalancesResponseEnvelope**](TransferAccountBalancesResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TransferAvailableBalances

> TransferBalancesResponseEnvelope TransferAvailableBalances(ctx).TransferBalancesRequest(transferBalancesRequest).Execute()

Transfer available balance between a user's accounts (e.g. global to isolated position)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	transferBalancesRequest := *openapiclient.NewTransferBalancesRequest("FromPositionId_example", "ToPositionId_example", "AssetId_example", "Quantity_example") // TransferBalancesRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.TransferAvailableBalances(context.Background()).TransferBalancesRequest(transferBalancesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.TransferAvailableBalances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TransferAvailableBalances`: TransferBalancesResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.TransferAvailableBalances`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTransferAvailableBalancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **transferBalancesRequest** | [**TransferBalancesRequest**](TransferBalancesRequest.md) |  | 

### Return type

[**TransferBalancesResponseEnvelope**](TransferBalancesResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAffiliateProgram

> AffiliateProgramEnvelope UpdateAffiliateProgram(ctx, programId).UpdateAffiliateProgramRequest(updateAffiliateProgramRequest).Execute()

Update an affiliate program



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	programId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	updateAffiliateProgramRequest := *openapiclient.NewUpdateAffiliateProgramRequest() // UpdateAffiliateProgramRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.UpdateAffiliateProgram(context.Background(), programId).UpdateAffiliateProgramRequest(updateAffiliateProgramRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.UpdateAffiliateProgram``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAffiliateProgram`: AffiliateProgramEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.UpdateAffiliateProgram`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**programId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAffiliateProgramRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAffiliateProgramRequest** | [**UpdateAffiliateProgramRequest**](UpdateAffiliateProgramRequest.md) |  | 

### Return type

[**AffiliateProgramEnvelope**](AffiliateProgramEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTradingChallenge

> TradingChallengeResponseEnvelope UpdateTradingChallenge(ctx, tradingChallengeId).UpdateTradingChallengeRequest(updateTradingChallengeRequest).Execute()

Update a trading challenge



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	tradingChallengeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	updateTradingChallengeRequest := *openapiclient.NewUpdateTradingChallengeRequest() // UpdateTradingChallengeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.UpdateTradingChallenge(context.Background(), tradingChallengeId).UpdateTradingChallengeRequest(updateTradingChallengeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.UpdateTradingChallenge``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTradingChallenge`: TradingChallengeResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.UpdateTradingChallenge`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tradingChallengeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTradingChallengeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateTradingChallengeRequest** | [**UpdateTradingChallengeRequest**](UpdateTradingChallengeRequest.md) |  | 

### Return type

[**TradingChallengeResponseEnvelope**](TradingChallengeResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserConfig

> UserUpdatedResponseEnvelope UpdateUserConfig(ctx, userId).UpdateUserConfigRequest(updateUserConfigRequest).Execute()

Update user configuration by ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	updateUserConfigRequest := *openapiclient.NewUpdateUserConfigRequest(*openapiclient.NewUpdateFieldString(false)) // UpdateUserConfigRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.UpdateUserConfig(context.Background(), userId).UpdateUserConfigRequest(updateUserConfigRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.UpdateUserConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserConfig`: UserUpdatedResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.UpdateUserConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateUserConfigRequest** | [**UpdateUserConfigRequest**](UpdateUserConfigRequest.md) |  | 

### Return type

[**UserUpdatedResponseEnvelope**](UserUpdatedResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserConfigSelf

> UserUpdatedResponseEnvelope UpdateUserConfigSelf(ctx).UpdateUserConfigRequest(updateUserConfigRequest).Execute()

Update user configuration for the authenticated user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	updateUserConfigRequest := *openapiclient.NewUpdateUserConfigRequest(*openapiclient.NewUpdateFieldString(false)) // UpdateUserConfigRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.UpdateUserConfigSelf(context.Background()).UpdateUserConfigRequest(updateUserConfigRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.UpdateUserConfigSelf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserConfigSelf`: UserUpdatedResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.UpdateUserConfigSelf`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserConfigSelfRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateUserConfigRequest** | [**UpdateUserConfigRequest**](UpdateUserConfigRequest.md) |  | 

### Return type

[**UserUpdatedResponseEnvelope**](UserUpdatedResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserKYC

> UpdateUserKYCResponseEnvelope UpdateUserKYC(ctx, userId).UpdateUserKYCRequest(updateUserKYCRequest).Execute()

Set or clear a user's KYC completion timestamp

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	updateUserKYCRequest := *openapiclient.NewUpdateUserKYCRequest(false) // UpdateUserKYCRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.UpdateUserKYC(context.Background(), userId).UpdateUserKYCRequest(updateUserKYCRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.UpdateUserKYC``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserKYC`: UpdateUserKYCResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.UpdateUserKYC`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserKYCRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateUserKYCRequest** | [**UpdateUserKYCRequest**](UpdateUserKYCRequest.md) |  | 

### Return type

[**UpdateUserKYCResponseEnvelope**](UpdateUserKYCResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidateSubmitOrder

> ValidateSubmitOrderResponse ValidateSubmitOrder(ctx).ValidateSubmitOrderRequest(validateSubmitOrderRequest).Execute()

Validate submit order request data

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	validateSubmitOrderRequest := *openapiclient.NewValidateSubmitOrderRequest("Quantity_example", "Tick_example", openapiclient.OrderKind("LIMIT"), "Price_example", "InverseLeverage_example", "UserBalance_example") // ValidateSubmitOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ValidateSubmitOrder(context.Background()).ValidateSubmitOrderRequest(validateSubmitOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ValidateSubmitOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidateSubmitOrder`: ValidateSubmitOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ValidateSubmitOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiValidateSubmitOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **validateSubmitOrderRequest** | [**ValidateSubmitOrderRequest**](ValidateSubmitOrderRequest.md) |  | 

### Return type

[**ValidateSubmitOrderResponse**](ValidateSubmitOrderResponse.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyUser

> UserUpdatedResponseEnvelope VerifyUser(ctx, userId).Execute()

Verify a user by ID

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-client-go/doraclient"
)

func main() {
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.VerifyUser(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.VerifyUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyUser`: UserUpdatedResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.VerifyUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiVerifyUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserUpdatedResponseEnvelope**](UserUpdatedResponseEnvelope.md)

### Authorization

[apiKeyAuthHeader](../README.md#apiKeyAuthHeader), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

