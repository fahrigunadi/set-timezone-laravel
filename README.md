# set-timezone-laravel
## Open File App\Providers\AppServiceProvider
Change method boot

```
public function boot()
{
	config(['app.locale' => 'id']);
	Carbon::setLocale('id');
}
```

### Open file config/app.php
Change separated values

```
'timezone' => 'Asia/Jakarta',

'locale' => 'id',

'faker_locale' => 'id_ID',
```
