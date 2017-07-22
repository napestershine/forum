# Tinker Commands
```$xslt
$ php artisan tinker
$ thread = factory('App\Thread', 50)->create(); 
$ $thread->each(function ($thread) { factory('App\Reply', 10)->create(['thread_id' => $thread->id]); });
```