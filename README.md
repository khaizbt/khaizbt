```php
<?php

namespace KhaizBadaruTammam;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Technopartner Indonesia',
                'position' => 'Software Engineer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            //Programming Language
            Php::class,
            Javascript::class,
            Laravel::class,
            Go::class,
            // Database
            MySql::class,
            MongoDB::class,
            ElasticSearch::class,
            
            //Server
            Docker::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
    
    public function getAvailableNow() : string 
    {
        return "I'm looking for freelance job";
    }
}
```
