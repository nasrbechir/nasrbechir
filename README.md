```php
<?php

namespace Bechir;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Synergy Soft',
                'position' => 'Web developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            PHP::class,
            Javascript::class,
	        Symfony::class,
            Laravel::class,
            Wordpress::class,
            ReactJS::class,
            Bootstrap::class,
            TailwindCss::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
