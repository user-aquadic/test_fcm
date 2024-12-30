### add firebase file to disk and .env
FIREBASE_CREDENTIALS=storage/app/firebase-auth.json

### Just Seed DB

`php artisan migrate --seed`

### then 

`php artisan tinker`

```php
$user = User::first();  
$user->notify(new AccountActivated());    
```
