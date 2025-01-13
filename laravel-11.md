1. Error saat verification email: https://iamrizwan.me/fix-email-verification-in-filamentphp/
2. cara query berdasarkan id user
   ```php
   public static function getEloquentQuery(): Builder{
        return parent::getEloquentQuery()->where('user_id',auth()->id());
    }
   ```

   Sumber
   - https://dev.to/johndivam/laravel-filament-get-resource-table-data-by-authenticated-id-15j7
   - https://stackoverflow.com/questions/77347148/laravel-filament-how-to-get-table-data-by-authenticated-user-id
   - https://filamentphp.com/docs/3.x/panels/resources/getting-started#customizing-the-resource-eloquent-query
   - https://laraveldaily.com/tip/filament-make-table-row-clickable-and-lead-to-view-page

3. 
