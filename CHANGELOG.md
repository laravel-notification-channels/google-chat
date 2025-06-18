# Changelog

All notable changes to `google-chat` will be documented in this file

## 3.1.0 - 2025-01-XX

-   **BREAKING:** Minimum PHP version is now 8.2
-   **BREAKING:** Now requires Laravel 12.x (dropped support for Laravel 9.x, 10.x, 11.x)
-   Updated to PHPUnit 11.x
-   Updated Orchestra Testbench to v10.x for Laravel 12
-   Updated GitHub Actions to test PHP 8.2, 8.3, and 8.4
-   Updated Guzzle HTTP to v7.x only

## 3.0.0 - 2022-04-30

-   Correct passing of notification instance instead of notifiable instance

## 2.0.1 - 2022-04-09

-   Corrected Laravel Framework version constraints, preventing installations on Laravel versions >=9.1

## 2.0.0 - 2022-02-12

-   Upgraded to support Laravel 9.x (Minimum of 9.0.2 due to an [unintended breaking change](https://github.com/laravel/framework/pull/40880))
-   Dropped support for PHP 7.3 and 7.4

## 1.0.1 - 2021-07-16

-   Removed property type hints for PHP 7.3 compatibility

## 1.0.0 - 2021-05-18

-   Initial Release - Woo-hoo!
