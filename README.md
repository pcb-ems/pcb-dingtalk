PcbDingtalk
================================

Installation
--------------------------------

```sh
composer require pcb-ems/pcb-dingtalk
```

Usage
--------------------------------

```php
$client = new PcbEms\PcbDingtalk\Client([
    'app_id' => 'xxxxxxxxxxxxxxxxxxxx',
    'app_secret' => 'xxxxxxx_xxxxxxx-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx',
]);

$userService = new PcbEms\PcbDingtalk\Services\UserService($client);

$data = $userService->getUserByPhone($phone);
```
