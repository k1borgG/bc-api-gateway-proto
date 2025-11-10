# Protocol Documentation
<a name="top"></a>

## Table of Contents

- [api_internal.proto](#api_internal-proto)
    - [BcApiGatewayInternal](#api-BcApiGatewayInternal)
  
- [api_merchant.proto](#api_merchant-proto)
    - [BcApiGatewayMerchant](#api-BcApiGatewayMerchant)
  
- [messages.proto](#messages-proto)
    - [AccountData](#api-AccountData)
    - [AccountIdentity](#api-AccountIdentity)
    - [AccountInfo](#api-AccountInfo)
    - [AddAccountCurrencyRequest](#api-AddAccountCurrencyRequest)
    - [AddAccountCurrencyResponse](#api-AddAccountCurrencyResponse)
    - [AddressIdentity](#api-AddressIdentity)
    - [Amount](#api-Amount)
    - [BcTxIdentity](#api-BcTxIdentity)
    - [BcTxInfo](#api-BcTxInfo)
    - [BcTxInfo.OperationsEntry](#api-BcTxInfo-OperationsEntry)
    - [BcTxOperation](#api-BcTxOperation)
    - [CreateAccountRequest](#api-CreateAccountRequest)
    - [CreateAccountResponse](#api-CreateAccountResponse)
    - [CreateCurrencyRequest](#api-CreateCurrencyRequest)
    - [CreateCurrencyResponse](#api-CreateCurrencyResponse)
    - [CreateMerchantRequest](#api-CreateMerchantRequest)
    - [CreateMerchantResponse](#api-CreateMerchantResponse)
    - [CreateWalletRequest](#api-CreateWalletRequest)
    - [CreateWalletResponse](#api-CreateWalletResponse)
    - [CreateWithdrawOrderRequest](#api-CreateWithdrawOrderRequest)
    - [CreateWithdrawOrderResponse](#api-CreateWithdrawOrderResponse)
    - [Currency](#api-Currency)
    - [CurrencyData](#api-CurrencyData)
    - [CurrencyIdentity](#api-CurrencyIdentity)
    - [CurrencyIdentityResponse](#api-CurrencyIdentityResponse)
    - [CurrencyInfo](#api-CurrencyInfo)
    - [EstimatedTime](#api-EstimatedTime)
    - [EstimationFeeIdentify](#api-EstimationFeeIdentify)
    - [EstimationFeeIdentity](#api-EstimationFeeIdentity)
    - [EventIdentity](#api-EventIdentity)
    - [EventInformation](#api-EventInformation)
    - [FeeInfo](#api-FeeInfo)
    - [GetAllWalletsRequest](#api-GetAllWalletsRequest)
    - [GetAllWalletsResponse](#api-GetAllWalletsResponse)
    - [GetCurrenciesRequest](#api-GetCurrenciesRequest)
    - [GetCurrenciesResponse](#api-GetCurrenciesResponse)
    - [GetDepositAddressRequest](#api-GetDepositAddressRequest)
    - [GetDepositAddressResponse](#api-GetDepositAddressResponse)
    - [GetEstimationFeeRequest](#api-GetEstimationFeeRequest)
    - [GetEstimationFeeResponse](#api-GetEstimationFeeResponse)
    - [GetEventListRequest](#api-GetEventListRequest)
    - [GetEventListResponse](#api-GetEventListResponse)
    - [GetOrderInfoRequest](#api-GetOrderInfoRequest)
    - [GetOrderInfoResponse](#api-GetOrderInfoResponse)
    - [GetOrderListByLimitAndOffsetRequest](#api-GetOrderListByLimitAndOffsetRequest)
    - [GetOrderListByLimitAndOffsetResponse](#api-GetOrderListByLimitAndOffsetResponse)
    - [GetOrderListByTimeRangeRequest](#api-GetOrderListByTimeRangeRequest)
    - [GetOrderListByTimeRangeResponse](#api-GetOrderListByTimeRangeResponse)
    - [GetTransactionRequest](#api-GetTransactionRequest)
    - [GetTransactionResponse](#api-GetTransactionResponse)
    - [GetWalletBalanceRequest](#api-GetWalletBalanceRequest)
    - [GetWalletBalanceResponse](#api-GetWalletBalanceResponse)
    - [GetWalletsRequest](#api-GetWalletsRequest)
    - [GetWalletsResponse](#api-GetWalletsResponse)
    - [GetWithdrawOrderRequest](#api-GetWithdrawOrderRequest)
    - [GetWithdrawOrderResponse](#api-GetWithdrawOrderResponse)
    - [MerchantIdentity](#api-MerchantIdentity)
    - [OperationsList](#api-OperationsList)
    - [OrderIdentify](#api-OrderIdentify)
    - [OrderIdentityResponse](#api-OrderIdentityResponse)
    - [OrderInfo](#api-OrderInfo)
    - [TimeRangeRequest](#api-TimeRangeRequest)
    - [TokenData](#api-TokenData)
    - [WalletData](#api-WalletData)
    - [WalletIdentity](#api-WalletIdentity)
    - [WalletInfo](#api-WalletInfo)
  
    - [AccountStatus](#api-AccountStatus)
    - [AccountType](#api-AccountType)
    - [BcTxStatus](#api-BcTxStatus)
    - [FeeLevel](#api-FeeLevel)
    - [Network](#api-Network)
    - [OrderStatus](#api-OrderStatus)
    - [OrderType](#api-OrderType)
    - [Provider](#api-Provider)
    - [WalletStatus](#api-WalletStatus)
    - [WalletType](#api-WalletType)
  
- [Scalar Value Types](#scalar-value-types)



<a name="api_internal-proto"></a>
<p align="right"><a href="#top">Top</a></p>

## api_internal.proto


 

 

 


<a name="api-BcApiGatewayInternal"></a>

### BcApiGatewayInternal
Internal RPC api gateway

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateMerchant | [CreateMerchantRequest](#api-CreateMerchantRequest) | [CreateMerchantResponse](#api-CreateMerchantResponse) |  |
| CreateWallet | [CreateWalletRequest](#api-CreateWalletRequest) | [CreateWalletResponse](#api-CreateWalletResponse) |  |
| CreateAccount | [CreateAccountRequest](#api-CreateAccountRequest) | [CreateAccountResponse](#api-CreateAccountResponse) |  |
| CreateCurrency | [CreateCurrencyRequest](#api-CreateCurrencyRequest) | [CreateCurrencyResponse](#api-CreateCurrencyResponse) |  |
| AddAccountCurrency | [AddAccountCurrencyRequest](#api-AddAccountCurrencyRequest) | [AddAccountCurrencyResponse](#api-AddAccountCurrencyResponse) |  |
| GetWallets | [GetWalletsRequest](#api-GetWalletsRequest) | [GetWalletsResponse](#api-GetWalletsResponse) |  |
| GetCurrencies | [GetCurrenciesRequest](#api-GetCurrenciesRequest) | [GetCurrenciesResponse](#api-GetCurrenciesResponse) |  |
| GetAllWallets | [GetAllWalletsRequest](#api-GetAllWalletsRequest) | [GetAllWalletsResponse](#api-GetAllWalletsResponse) |  |
| GetTransaction | [GetTransactionRequest](#api-GetTransactionRequest) | [GetTransactionResponse](#api-GetTransactionResponse) |  |
| GetWithdrawOrder | [GetWithdrawOrderRequest](#api-GetWithdrawOrderRequest) | [GetWithdrawOrderResponse](#api-GetWithdrawOrderResponse) |  |
| GetOrderInfo | [GetOrderInfoRequest](#api-GetOrderInfoRequest) | [GetOrderInfoResponse](#api-GetOrderInfoResponse) |  |
| GetOrderListByLimitAndOffset | [GetOrderListByLimitAndOffsetRequest](#api-GetOrderListByLimitAndOffsetRequest) | [GetOrderListByLimitAndOffsetResponse](#api-GetOrderListByLimitAndOffsetResponse) |  |
| GetOrderListByTimeRange | [GetOrderListByTimeRangeRequest](#api-GetOrderListByTimeRangeRequest) | [GetOrderListByTimeRangeResponse](#api-GetOrderListByTimeRangeResponse) |  |
| GetEventList | [GetEventListRequest](#api-GetEventListRequest) | [GetEventListResponse](#api-GetEventListResponse) |  |

 



<a name="api_merchant-proto"></a>
<p align="right"><a href="#top">Top</a></p>

## api_merchant.proto


 

 

 


<a name="api-BcApiGatewayMerchant"></a>

### BcApiGatewayMerchant
Merchant RPC api gateway

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateWithdrawOrder | [CreateWithdrawOrderRequest](#api-CreateWithdrawOrderRequest) | [CreateWithdrawOrderResponse](#api-CreateWithdrawOrderResponse) |  |
| AddAccountCurrency | [AddAccountCurrencyRequest](#api-AddAccountCurrencyRequest) | [AddAccountCurrencyResponse](#api-AddAccountCurrencyResponse) |  |
| GetDepositAddress | [GetDepositAddressRequest](#api-GetDepositAddressRequest) | [GetDepositAddressResponse](#api-GetDepositAddressResponse) |  |
| GetEstimationFee | [GetEstimationFeeRequest](#api-GetEstimationFeeRequest) | [GetEstimationFeeResponse](#api-GetEstimationFeeResponse) |  |
| GetTransaction | [GetTransactionRequest](#api-GetTransactionRequest) | [GetTransactionResponse](#api-GetTransactionResponse) |  |
| GetWithdrawOrder | [GetWithdrawOrderRequest](#api-GetWithdrawOrderRequest) | [GetWithdrawOrderResponse](#api-GetWithdrawOrderResponse) |  |
| GetOrderListByLimitAndOffset | [GetOrderListByLimitAndOffsetRequest](#api-GetOrderListByLimitAndOffsetRequest) | [GetOrderListByLimitAndOffsetResponse](#api-GetOrderListByLimitAndOffsetResponse) |  |
| GetWallets | [GetWalletsRequest](#api-GetWalletsRequest) | [GetWalletsResponse](#api-GetWalletsResponse) |  |
| GetCurrencies | [GetCurrenciesRequest](#api-GetCurrenciesRequest) | [GetCurrenciesResponse](#api-GetCurrenciesResponse) |  |
| GetWalletBalance | [GetWalletBalanceRequest](#api-GetWalletBalanceRequest) | [GetWalletBalanceResponse](#api-GetWalletBalanceResponse) |  |
| GetOrderInfo | [GetOrderInfoRequest](#api-GetOrderInfoRequest) | [GetOrderInfoResponse](#api-GetOrderInfoResponse) |  |
| GetOrderListByTimeRange | [GetOrderListByTimeRangeRequest](#api-GetOrderListByTimeRangeRequest) | [GetOrderListByTimeRangeResponse](#api-GetOrderListByTimeRangeResponse) |  |
| GetEventList | [GetEventListRequest](#api-GetEventListRequest) | [GetEventListResponse](#api-GetEventListResponse) |  |

 



<a name="messages-proto"></a>
<p align="right"><a href="#top">Top</a></p>

## messages.proto



<a name="api-AccountData"></a>

### AccountData
Data messages


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| Type | [AccountType](#api-AccountType) |  |  |
| Status | [AccountStatus](#api-AccountStatus) |  |  |
| Address | [string](#string) |  |  |






<a name="api-AccountIdentity"></a>

### AccountIdentity
Identity messages


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |






<a name="api-AccountInfo"></a>

### AccountInfo
Info messages


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| AccountIdentity | [AccountIdentity](#api-AccountIdentity) |  |  |
| AccountData | [AccountData](#api-AccountData) |  |  |
| CurrencyCount | [uint32](#uint32) |  |  |
| CurrencyInfoList | [CurrencyInfo](#api-CurrencyInfo) | repeated |  |






<a name="api-AddAccountCurrencyRequest"></a>

### AddAccountCurrencyRequest
Messages (requests and responses) for adding


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| AccountIdentity | [AccountIdentity](#api-AccountIdentity) |  |  |
| CurrencyIdentifier | [CurrencyIdentity](#api-CurrencyIdentity) | repeated |  |






<a name="api-AddAccountCurrencyResponse"></a>

### AddAccountCurrencyResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| AccountInfo | [AccountInfo](#api-AccountInfo) |  |  |
| CurrencyCount | [uint32](#uint32) |  |  |
| CurrencyInfoList | [CurrencyInfo](#api-CurrencyInfo) | repeated |  |






<a name="api-AddressIdentity"></a>

### AddressIdentity



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Address | [string](#string) |  |  |






<a name="api-Amount"></a>

### Amount



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Value | [uint64](#uint64) |  |  |
| Currency | [Currency](#api-Currency) |  |  |
| Metadata | [bytes](#bytes) |  |  |






<a name="api-BcTxIdentity"></a>

### BcTxIdentity



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| TxID | [string](#string) |  |  |
| Meta | [bytes](#bytes) |  |  |






<a name="api-BcTxInfo"></a>

### BcTxInfo



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Network | [Network](#api-Network) |  |  |
| Provider | [Provider](#api-Provider) |  |  |
| BcTxIdentifier | [BcTxIdentity](#api-BcTxIdentity) |  |  |
| Status | [BcTxStatus](#api-BcTxStatus) |  |  |
| Confirmations | [uint64](#uint64) |  |  |
| BlockNumber | [uint64](#uint64) |  |  |
| Operations | [BcTxInfo.OperationsEntry](#api-BcTxInfo-OperationsEntry) | repeated |  |
| RealFee | [uint64](#uint64) |  |  |
| ExplorerURL | [string](#string) |  |  |






<a name="api-BcTxInfo-OperationsEntry"></a>

### BcTxInfo.OperationsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [OperationsList](#api-OperationsList) |  |  |






<a name="api-BcTxOperation"></a>

### BcTxOperation
Operation


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Index | [uint32](#uint32) |  |  |
| Address | [string](#string) |  |  |
| Amount | [uint64](#uint64) |  |  |
| CurrencyIdentifier | [CurrencyIdentity](#api-CurrencyIdentity) |  |  |






<a name="api-CreateAccountRequest"></a>

### CreateAccountRequest







<a name="api-CreateAccountResponse"></a>

### CreateAccountResponse







<a name="api-CreateCurrencyRequest"></a>

### CreateCurrencyRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| Symbol | [string](#string) |  |  |
| ContractAddress | [string](#string) |  |  |
| Link | [string](#string) |  |  |
| SmartContractABI | [bytes](#bytes) |  |  |
| Decimals | [uint32](#uint32) |  |  |
| MinWithdrawalAmount | [uint64](#uint64) |  |  |
| MinDepositAmount | [uint64](#uint64) |  |  |
| MinMoveToHotAmount | [uint64](#uint64) |  |  |
| MinGasLimit | [uint64](#uint64) |  |  |






<a name="api-CreateCurrencyResponse"></a>

### CreateCurrencyResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| CurrencyInfo | [CurrencyInfo](#api-CurrencyInfo) |  |  |






<a name="api-CreateMerchantRequest"></a>

### CreateMerchantRequest
Messages (requests and responses) for creating






<a name="api-CreateMerchantResponse"></a>

### CreateMerchantResponse







<a name="api-CreateWalletRequest"></a>

### CreateWalletRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| MerchantIdentifier | [MerchantIdentity](#api-MerchantIdentity) | optional |  |
| CurrencyIdentifier | [CurrencyIdentity](#api-CurrencyIdentity) | repeated |  |






<a name="api-CreateWalletResponse"></a>

### CreateWalletResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| WalletInfo | [WalletInfo](#api-WalletInfo) |  |  |
| AccountInfo | [AccountInfo](#api-AccountInfo) |  |  |
| CurrencyCount | [uint32](#uint32) |  |  |
| CurrencyInfoList | [CurrencyInfo](#api-CurrencyInfo) | repeated |  |






<a name="api-CreateWithdrawOrderRequest"></a>

### CreateWithdrawOrderRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| CurrencyIdentifier | [CurrencyIdentity](#api-CurrencyIdentity) |  |  |
| EstimateFeeIdentifier | [EstimationFeeIdentity](#api-EstimationFeeIdentity) |  |  |
| AddressToIdentifier | [AddressIdentity](#api-AddressIdentity) |  |  |
| ExternalOrderIdentifier | [string](#string) |  |  |
| Amount | [uint64](#uint64) |  |  |
| ConfirmationsCount | [uint32](#uint32) |  |  |
| CallbackURL | [string](#string) |  |  |






<a name="api-CreateWithdrawOrderResponse"></a>

### CreateWithdrawOrderResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| OrderIdentifier | [OrderIdentify](#api-OrderIdentify) |  |  |






<a name="api-Currency"></a>

### Currency



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Symbol | [string](#string) |  |  |
| Decimals | [int32](#int32) |  |  |
| Name | [string](#string) |  |  |






<a name="api-CurrencyData"></a>

### CurrencyData



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| Symbol | [string](#string) |  |  |
| Decimals | [uint32](#uint32) |  |  |






<a name="api-CurrencyIdentity"></a>

### CurrencyIdentity



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |






<a name="api-CurrencyIdentityResponse"></a>

### CurrencyIdentityResponse
Identity response messages


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |
| Symbol | [string](#string) |  |  |
| Decimals | [uint32](#uint32) |  |  |
| Metadata | [bytes](#bytes) |  |  |






<a name="api-CurrencyInfo"></a>

### CurrencyInfo



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| CurrencyIdentity | [CurrencyIdentity](#api-CurrencyIdentity) |  |  |
| CurrencyData | [CurrencyData](#api-CurrencyData) |  |  |
| TokenData | [TokenData](#api-TokenData) | optional |  |






<a name="api-EstimatedTime"></a>

### EstimatedTime



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Min | [int64](#int64) |  |  |
| Max | [int64](#int64) |  |  |






<a name="api-EstimationFeeIdentify"></a>

### EstimationFeeIdentify



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |






<a name="api-EstimationFeeIdentity"></a>

### EstimationFeeIdentity



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |






<a name="api-EventIdentity"></a>

### EventIdentity



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |






<a name="api-EventInformation"></a>

### EventInformation



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Network | [Network](#api-Network) |  |  |
| Provider | [Provider](#api-Provider) |  |  |
| MerchantIdentifier | [MerchantIdentity](#api-MerchantIdentity) |  |  |
| OrderIdentifier | [OrderIdentify](#api-OrderIdentify) |  |  |
| EventIdentifier | [EventIdentity](#api-EventIdentity) |  |  |
| Type | [string](#string) |  |  |
| Producer | [string](#string) |  |  |
| Message | [string](#string) |  |  |






<a name="api-FeeInfo"></a>

### FeeInfo



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| FeeInfoIdentifier | [string](#string) |  |  |
| CurrencyIdentifier | [CurrencyIdentity](#api-CurrencyIdentity) |  |  |
| FeeLevel | [FeeLevel](#api-FeeLevel) |  |  |
| Amount | [uint64](#uint64) |  |  |
| ExpirationTime | [EstimatedTime](#api-EstimatedTime) |  |  |






<a name="api-GetAllWalletsRequest"></a>

### GetAllWalletsRequest







<a name="api-GetAllWalletsResponse"></a>

### GetAllWalletsResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| WalletCount | [uint32](#uint32) |  |  |
| WalletInfoList | [WalletInfo](#api-WalletInfo) | repeated |  |






<a name="api-GetCurrenciesRequest"></a>

### GetCurrenciesRequest







<a name="api-GetCurrenciesResponse"></a>

### GetCurrenciesResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| CurrencyCount | [uint64](#uint64) |  |  |
| CurrencyInfo | [CurrencyInfo](#api-CurrencyInfo) | repeated |  |






<a name="api-GetDepositAddressRequest"></a>

### GetDepositAddressRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| CurrencyIdentifier | [CurrencyIdentity](#api-CurrencyIdentity) |  |  |






<a name="api-GetDepositAddressResponse"></a>

### GetDepositAddressResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| AddressToIdentifier | [AddressIdentity](#api-AddressIdentity) |  |  |
| NetworkIdentifier | [Network](#api-Network) |  |  |






<a name="api-GetEstimationFeeRequest"></a>

### GetEstimationFeeRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| CurrencyIdentifier | [CurrencyIdentity](#api-CurrencyIdentity) |  |  |
| AddressToIdentifier | [AddressIdentity](#api-AddressIdentity) |  |  |
| Amount | [uint64](#uint64) |  |  |






<a name="api-GetEstimationFeeResponse"></a>

### GetEstimationFeeResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| EstimationFeeIdentifier | [EstimationFeeIdentity](#api-EstimationFeeIdentity) |  |  |
| FeeInfo | [FeeInfo](#api-FeeInfo) | repeated |  |






<a name="api-GetEventListRequest"></a>

### GetEventListRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| OrderIdentifier | [OrderIdentify](#api-OrderIdentify) |  |  |
| MerchantIdentifier | [MerchantIdentity](#api-MerchantIdentity) | optional |  |






<a name="api-GetEventListResponse"></a>

### GetEventListResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| EventsCount | [uint32](#uint32) |  |  |
| EventInfoList | [EventInformation](#api-EventInformation) | repeated |  |






<a name="api-GetOrderInfoRequest"></a>

### GetOrderInfoRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| OrderIdentifier | [OrderIdentify](#api-OrderIdentify) |  |  |
| MerchantIdentifier | [MerchantIdentity](#api-MerchantIdentity) | optional |  |






<a name="api-GetOrderInfoResponse"></a>

### GetOrderInfoResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| OrderInfo | [OrderInfo](#api-OrderInfo) |  |  |






<a name="api-GetOrderListByLimitAndOffsetRequest"></a>

### GetOrderListByLimitAndOffsetRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| Limit | [uint32](#uint32) |  |  |
| Offset | [uint32](#uint32) |  |  |
| MerchantIdentifier | [MerchantIdentity](#api-MerchantIdentity) | optional |  |






<a name="api-GetOrderListByLimitAndOffsetResponse"></a>

### GetOrderListByLimitAndOffsetResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| OrdersCount | [uint32](#uint32) |  |  |
| OrderInfoList | [OrderInfo](#api-OrderInfo) | repeated |  |






<a name="api-GetOrderListByTimeRangeRequest"></a>

### GetOrderListByTimeRangeRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| TimeRange | [TimeRangeRequest](#api-TimeRangeRequest) |  |  |
| MerchantIdentifier | [MerchantIdentity](#api-MerchantIdentity) | optional |  |






<a name="api-GetOrderListByTimeRangeResponse"></a>

### GetOrderListByTimeRangeResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| OrdersCount | [uint32](#uint32) |  |  |
| OrderInfoList | [OrderInfo](#api-OrderInfo) | repeated |  |






<a name="api-GetTransactionRequest"></a>

### GetTransactionRequest







<a name="api-GetTransactionResponse"></a>

### GetTransactionResponse







<a name="api-GetWalletBalanceRequest"></a>

### GetWalletBalanceRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| CurrencyIdentifier | [CurrencyIdentity](#api-CurrencyIdentity) |  |  |






<a name="api-GetWalletBalanceResponse"></a>

### GetWalletBalanceResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| AddressToIdentifier | [AddressIdentity](#api-AddressIdentity) |  |  |
| BalanceInfo | [Amount](#api-Amount) |  |  |






<a name="api-GetWalletsRequest"></a>

### GetWalletsRequest
Messages (requests and responses) for retrieving


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| MerchantIdentifier | [MerchantIdentity](#api-MerchantIdentity) | optional |  |






<a name="api-GetWalletsResponse"></a>

### GetWalletsResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| WalletCount | [uint32](#uint32) |  |  |
| WalletInfoList | [WalletInfo](#api-WalletInfo) | repeated |  |






<a name="api-GetWithdrawOrderRequest"></a>

### GetWithdrawOrderRequest







<a name="api-GetWithdrawOrderResponse"></a>

### GetWithdrawOrderResponse







<a name="api-MerchantIdentity"></a>

### MerchantIdentity



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |






<a name="api-OperationsList"></a>

### OperationsList



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Operations | [BcTxOperation](#api-BcTxOperation) | repeated |  |






<a name="api-OrderIdentify"></a>

### OrderIdentify



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |






<a name="api-OrderIdentityResponse"></a>

### OrderIdentityResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |
| ExternalOrderUUID | [string](#string) |  |  |
| ProviderOrderUUID | [string](#string) |  |  |






<a name="api-OrderInfo"></a>

### OrderInfo



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Network | [Network](#api-Network) |  |  |
| Provider | [Provider](#api-Provider) |  |  |
| WalletIdentifier | [WalletIdentity](#api-WalletIdentity) |  |  |
| AccountIdentifier | [AccountIdentity](#api-AccountIdentity) |  |  |
| MerchantIdentifier | [MerchantIdentity](#api-MerchantIdentity) |  |  |
| AddressIdentifier | [AddressIdentity](#api-AddressIdentity) |  |  |
| EstimationFeeIdentifier | [EstimationFeeIdentify](#api-EstimationFeeIdentify) |  |  |
| CurrencyIdentifier | [CurrencyIdentityResponse](#api-CurrencyIdentityResponse) |  |  |
| OrderIdentifier | [OrderIdentityResponse](#api-OrderIdentityResponse) |  |  |
| Type | [OrderType](#api-OrderType) |  |  |
| Status | [OrderStatus](#api-OrderStatus) |  |  |
| Amount | [uint64](#uint64) |  |  |
| RealFee | [uint64](#uint64) |  |  |
| CreatedAt | [uint64](#uint64) |  |  |
| BcTxList | [BcTxInfo](#api-BcTxInfo) | repeated |  |






<a name="api-TimeRangeRequest"></a>

### TimeRangeRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| Start | [uint64](#uint64) |  |  |
| End | [uint64](#uint64) |  |  |






<a name="api-TokenData"></a>

### TokenData



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| ContractAddress | [string](#string) |  |  |
| ContractAddressRaw | [bytes](#bytes) |  |  |
| AssetType | [string](#string) |  |  |






<a name="api-WalletData"></a>

### WalletData



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| NetworkIdentifier | [Network](#api-Network) |  |  |
| ProviderIdentifier | [Provider](#api-Provider) |  |  |
| Type | [WalletType](#api-WalletType) |  |  |
| Status | [WalletStatus](#api-WalletStatus) |  |  |






<a name="api-WalletIdentity"></a>

### WalletIdentity



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| UUID | [string](#string) |  |  |






<a name="api-WalletInfo"></a>

### WalletInfo



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| WalletIdentity | [WalletIdentity](#api-WalletIdentity) |  |  |
| WalletData | [WalletData](#api-WalletData) |  |  |
| AccountCount | [uint32](#uint32) |  |  |
| AccountInfoList | [AccountInfo](#api-AccountInfo) | repeated |  |





 


<a name="api-AccountStatus"></a>

### AccountStatus


| Name | Number | Description |
| ---- | ------ | ----------- |
| ACCOUNT_STATUS_PLACEHOLDER | 0 |  |
| ACCOUNT_STATUS_ENABLED | 1 |  |
| ACCOUNT_STATUS_DISABLED | 2 |  |



<a name="api-AccountType"></a>

### AccountType


| Name | Number | Description |
| ---- | ------ | ----------- |
| ACCOUNT_TYPE_PLACEHOLDER | 0 |  |
| ACCOUNT_TYPE_PRIVATE_KEY | 1 |  |
| ACCOUNT_TYPE_HDWALLET | 2 |  |
| ACCOUNT_TYPE_MPC | 3 |  |



<a name="api-BcTxStatus"></a>

### BcTxStatus


| Name | Number | Description |
| ---- | ------ | ----------- |
| PLACEHOLDER_BC_TX_STATUS | 0 |  |
| BC_TX_IN_MINING | 1 |  |
| BC_TX_SUCCESS | 2 |  |
| BC_TX_EXECUTION_FAILED | 3 |  |
| BC_TX_WAITING_FOR_CONFIRMATIONS | 4 |  |



<a name="api-FeeLevel"></a>

### FeeLevel


| Name | Number | Description |
| ---- | ------ | ----------- |
| PLACEHOLDER_FEE_LEVEL | 0 |  |
| FAST | 1 |  |
| MEDIUM | 2 |  |
| SLOW | 3 |  |



<a name="api-Network"></a>

### Network
Enums

| Name | Number | Description |
| ---- | ------ | ----------- |
| PLACEHOLDER_NETWORK | 0 |  |
| ETHEREUM | 1 |  |
| BITCOIN | 2 |  |
| TRON | 3 |  |
| BINANCE_SMART_CHAIN | 4 |  |
| ARBITRUM | 5 |  |
| OPTIMISTIC | 6 |  |



<a name="api-OrderStatus"></a>

### OrderStatus


| Name | Number | Description |
| ---- | ------ | ----------- |
| PLACEHOLDER_ORDER_STATUS | 0 |  |
| ACCEPTED | 1 |  |
| CREATED | 2 |  |
| PROCESSING | 3 |  |
| CONFIRMED | 4 |  |
| FAILED | 5 |  |
| SUCCESS | 6 |  |
| CANCELED | 7 |  |



<a name="api-OrderType"></a>

### OrderType


| Name | Number | Description |
| ---- | ------ | ----------- |
| PLACEHOLDER_ORDER_TYPE | 0 |  |
| WITHDRAW | 1 |  |
| DEPOSIT | 2 |  |



<a name="api-Provider"></a>

### Provider


| Name | Number | Description |
| ---- | ------ | ----------- |
| PLACEHOLDER_PROVIDER | 0 |  |
| CRYPTOBUNDLE | 1 |  |
| FIREBLOCKS | 2 |  |
| COPER | 3 |  |
| BITGO | 4 |  |



<a name="api-WalletStatus"></a>

### WalletStatus


| Name | Number | Description |
| ---- | ------ | ----------- |
| WALLET_STATUS_PLACEHOLDER | 0 |  |
| WALLET_STATUS_ENABLED | 1 |  |
| WALLET_STATUS_DISABLED | 2 |  |



<a name="api-WalletType"></a>

### WalletType


| Name | Number | Description |
| ---- | ------ | ----------- |
| WALLET_TYPE_PLACEHOLDER | 0 |  |
| WALLET_TYPE_PRIVATE_KEY | 1 |  |
| WALLET_TYPE_HDWALLET | 2 |  |
| WALLET_TYPE_MPC | 3 |  |


 

 

 



## Scalar Value Types

| .proto Type | Notes | C++ | Java | Python | Go | C# | PHP | Ruby |
| ----------- | ----- | --- | ---- | ------ | -- | -- | --- | ---- |
| <a name="double" /> double |  | double | double | float | float64 | double | float | Float |
| <a name="float" /> float |  | float | float | float | float32 | float | float | Float |
| <a name="int32" /> int32 | Uses variable-length encoding. Inefficient for encoding negative numbers – if your field is likely to have negative values, use sint32 instead. | int32 | int | int | int32 | int | integer | Bignum or Fixnum (as required) |
| <a name="int64" /> int64 | Uses variable-length encoding. Inefficient for encoding negative numbers – if your field is likely to have negative values, use sint64 instead. | int64 | long | int/long | int64 | long | integer/string | Bignum |
| <a name="uint32" /> uint32 | Uses variable-length encoding. | uint32 | int | int/long | uint32 | uint | integer | Bignum or Fixnum (as required) |
| <a name="uint64" /> uint64 | Uses variable-length encoding. | uint64 | long | int/long | uint64 | ulong | integer/string | Bignum or Fixnum (as required) |
| <a name="sint32" /> sint32 | Uses variable-length encoding. Signed int value. These more efficiently encode negative numbers than regular int32s. | int32 | int | int | int32 | int | integer | Bignum or Fixnum (as required) |
| <a name="sint64" /> sint64 | Uses variable-length encoding. Signed int value. These more efficiently encode negative numbers than regular int64s. | int64 | long | int/long | int64 | long | integer/string | Bignum |
| <a name="fixed32" /> fixed32 | Always four bytes. More efficient than uint32 if values are often greater than 2^28. | uint32 | int | int | uint32 | uint | integer | Bignum or Fixnum (as required) |
| <a name="fixed64" /> fixed64 | Always eight bytes. More efficient than uint64 if values are often greater than 2^56. | uint64 | long | int/long | uint64 | ulong | integer/string | Bignum |
| <a name="sfixed32" /> sfixed32 | Always four bytes. | int32 | int | int | int32 | int | integer | Bignum or Fixnum (as required) |
| <a name="sfixed64" /> sfixed64 | Always eight bytes. | int64 | long | int/long | int64 | long | integer/string | Bignum |
| <a name="bool" /> bool |  | bool | boolean | boolean | bool | bool | boolean | TrueClass/FalseClass |
| <a name="string" /> string | A string must always contain UTF-8 encoded or 7-bit ASCII text. | string | String | str/unicode | string | string | string | String (UTF-8) |
| <a name="bytes" /> bytes | May contain any arbitrary sequence of bytes. | string | ByteString | str | []byte | ByteString | string | String (ASCII-8BIT) |

