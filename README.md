```php
namespace gab;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'RDPLab',
                'location' => 'Swiss'         
            ];[
                'company' => 'Clinique La Ligne Bleue - Groupe Louis Pasteur Santé',
                'location' => 'Epinal'
            ]
        ];
    }
    public function getCurrentJob(): array
    {
        return [
            'job' => [
                'title' => 'Pentester, System & Network Administrator, Musician',
                'location' => 'Epinal, France'
            ]
        ];
    }
    public function getCurrentEducation(): array
    {
        return [
            'education' => [
                'school' => 'Pierre Mendès France High School Epinal',
                'location' => 'Epinal, France'
            ]
        ];
    }
    

    public function getDailyKnowledge(): array
    {
        return [
            Linux::class,
            Windows::class,
            MacOS::class,
            Mikrotik::class,
            Network::class,
            Security::class,
            Php::class,
            Javascript::class,
            HTML::class,
            Python::class,
            Css::class,
            Git::class,
            MySql::class,
            Bash::class,
            Electron::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To make internet safer and faster everyday';
    }
}>
