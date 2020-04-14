# composer-test-pack-by-shafeek

Link : https://www.w3resource.com/php/composer/create-publish-and-use-your-first-composer-package.php

Its a "hello world" composer test library pack 

Installation using Composer

composer require web-developer-in-bangalore/composer-test-pack-by-shafeek:dev-master

Usage

require_once __DIR__ . '/vendor/autoload.php';

use web_developer_in_bangalore\composer_test_pack_by_shafeek\Index;

$greeting = new Index();

echo $greeting->greet("Hello Composer");

