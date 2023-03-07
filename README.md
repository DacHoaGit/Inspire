## Installation

Update composer.json

```bash
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/dachoagit/inspire"
    }
]
```

Execute the following command to install the package:

```bash
composer require dachoagit/inspire:"*"
```

Open the `config/app.php` file and scroll down to the providers array.
Add the following line of code in that section:

```bash
Dachoagit\Inspire\Providers\InspirationProvider::class,
```
