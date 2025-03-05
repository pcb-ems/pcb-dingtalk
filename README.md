pcb-dingtalk
================================

## 安装

```sh
composer require pcb-ems/pcb-dingtalk
```

## 用例

```php
$client = new PcbEms\PcbDingtalk\Client([
    'app_id' => 'xxxxxxxxxxxxxxxxxxxx',
    'app_secret' => 'xxxxxxx_xxxxxxx-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx',
]);

$userService = new PcbEms\PcbDingtalk\Services\UserService($client);

$data = $userService->getUserByPhone($phone);
```
