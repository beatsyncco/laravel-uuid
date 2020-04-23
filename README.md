# Laravel UUID
A simple UUID trait for your eloquent models. 

## Installation
Install the package via composer 
```bash
composer require beatsync/laravel-uuid`
```

## Useage

```php
namespace App;

use BeatSync\Uuid\HasUuid;
use Illuminate\Database\Eloquent\Model;

class MyModel extends Model
{
    use HasUuid;
}
``` 
