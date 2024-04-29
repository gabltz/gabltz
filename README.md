```php
namespace gab;

class About extends him
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Clinique La Ligne Bleue - Groupe Louis Pasteur Santé',
                'location' => 'Epinal (on-site)'
            ];[
                'company' => 'Propel',
                'location' => 'Nice, France (remote)'
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

}>
