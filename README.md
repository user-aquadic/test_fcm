### Just Seed DB

`php artisan migrate --seed`

### then 

`php artisan tinker`

```php
$user = User::first();  
$user->notify(new AccountActivated());    
```
