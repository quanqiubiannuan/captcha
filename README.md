# 验证码
PHP 验证码类。

**安装**

`composer require daiji/captcha`

**使用**

thinkphp框架

```php
<?php

namespace app\controller;

use app\BaseController;
use daiji\captcha\Captcha;

class Index extends BaseController
{
    public function index()
    {
        // 输出验证码图片
        Captcha::getInstance()->output();
    }
}
```

其它框架同理使用！

