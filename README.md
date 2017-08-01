# bankcard-info
查询银行卡信息

> 代码参考 [abei2017](https://github.com/abei2017/yii2-bankcard-info),根据自身需求稍作修改


安装步骤
------------

执行

```
composer require gnp/bankcard-info dev-master

```

然后执行 composer install

代码中如何使用
```
 require_once __DIR__.'/vendor/autoload.php';
 $number = '银行卡号';
 $res = gnp\bankcardInfo\BankCard::cardInfo($number);
 var_dump($res);
```
