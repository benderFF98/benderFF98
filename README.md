<h1 align='center'>
  Hello, I'm Felipe Bender :boy: <a href="https://www.linkedin.com/in/benderfelipe/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;&nbsp;
</h1>

```php
<?php

namespace FelipeBender;

class About extends Me
{
    //So, I lost my old account due to some security issues this is the new one :)
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Sixchains',
                'position' => 'Backend Developer'         
            ]
        ];
    }

    public function getBestSkills(): array
    {
        return [
            Php::class,
            Laravel::class,
            GoogleCloud::class,
            Python::class,
            SQL::class,
            NoSQL::class
        ];
    }

    public function getSkills(): array
    {
        return [
            Kubernetes::class,
            DataAnalysis::class,
            Javascript::class,
        ];
    }

    public function getLearningSkills(): array
    {
        return [
            Go::class,
            ApiSecurity:class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Do some code related research on academic levels';
    }
}
```


<details>
  <summary>📃 Resume</summary>


## Education

- 📖 **System Analysis and Development**\
📆 2023 - 2025\
📍 **ESTACIO - Universidade Paranaesne** - Toledo/PR, Brazil

## Experience
  
   - 👨‍💻 **PHP Developer(Laravel)**\
📆 2022 - moment\
📍 **Sixchains** - Remote
  
  - 👨‍💻 **PHP Developer(Laravel)**\
📆 2021 - 2022\
📍 **Manfing** - Toledo/PR, Brazil

- 👨‍💻 **Support Manager / IT / Network Engineer JR**\
📆 2020 - 2021\
📍 **Oesteline** - Toledo/PR, Brazil
