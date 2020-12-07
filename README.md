```php
<?php

namespace MedDhiia;

use userame as Gaffa;

class About extends Me
{

    public function getKnowledge(): array
    {
        return [
            Php::class,
            Python::class,
            Laravel::class,
            Symfony::class,
            Vuejs::class,
            Angular::class,
            Docker::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
