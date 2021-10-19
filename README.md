<?php

namespace ClaudioAlcantaraR;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Marujalimón',
                'position' => 'Web Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            MySQL::class,
            Javascript::class,
            HTML5::class,
            CSS3::class,
            Wordpress::class,
            Ecommerce::class,
            Bootstrap::class,
            AdobeXD::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
