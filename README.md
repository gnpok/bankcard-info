# bankcard-info
查询银行卡信息
abei2017/yii2-bankcard-info
=============
支持国内数百家银行的卡面分析，可以使用composer直接安装。


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
 $number = '6217001270017368707';
 $res = gnp\bankcardInfo\BankCard::cardInfo($number);
 var_dump($res);
```