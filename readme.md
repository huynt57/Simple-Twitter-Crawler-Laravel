# Simple Twitter Crawler


This is a simple application to crawl tweets from twitter. 

## Install

You need PHP 5.6, MySQL, Apache and composer installed to run this project.


You need to change config to your database in .env file

In root, run:

<pre>
composer install
php artisan key:generate
php artisan migrate

</pre>

Run:
<pre>
/get-tweet
</pre>

to see result

Thanks