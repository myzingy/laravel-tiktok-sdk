composer.json
```
"autoload": {
        "psr-4": {
            "Fengers\\TikTok\\":"vendor/myzingy/laravel-tiktok-sdk/src"
        }
    },
"require": {"myzingy/laravel-tiktok-sdk": "master"}
"repositories": [
        {
            "type":"package",
            "package": {
                "name": "myzingy/laravel-tiktok-sdk",
                "version":"master",
                "source": {
                    "url": "https://github.com/myzingy/laravel-tiktok-sdk.git",
                    "type": "git",
                    "reference":"master"
                }
            }
        }
    ]
```
