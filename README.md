### Author: Pham Ngoc Linh ###

# Run Project Command: 

- Stop local service: service mysql stop && service apache2 stop 

- Set alias for sail: alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'

- Build project: ./vendor/bin/sail up || sail up

- Stop project: sail stop

# Access Workspace

- docker exec -it laravel-with-sail-laravel.test-1 bash

- sail php --version

- sail composer require laravel/sanctum

- sail exec mysql mysql -u root -p


# Laravel Command

- Make controller : sail php artisan make:controller Api/ProductController -r --model=Product
