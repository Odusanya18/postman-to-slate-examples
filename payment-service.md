---
title: API Reference
language_tabs:
  - shell
  - php
  - java
  - python
toc_footers:
includes:
    - errors
search: true
---
# Introduction

```
We have language bindings in php, java, python! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.
```

### Version
Version: 2.0

# Get ewallet payment instrument with user access token


null

## Get ewallet Payment Instrument with user access token
```shell
curl "/api/v1/ewallet/instruments" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetEwalletPaymentInstrumentWithUserAccessTokenApi();
api.get_api_v1_ewallet_instruments(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetEwalletPaymentInstrumentWithUserAccessTokenApi;

ApiClient apiClient = new ApiClient();

GetEwalletPaymentInstrumentWithUserAccessTokenApi api = new GetEwalletPaymentInstrumentWithUserAccessTokenApi(apiClient);
api.getApiV1EwalletInstruments(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetEwalletPaymentInstrumentWithUserAccessTokenApi($api_client);
$api->getApiV1EwalletInstruments($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`GET /api/v1/ewallet/instruments`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Paying with user access token and payment identifier


null

## Paying with user access token and payment identifier
```shell
curl "/api/v1/ewallet/purchases" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PayingWithUserAccessTokenAndPaymentIdentifierApi();
api.post_api_v1_ewallet_purchases(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PayingWithUserAccessTokenAndPaymentIdentifierApi;

ApiClient apiClient = new ApiClient();

PayingWithUserAccessTokenAndPaymentIdentifierApi api = new PayingWithUserAccessTokenAndPaymentIdentifierApi(apiClient);
api.postApiV1EwalletPurchases(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PayingWithUserAccessTokenAndPaymentIdentifierApi($api_client);
$api->postApiV1EwalletPurchases($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v1/ewallet/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Ewallet service status


null

## Ewallet Service Status
```shell
curl "/api/v1/ewallet/status" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.EwalletServiceStatusApi();
api.get_api_v1_ewallet_status(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.EwalletServiceStatusApi;

ApiClient apiClient = new ApiClient();

EwalletServiceStatusApi api = new EwalletServiceStatusApi(apiClient);
api.getApiV1EwalletStatus(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\EwalletServiceStatusApi($api_client);
$api->getApiV1EwalletStatus($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`GET /api/v1/ewallet/status`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Generate processor access token


null

# Purchase service status


null

## Purchase Service Status
```shell
curl "/api/v1/purchases/status" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PurchaseServiceStatusApi();
api.get_api_v1_purchases_status(content_type, body, signature, signature_method, timestamp, nonce, authorization, transaction_ref);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PurchaseServiceStatusApi;

ApiClient apiClient = new ApiClient();

PurchaseServiceStatusApi api = new PurchaseServiceStatusApi(apiClient);
api.getApiV1PurchasesStatus(contentType, body, signature, signatureMethod, timestamp, nonce, authorization, transactionRef);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PurchaseServiceStatusApi($api_client);
$api->getApiV1PurchasesStatus($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization, $transaction_ref);




```

### HTTP Request
`GET /api/v1/purchases/status`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||
|transactionRef|false|string||


### Responses for status codes
|default|
|----|
||


# Get user access token


null

# Processor payment 


null

## Processor Payment 
```shell
curl "/api/v1/purchases" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ProcessorPaymentApi();
api.post_api_v1_purchases(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ProcessorPaymentApi;

ApiClient apiClient = new ApiClient();

ProcessorPaymentApi api = new ProcessorPaymentApi(apiClient);
api.postApiV1Purchases(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ProcessorPaymentApi($api_client);
$api->postApiV1Purchases($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v1/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Get transaction status


null

# Processor otp complete transaction


null

## Processor OTP complete transaction
```shell
curl "/api/v1/purchases/otps/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ProcessorOTPCompleteTransactionApi();
api.post_api_v1_purchases_otps_auths(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ProcessorOTPCompleteTransactionApi;

ApiClient apiClient = new ApiClient();

ProcessorOTPCompleteTransactionApi api = new ProcessorOTPCompleteTransactionApi(apiClient);
api.postApiV1PurchasesOtpsAuths(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ProcessorOTPCompleteTransactionApi($api_client);
$api->postApiV1PurchasesOtpsAuths($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v1/purchases/otps/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Processor validate card


null

## Processor validate card
```shell
curl "/api/v1/purchases/validations" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ProcessorValidateCardApi();
api.post_api_v1_purchases_validations(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ProcessorValidateCardApi;

ApiClient apiClient = new ApiClient();

ProcessorValidateCardApi api = new ProcessorValidateCardApi(apiClient);
api.postApiV1PurchasesValidations(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ProcessorValidateCardApi($api_client);
$api->postApiV1PurchasesValidations($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v1/purchases/validations`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Get user access token by merchant (ewallet)


null

# Gateway payment without otp


null

## Gateway Payment without OTP
```shell
curl "/api/v1/payment/gateway/purchase" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GatewayPaymentWithoutOTPApi();
api.post_api_v1_payment_gateway_purchase(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GatewayPaymentWithoutOTPApi;

ApiClient apiClient = new ApiClient();

GatewayPaymentWithoutOTPApi api = new GatewayPaymentWithoutOTPApi(apiClient);
api.postApiV1PaymentGatewayPurchase(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GatewayPaymentWithoutOTPApi($api_client);
$api->postApiV1PaymentGatewayPurchase($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v1/payment/gateway/purchase`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Webpay


null

## Webpay
```shell
curl "/webpay/api/v2/pay.json" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.WebpayApi();
api.post_webpay_api_v2_pay_json(content_type, body, authorization, terminal_id);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.WebpayApi;

ApiClient apiClient = new ApiClient();

WebpayApi api = new WebpayApi(apiClient);
api.postWebpayApiV2PayJson(contentType, body, authorization, terminalId);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\WebpayApi($api_client);
$api->postWebpayApiV2PayJson($content_type, $body, $authorization, $terminal_id);




```

### HTTP Request
`POST /webpay/api/v2/pay.json`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||
|TerminalId|true|string||


### Responses for status codes
|default|
|----|
||


# Payment v2


null

## Payment V2
```shell
curl "/api/v2/purchases" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentVApi();
api.post_api_v2_purchases(signature, signature_method, timestamp, nonce, authorization, content_type, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentVApi;

ApiClient apiClient = new ApiClient();

PaymentVApi api = new PaymentVApi(apiClient);
api.postApiV2Purchases(signature, signatureMethod, timestamp, nonce, authorization, contentType, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentVApi($api_client);
$api->postApiV2Purchases($signature, $signature_method, $timestamp, $nonce, $authorization, $content_type, $body);




```

### HTTP Request
`POST /api/v2/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||
|Content-Type|true|string||


### Responses for status codes
|default|
|----|
||


# Payment otp v2


null

# Validation v2


null

## Validation V2
```shell
curl "/api/v2/purchases/validations" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidationVApi();
api.post_api_v2_purchases_validations(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidationVApi;

ApiClient apiClient = new ApiClient();

ValidationVApi api = new ValidationVApi(apiClient);
api.postApiV2PurchasesValidations(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidationVApi($api_client);
$api->postApiV2PurchasesValidations($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v2/purchases/validations`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Validation otp v2


null

# Payment v2 status


null

## Payment V2 Status
```shell
curl "/api/v1/purchases" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentVStatusApi();
api.get_api_v1_purchases(content_type, body, signature, signature_method, timestamp, nonce, authorization, transaction_ref, amount, transaction_ref2, amount2);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentVStatusApi;

ApiClient apiClient = new ApiClient();

PaymentVStatusApi api = new PaymentVStatusApi(apiClient);
api.getApiV1Purchases(contentType, body, signature, signatureMethod, timestamp, nonce, authorization, transactionRef, amount, transactionRef2, amount2);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentVStatusApi($api_client);
$api->getApiV1Purchases($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization, $transaction_ref, $amount, $transaction_ref2, $amount2);




```

### HTTP Request
`GET /api/v1/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||
|transactionRef|true|string||
|amount|true|string||


### Query Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|transactionRef|false|string||
|amount|false|string||


### Responses for status codes
|default|
|----|
||


# Payment otp v2 cardinal


null

## Payment OTP V2 Cardinal
```shell
curl "/api/v2/purchases/otps/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentOTPVCardinalApi();
api.post_api_v2_purchases_otps_auths(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentOTPVCardinalApi;

ApiClient apiClient = new ApiClient();

PaymentOTPVCardinalApi api = new PaymentOTPVCardinalApi(apiClient);
api.postApiV2PurchasesOtpsAuths(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentOTPVCardinalApi($api_client);
$api->postApiV2PurchasesOtpsAuths($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v2/purchases/otps/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Validation otp v2 cardinal


null

## Validation OTP V2 Cardinal
```shell
curl "/api/v2/purchases/validations/otps/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidationOTPVCardinalApi();
api.post_api_v2_purchases_validations_otps_auths(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidationOTPVCardinalApi;

ApiClient apiClient = new ApiClient();

ValidationOTPVCardinalApi api = new ValidationOTPVCardinalApi(apiClient);
api.postApiV2PurchasesValidationsOtpsAuths(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidationOTPVCardinalApi($api_client);
$api->postApiV2PurchasesValidationsOtpsAuths($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v2/purchases/validations/otps/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Generate user access token 


null

## Generate User Access Token 
```shell
curl "/passport/oauth/token" -X POST
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GenerateUserAccessTokenApi();
api.post_passport_oauth_token(authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GenerateUserAccessTokenApi;

ApiClient apiClient = new ApiClient();

GenerateUserAccessTokenApi api = new GenerateUserAccessTokenApi(apiClient);
api.postPassportOauthToken(authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GenerateUserAccessTokenApi($api_client);
$api->postPassportOauthToken($authorization);




```

### HTTP Request
`POST /passport/oauth/token`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Payment otp auto enroll


null

## Payment OTP Auto Enroll
```shell
curl "/api/v2/purchases/otps/enrollments" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentOTPAutoEnrollApi();
api.post_api_v2_purchases_otps_enrollments(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentOTPAutoEnrollApi;

ApiClient apiClient = new ApiClient();

PaymentOTPAutoEnrollApi api = new PaymentOTPAutoEnrollApi(apiClient);
api.postApiV2PurchasesOtpsEnrollments(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentOTPAutoEnrollApi($api_client);
$api->postApiV2PurchasesOtpsEnrollments($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v2/purchases/otps/enrollments`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Payment v2 status new


null

## Payment V2 Status New
```shell
curl "/api/v2/purchases" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentVStatusNewApi();
api.get_api_v2_purchases(content_type, body, signature, signature_method, timestamp, nonce, authorization, transaction_ref, amount);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentVStatusNewApi;

ApiClient apiClient = new ApiClient();

PaymentVStatusNewApi api = new PaymentVStatusNewApi(apiClient);
api.getApiV2Purchases(contentType, body, signature, signatureMethod, timestamp, nonce, authorization, transactionRef, amount);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentVStatusNewApi($api_client);
$api->getApiV2Purchases($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization, $transaction_ref, $amount);




```

### HTTP Request
`GET /api/v2/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Query Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|transactionRef|true|string||
|amount|true|string||


### Responses for status codes
|default|
|----|
||


# Validaiton otp auto enroll


null

## Validaiton OTP Auto Enroll
```shell
curl "/api/v2/purchases/validations/otps/enrollments" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidaitonOTPAutoEnrollApi();
api.post_api_v2_purchases_validations_otps_enrollments(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidaitonOTPAutoEnrollApi;

ApiClient apiClient = new ApiClient();

ValidaitonOTPAutoEnrollApi api = new ValidaitonOTPAutoEnrollApi(apiClient);
api.postApiV2PurchasesValidationsOtpsEnrollments(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidaitonOTPAutoEnrollApi($api_client);
$api->postApiV2PurchasesValidationsOtpsEnrollments($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v2/purchases/validations/otps/enrollments`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Validation recurrent


null

## Validation Recurrent
```shell
curl "/api/v2/purchases/validations/recurrents" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidationRecurrentApi();
api.post_api_v2_purchases_validations_recurrents(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidationRecurrentApi;

ApiClient apiClient = new ApiClient();

ValidationRecurrentApi api = new ValidationRecurrentApi(apiClient);
api.postApiV2PurchasesValidationsRecurrents(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidationRecurrentApi($api_client);
$api->postApiV2PurchasesValidationsRecurrents($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v2/purchases/validations/recurrents`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Http://localhost:19080/api/v1/ewallet/auths


null

## http://localhost:19080/api/v1/ewallet/auths
```shell
curl "/api/v1/ewallet/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.HttplocalhostapivewalletauthsApi();
api.post_api_v1_ewallet_auths(content_type, body, signature, signature_method, timestamp, nonce, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.HttplocalhostapivewalletauthsApi;

ApiClient apiClient = new ApiClient();

HttplocalhostapivewalletauthsApi api = new HttplocalhostapivewalletauthsApi(apiClient);
api.postApiV1EwalletAuths(contentType, body, signature, signatureMethod, timestamp, nonce, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\HttplocalhostapivewalletauthsApi($api_client);
$api->postApiV1EwalletAuths($content_type, $body, $signature, $signature_method, $timestamp, $nonce, $authorization);




```

### HTTP Request
`POST /api/v1/ewallet/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



Get Wallet Payment Methods




Process finished with exit code 0
