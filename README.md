# Alipay SDK (支付宝SDK)

[![Latest Stable Version](https://poser.pugx.org/miuhr/alipay-sdk/v/stable)](https://packagist.org/packages/miuhr/alipay-sdk)
[![Total Downloads](https://poser.pugx.org/miuhr/alipay-sdk/downloads)](https://packagist.org/packages/miuhr/alipay-sdk)
[![License](https://poser.pugx.org/miuhr/alipay-sdk/license)](https://packagist.org/packages/miuhr/alipay-sdk)

所有SDK源文件取自 [支付宝官网](https://docs.open.alipay.com/54/103419/)，原版未改动。

最后更新版本参见保留目录名

## 使用

```$bash
composer require miuhr/alipay-sdk
```

所有类都被映射到了顶层命名空间

```php
$c = new \AopClient();
$c->gatewayUrl = "https://openapi.alipay.com/gateway.do";

$request= new \AlipaySystemOauthTokenRequest();
$request->setCode($auth_code);
```
