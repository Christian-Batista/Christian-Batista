```sh
/**
 * 🚀 Self-taught junior developer, passionate about hands-on learning and continuous improvement.
 *
 * 💡 Passionate about delivering my best, constantly seeking opportunities to contribute
 *    and collaborate with others. Strong believer in teamwork and the power of collective growth.
 *
 * 🌐 Looking forward to expanding both technical skills and soft skills this year, with the ultimate goal of
 *    getting closer to my dreams. Let's learn, share, and code together! 💻✨
 */
```
```sh
<?php

namespace ChrisBatDev;

class About extends Me
{

    /**
     * Where the magic happens! 🚀 Currently shaping ideas at MidasRed.
     *
     * @return array
     */
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'MidasRed',
                'position' => 'Software Developer'         
            ]
        ];
    }

    /**
    * My daily companions in the coding journey! 💻✨
    *
    * @return array
    */
    public function getDailyKnowledge(): array
    {
        return [
            'Php' => '50%',
            'Javascript' => '35%',
            'Laravel' => '60%',
            'Vuejs' => '30%',
            'ReactNative' => '30%',
            'TailwindCss' => '60%'
        ];
    }

    /**
    * Worked at HillsdaleAssets in Moca, Dominican Republic for 1 year.
    *
    * 📆 Duration: 1 year
    * 🌍 Location: Moca, Dominican Republic
    *
    * 🛠 Technologies used:
    * - SQL
    * - Laravel
    * - Vue.js
    *
    * #codingMemories #TeamWork #LearningJourney
    */
    public function getHillsdaleAssetsExperience(): array
    {
        return [
            'duration' => '1 year',
            'location' => 'Moca, Dominican Republic',
            'technologies' => ['SQL', 'Laravel', 'Vue.js'],
            'responsibilities' => 'Building tools to manage various aspects of a swimwear manufacturing factory.'           
        ];
    }

    /**
    * Dreaming of a world where coding is not just a job, but a love affair. 💖✨
    *
    * @return string
    */
    public function getFutureGoal(): string
    {
        return 'To become a developer who not only loves what they do but lives for it.';
    }
}
```
# Christian-Batista
