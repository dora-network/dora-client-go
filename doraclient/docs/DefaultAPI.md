# \DefaultAPI

All URIs are relative to *https://localhost:8084*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelAllOpenOrders**](DefaultAPI.md#CancelAllOpenOrders) | **Delete** /v1/orders | Cancel all open orders, if user passes orderbook on query param it will cancel all orders on specific orderbook, admin can cancel user&#39;s orders on specific orderbook
[**CancelOrderById**](DefaultAPI.md#CancelOrderById) | **Delete** /v1/orders/{order_id} | Cancel an order by ID
[**CheckUserEmailExists**](DefaultAPI.md#CheckUserEmailExists) | **Get** /v1/user/exists | Check whether a user email exists
[**ClaimLeverageGetAccruedInterest**](DefaultAPI.md#ClaimLeverageGetAccruedInterest) | **Post** /v1/leverage/accrued_interest/claim | Claim current accrued leverage interest for a specific user
[**CloseIsolatedPosition**](DefaultAPI.md#CloseIsolatedPosition) | **Post** /v1/positions/close | Close isolated positions, repaying the borrowed
[**CreateAPIKeyForUser**](DefaultAPI.md#CreateAPIKeyForUser) | **Post** /v1/user/apikey | Create apikey for a user
[**CreateNewIsolatedPosition**](DefaultAPI.md#CreateNewIsolatedPosition) | **Post** /v1/positions/new_isolated | Create a new isolated position for a user transferring available assets into the position
[**CreateOrder**](DefaultAPI.md#CreateOrder) | **Post** /v1/orders | Create a new order
[**DeleteUser**](DefaultAPI.md#DeleteUser) | **Delete** /v1/user/{user_id} | Delete user by ID
[**GetAllAssetPrices**](DefaultAPI.md#GetAllAssetPrices) | **Get** /v1/price | Get the current price of all assets
[**GetAssetById**](DefaultAPI.md#GetAssetById) | **Get** /v1/assets/{asset_id} | Get asset by ID
[**GetAssetPrice**](DefaultAPI.md#GetAssetPrice) | **Get** /v1/price/asset/{asset_id} | Get the current price of an asset
[**GetAssetsStream**](DefaultAPI.md#GetAssetsStream) | **Get** /v1/assets/stream | Get all inserts or updates for assets
[**GetCandleData**](DefaultAPI.md#GetCandleData) | **Get** /v1/charts/{order_book_id}/candle | Get candlestick data for an orderbook
[**GetCouponPaymentsByAssetId**](DefaultAPI.md#GetCouponPaymentsByAssetId) | **Get** /v1/assets/{asset_id}/coupon_payments | Get coupon payments for a bond asset
[**GetL1Depth**](DefaultAPI.md#GetL1Depth) | **Get** /v1/orderbooks/{order_book_id}/L1 | Get the top price levels for a specific orderbook (L1 market depth)
[**GetL2Depth**](DefaultAPI.md#GetL2Depth) | **Get** /v1/orderbooks/{order_book_id}/L2 | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetL3Depth**](DefaultAPI.md#GetL3Depth) | **Get** /v1/orderbooks/{order_book_id}/L3 | Get all open orders for a specific orderbook (L3 market depth)
[**GetLedgerBalancesSelf**](DefaultAPI.md#GetLedgerBalancesSelf) | **Get** /v1/ledger/balances/self | Get your own available, locked, and borrowed assets
[**GetLedgerInterestSelf**](DefaultAPI.md#GetLedgerInterestSelf) | **Get** /v1/ledger/interest/self | Get your own interest
[**GetLedgerModule**](DefaultAPI.md#GetLedgerModule) | **Get** /v1/ledger/module | Get the entire module object, including unborrowed leverage assets and total leverage trackers
[**GetLedgerModuleByAsset**](DefaultAPI.md#GetLedgerModuleByAsset) | **Get** /v1/ledger/module/{asset_id} | Get the module object for a single asset ID
[**GetLedgerPositionsSelf**](DefaultAPI.md#GetLedgerPositionsSelf) | **Get** /v1/ledger/positions/self | Get your own positions
[**GetLedgerValueSelf**](DefaultAPI.md#GetLedgerValueSelf) | **Get** /v1/ledger/value/self | Get your own available, locked, and borrowed USD value; and realized and unrealized PnL
[**GetOrderById**](DefaultAPI.md#GetOrderById) | **Get** /v1/orders/{order_id} | Get order by ID
[**GetOrderbookById**](DefaultAPI.md#GetOrderbookById) | **Get** /v1/orderbooks/{order_book_id} | Get orderbook by ID
[**GetOrderbookDepth**](DefaultAPI.md#GetOrderbookDepth) | **Get** /v1/orderbooks/{order_book_id}/depth | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetOrderbookOrders**](DefaultAPI.md#GetOrderbookOrders) | **Get** /v1/orderbooks/{order_book_id}/orders | Get all open orders for a specific orderbook (L3 market depth)
[**GetOrderbookStats**](DefaultAPI.md#GetOrderbookStats) | **Get** /v1/orderbooks/{order_book_id}/stats | Get orderbook stats
[**GetOrderbookStatsStream**](DefaultAPI.md#GetOrderbookStatsStream) | **Get** /v1/orderbooks/{order_book_id}/stats/stream | Orderbook stats stream
[**GetOrderbookSummary**](DefaultAPI.md#GetOrderbookSummary) | **Get** /v1/orderbooks/{order_book_id}/summary | Get summary of an orderbook
[**GetOrderbookTop**](DefaultAPI.md#GetOrderbookTop) | **Get** /v1/orderbooks/{order_book_id}/top | Get the top price levels for a specific orderbook (L1 market depth)
[**GetPoolPrice**](DefaultAPI.md#GetPoolPrice) | **Get** /v1/price/pool/{pool_id} | Get the current price of a pool
[**GetTradeById**](DefaultAPI.md#GetTradeById) | **Get** /v1/trades/{trade_id} | Get a trade by ID
[**GetTrades**](DefaultAPI.md#GetTrades) | **Get** /v1/trades | Get a filtered, paginated list of trades
[**GetTransactionById**](DefaultAPI.md#GetTransactionById) | **Get** /v1/transactions/{transaction_id} | Get a transaction by ID
[**GetTransactions**](DefaultAPI.md#GetTransactions) | **Get** /v1/transactions | Get a filtered, paginated list of transactions
[**GetUserById**](DefaultAPI.md#GetUserById) | **Get** /v1/user/{user_id} | Get user by ID (admin only)
[**GetUserLedgerStream**](DefaultAPI.md#GetUserLedgerStream) | **Get** /v1/user/{user_id}/ledger/stream | Get a snapshot of user&#39;s ledger updates since a specific time, and opens a stream for further updates
[**GetUserOrderUpdatesStream**](DefaultAPI.md#GetUserOrderUpdatesStream) | **Get** /v1/user/{user_id}/orders/{order_book_id}/updates/stream | Get a snapshot of user&#39;s order updates for the given order book since a specific time, and opens a stream for further updates
[**GetUserOrdersUpdatesStreamAll**](DefaultAPI.md#GetUserOrdersUpdatesStreamAll) | **Get** /v1/user/{user_id}/orders/all/updates/stream | Get a snapshot of user&#39;s order updates across all order books since a specific time, and opens a stream for further updates
[**GetUserSelf**](DefaultAPI.md#GetUserSelf) | **Get** /v1/user/self | Get user details for the authenticated user
[**GetUserTransactionsStream**](DefaultAPI.md#GetUserTransactionsStream) | **Get** /v1/user/{user_id}/transactions/stream | Get a snapshot of user&#39;s executed transactions since a specific time, and opens a stream for further updates
[**GetUsersAPIKeys**](DefaultAPI.md#GetUsersAPIKeys) | **Get** /v1/user/apikey | Get user&#39;s api keys
[**LeverageGetAccruedInterestByUser**](DefaultAPI.md#LeverageGetAccruedInterestByUser) | **Get** /v1/leverage/accrued_interest/self | Get current accrued leverage interest for the user
[**LeverageIsolateCollateral**](DefaultAPI.md#LeverageIsolateCollateral) | **Post** /v1/leverage/isolate_collateral | Create an isolated position by transferring collateral to the position from the user&#39;s global collateral
[**LeverageSupply**](DefaultAPI.md#LeverageSupply) | **Post** /v1/leverage/supply | Supply leverage for a specific asset
[**LeverageUnite**](DefaultAPI.md#LeverageUnite) | **Post** /v1/leverage/unite | Combines all isolated positions into a single global position
[**LeverageWithdraw**](DefaultAPI.md#LeverageWithdraw) | **Post** /v1/leverage/withdraw | Withdraw leverage for a specific asset
[**LiquidityAdd**](DefaultAPI.md#LiquidityAdd) | **Post** /v1/liquidity/pool/{pool_id}/add | Add liquidity to a pool
[**LiquiditySubtract**](DefaultAPI.md#LiquiditySubtract) | **Post** /v1/liquidity/pool/{pool_id}/remove | Subtract liquidity from a pool
[**ListAssets**](DefaultAPI.md#ListAssets) | **Get** /v1/assets | List assets
[**ListOrderBooks**](DefaultAPI.md#ListOrderBooks) | **Get** /v1/orderbooks | List order books
[**ListOrders**](DefaultAPI.md#ListOrders) | **Get** /v1/orders | List all orders
[**ListPositionAccountsSelf**](DefaultAPI.md#ListPositionAccountsSelf) | **Get** /v1/user/self/position_accounts | List all position accounts for the authenticated user
[**PayLeverageGetAccruedInterest**](DefaultAPI.md#PayLeverageGetAccruedInterest) | **Post** /v1/leverage/accrued_interest/pay | Pay current accrued leverage interest for a specific user
[**RevokeAPIKeyForUser**](DefaultAPI.md#RevokeAPIKeyForUser) | **Put** /v1/user/apikey/{key_id}/revoke | Revoke apikey for a user
[**StreamAssetPrices**](DefaultAPI.md#StreamAssetPrices) | **Get** /v1/prices/stream | Stream real-time asset prices as map objects
[**StreamCandleData**](DefaultAPI.md#StreamCandleData) | **Get** /v1/charts/{order_book_id}/candle/stream | Get a snapshot of candlestick data from date provided, and open a stream for real-time updates
[**StreamOrderBookBalances**](DefaultAPI.md#StreamOrderBookBalances) | **Get** /v1/orderbooks/{order_book_id}/balances/stream | Get a snapshot of base and quote balances for an order book and open a stream for real-time updates
[**StreamOrderbookOpenOrders**](DefaultAPI.md#StreamOrderbookOpenOrders) | **Get** /v1/orderbooks/{order_book_id}/open/stream | Get a snapshot of open orders in an order book and open a stream for real-time updates
[**StreamTrades**](DefaultAPI.md#StreamTrades) | **Get** /v1/trades/{order_book_id}/stream | Get a snapshot of trades executed on the given order book from a specific date and open a stream for real-time updates
[**TransferAvailableBalances**](DefaultAPI.md#TransferAvailableBalances) | **Post** /v1/positions/transfer_balances | Transfer available balance between a user&#39;s accounts (e.g. global to isolated position)
[**UpdateUserConfig**](DefaultAPI.md#UpdateUserConfig) | **Put** /v1/user/{user_id}/config | Update user configuration by ID
[**UpdateUserConfigSelf**](DefaultAPI.md#UpdateUserConfigSelf) | **Put** /v1/user/config/self | Update user configuration for the authenticated user
[**ValidateSubmitOrder**](DefaultAPI.md#ValidateSubmitOrder) | **Post** /v1/orders/validate | Validate submit order request data
[**VerifyUser**](DefaultAPI.md#VerifyUser) | **Put** /v1/user/{user_id}/verify | Verify a user by ID



## CancelAllOpenOrders

> ListOrdersResponseEnvelope CancelAllOpenOrders(ctx).OrderBookId(orderBookId).UserId(userId).OrderKind(orderKind).Execute()

Cancel all open orders, if user passes orderbook on query param it will cancel all orders on specific orderbook, admin can cancel user's orders on specific orderbook

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	orderBookId := "orderBookId_example" // string |  (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	orderKind := openapiclient.OrderKind("LIMIT") // OrderKind |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CancelAllOpenOrders(context.Background()).OrderBookId(orderBookId).UserId(userId).OrderKind(orderKind).Execute()
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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


## CheckUserEmailExists

> EmailExistsResponseEnvelope CheckUserEmailExists(ctx).Email(email).Execute()

Check whether a user email exists

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	email := "email_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CheckUserEmailExists(context.Background()).Email(email).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CheckUserEmailExists``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckUserEmailExists`: EmailExistsResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CheckUserEmailExists`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckUserEmailExistsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email** | **string** |  | 

### Return type

[**EmailExistsResponseEnvelope**](EmailExistsResponseEnvelope.md)

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	claimLeverageAccruedInterestRequest := *openapiclient.NewClaimLeverageAccruedInterestRequest() // ClaimLeverageAccruedInterestRequest | 

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	createAPIKeyRequest := *openapiclient.NewCreateAPIKeyRequest() // CreateAPIKeyRequest | 

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


## CreateNewIsolatedPosition

> NewIsolatedPositionResponseEnvelope CreateNewIsolatedPosition(ctx).NewIsolatedPositionRequest(newIsolatedPositionRequest).Execute()

Create a new isolated position for a user transferring available assets into the position

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	newIsolatedPositionRequest := *openapiclient.NewNewIsolatedPositionRequest("GlobalPositionId_example", "AssetId_example", "Quantity_example") // NewIsolatedPositionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateNewIsolatedPosition(context.Background()).NewIsolatedPositionRequest(newIsolatedPositionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateNewIsolatedPosition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateNewIsolatedPosition`: NewIsolatedPositionResponseEnvelope
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateNewIsolatedPosition`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateNewIsolatedPositionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **newIsolatedPositionRequest** | [**NewIsolatedPositionRequest**](NewIsolatedPositionRequest.md) |  | 

### Return type

[**NewIsolatedPositionResponseEnvelope**](NewIsolatedPositionResponseEnvelope.md)

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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


## GetAssetsStream

> StreamAssetsResponse GetAssetsStream(ctx).Since(since).Until(until).Execute()

Get all inserts or updates for assets

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	// response from `GetAssetsStream`: StreamAssetsResponse
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

[**StreamAssetsResponse**](StreamAssetsResponse.md)

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	orderBookId := "orderBookId_example" // string | 
	start := time.Now() // time.Time |  (optional)
	end := time.Now() // time.Time |  (optional)
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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

> ListTransactionsResponseEnvelope GetTransactions(ctx).Pools(pools).UserIds(userIds).TxKinds(txKinds).Start(start).End(end).Page(page).Limit(limit).Execute()

Get a filtered, paginated list of transactions

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	pools := []string{"Inner_example"} // []string |  (optional)
	userIds := []string{"Inner_example"} // []string |  (optional)
	txKinds := []openapiclient.TransactionKind{openapiclient.TransactionKind("ACCRUE_INTEREST")} // []TransactionKind |  (optional)
	start := time.Now() // time.Time |  (optional)
	end := time.Now() // time.Time |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetTransactions(context.Background()).Pools(pools).UserIds(userIds).TxKinds(txKinds).Start(start).End(end).Page(page).Limit(limit).Execute()
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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


## GetUserLedgerStream

> StreamPositionsResponse GetUserLedgerStream(ctx, userId).Execute()

Get a snapshot of user's ledger updates since a specific time, and opens a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	// response from `GetUserLedgerStream`: StreamPositionsResponse
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

[**StreamPositionsResponse**](StreamPositionsResponse.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserOrderUpdatesStream

> StreamOrderUpdatesResponse GetUserOrderUpdatesStream(ctx, userId, orderBookId).Since(since).Execute()

Get a snapshot of user's order updates for the given order book since a specific time, and opens a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	// response from `GetUserOrderUpdatesStream`: StreamOrderUpdatesResponse
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

[**StreamOrderUpdatesResponse**](StreamOrderUpdatesResponse.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserOrdersUpdatesStreamAll

> StreamOrderUpdatesResponse GetUserOrdersUpdatesStreamAll(ctx, userId).Since(since).Execute()

Get a snapshot of user's order updates across all order books since a specific time, and opens a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	// response from `GetUserOrdersUpdatesStreamAll`: StreamOrderUpdatesResponse
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

[**StreamOrderUpdatesResponse**](StreamOrderUpdatesResponse.md)

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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

> StreamTransactionsResponse GetUserTransactionsStream(ctx, userId).Since(since).Execute()

Get a snapshot of user's executed transactions since a specific time, and opens a stream for further updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	// response from `GetUserTransactionsStream`: StreamTransactionsResponse
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

[**StreamTransactionsResponse**](StreamTransactionsResponse.md)

### Authorization

[apiKeyAuthQuery](../README.md#apiKeyAuthQuery)

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	status := openapiclient.OrderBookStatus("CLOSED") // OrderBookStatus |  (optional)
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
 **status** | [**OrderBookStatus**](OrderBookStatus.md) |  | 
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

> ListOrdersResponseEnvelope ListOrders(ctx).OrderBookId(orderBookId).Kind(kind).Status(status).Side(side).From(from).To(to).Page(page).Limit(limit).Execute()

List all orders

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	orderBookId := []string{"Inner_example"} // []string |  (optional)
	kind := []openapiclient.OrderKind{openapiclient.OrderKind("LIMIT")} // []OrderKind |  (optional)
	status := []openapiclient.OrderStatus{openapiclient.OrderStatus("OPEN")} // []OrderStatus |  (optional)
	side := openapiclient.Side("BUY") // Side |  (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListOrders(context.Background()).OrderBookId(orderBookId).Kind(kind).Status(status).Side(side).From(from).To(to).Page(page).Limit(limit).Execute()
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
 **orderBookId** | **[]string** |  | 
 **kind** | [**[]OrderKind**](OrderKind.md) |  | 
 **status** | [**[]OrderStatus**](OrderStatus.md) |  | 
 **side** | [**Side**](Side.md) |  | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** |  | 
 **page** | **int32** |  | [default to 1]
 **limit** | **int32** |  | [default to 100]

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	payLeverageAccruedInterestRequest := *openapiclient.NewPayLeverageAccruedInterestRequest() // PayLeverageAccruedInterestRequest | 

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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


## StreamAssetPrices

> StreamAssetPricesResponse StreamAssetPrices(ctx).Since(since).AssetId(assetId).Execute()

Stream real-time asset prices as map objects



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
)

func main() {
	since := time.Now() // time.Time |  (optional)
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.StreamAssetPrices(context.Background()).Since(since).AssetId(assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.StreamAssetPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamAssetPrices`: StreamAssetPricesResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.StreamAssetPrices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStreamAssetPricesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **since** | **time.Time** |  | 
 **assetId** | **string** |  | 

### Return type

[**StreamAssetPricesResponse**](StreamAssetPricesResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamCandleData

> StreamCandlesResponse StreamCandleData(ctx, orderBookId).Since(since).Resolution(resolution).Execute()

Get a snapshot of candlestick data from date provided, and open a stream for real-time updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	// response from `StreamCandleData`: StreamCandlesResponse
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

[**StreamCandlesResponse**](StreamCandlesResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamOrderBookBalances

> StreamOrderBookBalancesResponse StreamOrderBookBalances(ctx, orderBookId).Since(since).Execute()

Get a snapshot of base and quote balances for an order book and open a stream for real-time updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	// response from `StreamOrderBookBalances`: StreamOrderBookBalancesResponse
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

[**StreamOrderBookBalancesResponse**](StreamOrderBookBalancesResponse.md)

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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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

> StreamTradesResponse StreamTrades(ctx, orderBookId).Since(since).Execute()

Get a snapshot of trades executed on the given order book from a specific date and open a stream for real-time updates

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	// response from `StreamTrades`: StreamTradesResponse
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

[**StreamTradesResponse**](StreamTradesResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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
	openapiclient "github.com/dora-network/dora-go-client/doraclient"
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

