## PHP NHZ Faucet

A faucet application for NHZ written in PHP on top of the Laravel framework.

### Requirements

* PHP 5.3.\*
* composer
* Redis

### Installation

The faucet is designed around Laravel, which uses composer as its core package
management system. This makes deployment pretty simple.

1. Clone this repository onto your server
2. Run ```composer install``` to download the dependencies
3. Configure the application-specific settings in app/config/{app,faucet}.php
4. Publish the site via Apache

