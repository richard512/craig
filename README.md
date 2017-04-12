# Craigslist car listings crawler

Crawls craigslist car listings and stores results in sqlite db

### Install dependencies

```
sudo apt install composer php php-sqlite3
composer install
```

### Start the crawler
```
php crawl.php
```

### Start the php web server
```
php -S localhost:9000
```

### Open the web app in your default web browser
```
xdg-open http://localhost:9000/
```

### View the SQLite DB
```sqlite3 cars.db```


Note : The crawler currently searches only for Toyota Camrys posted by owners. This can be changed by opening crawl.php and modifying the link on line 27 or changing the keyword on line 5
