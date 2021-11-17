```php
<?php

namespace MedDhiia;

use Username as Gaffa;

class About extends Me
{

    public function getKnowledge(): array
    {
        return [
            Laravel::class,
            Symfony::class,
            Python::class,
            Vuejs::class,
            Flutter::class,
            Docker::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
