# Craigslist car listings crawler

Crawls craigslist car listings and stores results in sqlite db

## Setup & Run

```
sudo apt install composer php php-sqlite3
composer install
php crawl.php
php -S localhost:9000
xdg http://localhost:9000/
```

## View the SQLite DB
```sqlite3 cars.db```


Note : The crawler currently searches only for Toyota Camrys posted by owners. This can be changed by opening crawl.php and modifying the link on line 27 or changing the keyword on line 5
