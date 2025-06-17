# think-paginator-driver

## 安装
```bash
composer require reaway/think-paginator-driver
```

## 用法
在provider.php定义文件中重新绑定
```php
use Think\Component\Paginator\Bootstrap4;

return [
    'think\Paginator' => Bootstrap4::class
];
```

## 文档

详细参考 [https://doc.thinkphp.cn/v8_0/pagination_query.html](https://doc.thinkphp.cn/v8_0/pagination_query.html)