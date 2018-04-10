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

## Security

If you discover any security related issues, please email haobing.wang@qq.com instead of using the issue tracker.

## Credits

- [Haobing Wang][link-author]


[ico-version]: https://img.shields.io/packagist/v/miuhr/alipay-sdk.svg
[link-packagist]: https://packagist.org/packages/miuhr/alipay-sdk

[ico-downloads]: https://img.shields.io/packagist/dt/miuhr/alipay-sdk.svg
[link-downloads]: https://packagist.org/packages/miuhr/alipay-sdk

[ico-license]: https://img.shields.io/packagist/l/doctrine/orm.svg

[link-author]: https://github.com/haobingwang

