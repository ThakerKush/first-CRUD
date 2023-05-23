### A CRUD api in laravel

### How to run the project

After setting up laravel on your machine run

```bash
php artisan serve
```

In the root of the project

The routes are as follows:

```php
Route::get('/product', [ProductController::class, 'index']);                        -->Read
Route::post('/product/create', [ProductController::class, 'store']);                -->Create
Route::get('/product/{id}', [ProductController::class, 'show']);                    -->Read By Id
Route::put('/product/update/{id}', [ProductController::class, 'update']);           -->Update
Route::delete('/product/delete/{id}', [ProductController::class, 'destroy']);       -->Delete
```
