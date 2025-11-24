<h1 align='center'>
  Hello, I'm Felipe Bender 👨‍💻  
  <a href="https://www.linkedin.com/in/benderfelipe/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</h1>

```php
<?php

namespace FelipeBender;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company'  => 'SSYS Sistemas',
                'position' => 'Tech Lead'
            ]
        ];
    }

    public function getBestSkills(): array
    {
        return [
            Python::class,
            PHP::class,
            Javascript::class,
            Kotlin::class,
            SQL::class,
            NoSQL::class,
            Cloud::class,         // AWS / GCP
            Kubernetes::class
        ];
    }

    public function getSkills(): array
    {
        return [
            Laravel::class,
            Django::class,
            NodeJS::class,
            VueJS::class,
            DataPipelines::class,
            CICD::class,
            Docker::class,
            Microservices::class
        ];
    }

    public function getLearningSkills(): array
    {
        return [
            Go::class,
            AILLMs::class,        // AI, LLMs, ML research
            AdvancedCloud::class  // Infra scaling, K8s, Helm
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Pursue a Master’s degree in Computer Science focusing on Artificial Intelligence research.';
    }
}
