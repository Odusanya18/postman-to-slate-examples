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

# Status


status additional description here

## null
```shell
curl "/health" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.StatusApi();
api.get_health(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.StatusApi;

ApiClient apiClient = new ApiClient();

StatusApi api = new StatusApi(apiClient);
api.getHealth(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\StatusApi($api_client);
$api->getHealth($content_type, $authorization, $body);




```

### HTTP Request
`GET /health`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Tokenise


tokenise additional description here

## null
```shell
curl "/api/v1/tokenise" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.TokeniseApi();
api.post_api_v1_tokenise(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.TokeniseApi;

ApiClient apiClient = new ApiClient();

TokeniseApi api = new TokeniseApi(apiClient);
api.postApiV1Tokenise(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\TokeniseApi($api_client);
$api->postApiV1Tokenise($content_type, $authorization, $body);




```

### HTTP Request
`POST /api/v1/tokenise`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# De tokenise


de-tokenise additional description here

## null
```shell
curl "/api/v1/de-tokenise" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.DetokeniseApi();
api.post_api_v1_de_tokenise(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.DetokeniseApi;

ApiClient apiClient = new ApiClient();

DetokeniseApi api = new DetokeniseApi(apiClient);
api.postApiV1DeTokenise(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\DetokeniseApi($api_client);
$api->postApiV1DeTokenise($content_type, $authorization, $body);




```

### HTTP Request
`POST /api/v1/de-tokenise`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Providers


get all providers

## get all providers
```shell
curl "/api/v1/providers" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ProvidersApi();
api.get_api_v1_providers(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ProvidersApi;

ApiClient apiClient = new ApiClient();

ProvidersApi api = new ProvidersApi(apiClient);
api.getApiV1Providers(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ProvidersApi($api_client);
$api->getApiV1Providers($content_type, $authorization, $body);




```

### HTTP Request
`GET /api/v1/providers`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



get all providers

# Create provider


create provider

## create provider
```shell
curl "/api/v1/providers" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.CreateProviderApi();
api.post_api_v1_providers(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.CreateProviderApi;

ApiClient apiClient = new ApiClient();

CreateProviderApi api = new CreateProviderApi(apiClient);
api.postApiV1Providers(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\CreateProviderApi($api_client);
$api->postApiV1Providers($content_type, $authorization, $body);




```

### HTTP Request
`POST /api/v1/providers`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



create provider

# Delete provider


delete provider

## delete provider
```shell
curl "/api/v1/providers/55bf414815cc6b04ce2717e2" -X DELETE -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.DeleteProviderApi();
api.delete_api_v1_providers55bf414815cc6b04ce2717e2(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.DeleteProviderApi;

ApiClient apiClient = new ApiClient();

DeleteProviderApi api = new DeleteProviderApi(apiClient);
api.deleteApiV1Providers55bf414815cc6b04ce2717e2(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\DeleteProviderApi($api_client);
$api->deleteApiV1Providers55bf414815cc6b04ce2717e2($content_type, $authorization, $body);




```

### HTTP Request
`DELETE /api/v1/providers/55bf414815cc6b04ce2717e2`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



delete provider

# Update provider


update provider

## update provider
```shell
curl "/api/v1/providers" -X PUT -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.UpdateProviderApi();
api.put_api_v1_providers(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.UpdateProviderApi;

ApiClient apiClient = new ApiClient();

UpdateProviderApi api = new UpdateProviderApi(apiClient);
api.putApiV1Providers(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\UpdateProviderApi($api_client);
$api->putApiV1Providers($content_type, $authorization, $body);




```

### HTTP Request
`PUT /api/v1/providers`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



update provider

# Get provider


get provider

## get provider
```shell
curl "/api/v1/providers/55bf47af15cc6b05a0c16062" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetProviderApi();
api.get_api_v1_providers55bf47af15cc6b05a0c16062(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetProviderApi;

ApiClient apiClient = new ApiClient();

GetProviderApi api = new GetProviderApi(apiClient);
api.getApiV1Providers55bf47af15cc6b05a0c16062(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetProviderApi($api_client);
$api->getApiV1Providers55bf47af15cc6b05a0c16062($content_type, $authorization, $body);




```

### HTTP Request
`GET /api/v1/providers/55bf47af15cc6b05a0c16062`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



get provider

# Create token requestor


create token requestor

## create token requestor
```shell
curl "/api/v1/requestors/" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.CreateTokenRequestorApi();
api.post_api_v1_requestors(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.CreateTokenRequestorApi;

ApiClient apiClient = new ApiClient();

CreateTokenRequestorApi api = new CreateTokenRequestorApi(apiClient);
api.postApiV1Requestors(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\CreateTokenRequestorApi($api_client);
$api->postApiV1Requestors($content_type, $authorization, $body);




```

### HTTP Request
`POST /api/v1/requestors/`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



create token requestor

# Get token requestor


get token requestor

## get token requestor
```shell
curl "/api/v1/requestors/" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetTokenRequestorApi();
api.get_api_v1_requestors(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetTokenRequestorApi;

ApiClient apiClient = new ApiClient();

GetTokenRequestorApi api = new GetTokenRequestorApi(apiClient);
api.getApiV1Requestors(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetTokenRequestorApi($api_client);
$api->getApiV1Requestors($content_type, $authorization, $body);




```

### HTTP Request
`GET /api/v1/requestors/`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



get token requestor

# Get token requestors


get token requestors

## get token requestors
```shell
curl "/api/v1/requestors" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetTokenRequestorsApi();
api.get_api_v1_requestors(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetTokenRequestorsApi;

ApiClient apiClient = new ApiClient();

GetTokenRequestorsApi api = new GetTokenRequestorsApi(apiClient);
api.getApiV1Requestors(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetTokenRequestorsApi($api_client);
$api->getApiV1Requestors($content_type, $authorization, $body);




```

### HTTP Request
`GET /api/v1/requestors`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



get token requestors

# Update token requestor


update token requestor

## update token requestor
```shell
curl "/api/v1/requestors" -X PUT -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.UpdateTokenRequestorApi();
api.put_api_v1_requestors(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.UpdateTokenRequestorApi;

ApiClient apiClient = new ApiClient();

UpdateTokenRequestorApi api = new UpdateTokenRequestorApi(apiClient);
api.putApiV1Requestors(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\UpdateTokenRequestorApi($api_client);
$api->putApiV1Requestors($content_type, $authorization, $body);




```

### HTTP Request
`PUT /api/v1/requestors`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



update token requestor

# Delete token requestor


delete token requestor

## delete token requestor
```shell
curl "/api/v1/requestors/55c8705515cc6b2f785b1387" -X DELETE -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.DeleteTokenRequestorApi();
api.delete_api_v1_requestors55c8705515cc6b2f785b1387(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.DeleteTokenRequestorApi;

ApiClient apiClient = new ApiClient();

DeleteTokenRequestorApi api = new DeleteTokenRequestorApi(apiClient);
api.deleteApiV1Requestors55c8705515cc6b2f785b1387(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\DeleteTokenRequestorApi($api_client);
$api->deleteApiV1Requestors55c8705515cc6b2f785b1387($content_type, $authorization, $body);




```

### HTTP Request
`DELETE /api/v1/requestors/55c8705515cc6b2f785b1387`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



delete token requestor

# Get token requestor domains


get token requestor domains

## get token requestor domains
```shell
curl "/api/v1/requestors/55c8817415cc6b300ec4753a/domains" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetTokenRequestorDomainsApi();
api.get_api_v1_requestors55c8817415cc6b300ec4753a_domains(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetTokenRequestorDomainsApi;

ApiClient apiClient = new ApiClient();

GetTokenRequestorDomainsApi api = new GetTokenRequestorDomainsApi(apiClient);
api.getApiV1Requestors55c8817415cc6b300ec4753aDomains(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetTokenRequestorDomainsApi($api_client);
$api->getApiV1Requestors55c8817415cc6b300ec4753aDomains($content_type, $authorization, $body);




```

### HTTP Request
`GET /api/v1/requestors/55c8817415cc6b300ec4753a/domains`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



get token requestor domains

# Create token requestor domain


create token requestor domain

## create token requestor domain
```shell
curl "/api/v1/requestors/563c68f76aa94f1902caa8ff/domains" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.CreateTokenRequestorDomainApi();
api.post_api_v1_requestors563c68f76aa94f1902caa8ff_domains(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.CreateTokenRequestorDomainApi;

ApiClient apiClient = new ApiClient();

CreateTokenRequestorDomainApi api = new CreateTokenRequestorDomainApi(apiClient);
api.postApiV1Requestors563c68f76aa94f1902caa8ffDomains(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\CreateTokenRequestorDomainApi($api_client);
$api->postApiV1Requestors563c68f76aa94f1902caa8ffDomains($content_type, $authorization, $body);




```

### HTTP Request
`POST /api/v1/requestors/563c68f76aa94f1902caa8ff/domains`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



create token requestor domain

# Delete token requestor domain


delete token requestor domain

## delete token requestor domain
```shell
curl "/api/v1/requestors/55c8817415cc6b300ec4753a/domains/55c8855315cc6b30318f1ef9" -X DELETE -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.DeleteTokenRequestorDomainApi();
api.delete_api_v1_requestors55c8817415cc6b300ec4753a_domains55c8855315cc6b30318f1ef9(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.DeleteTokenRequestorDomainApi;

ApiClient apiClient = new ApiClient();

DeleteTokenRequestorDomainApi api = new DeleteTokenRequestorDomainApi(apiClient);
api.deleteApiV1Requestors55c8817415cc6b300ec4753aDomains55c8855315cc6b30318f1ef9(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\DeleteTokenRequestorDomainApi($api_client);
$api->deleteApiV1Requestors55c8817415cc6b300ec4753aDomains55c8855315cc6b30318f1ef9($content_type, $authorization, $body);




```

### HTTP Request
`DELETE /api/v1/requestors/55c8817415cc6b300ec4753a/domains/55c8855315cc6b30318f1ef9`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



delete token requestor domain

# Token info


token info additional description here

## null
```shell
curl "/api/v1/tokens/5123451913660370100" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.TokenInfoApi();
api.get_api_v1_tokens5123451913660370100(content_type, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.TokenInfoApi;

ApiClient apiClient = new ApiClient();

TokenInfoApi api = new TokenInfoApi(apiClient);
api.getApiV1Tokens5123451913660370100(contentType, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\TokenInfoApi($api_client);
$api->getApiV1Tokens5123451913660370100($content_type, $authorization, $body);




```

### HTTP Request
`GET /api/v1/tokens/5123451913660370100`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||



