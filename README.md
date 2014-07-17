SimplePreAuthenticatorBundle
==============

Backport of Symfony 2.4 SimplePreAuthenticatorInterface to 2.3 LTS branch

Installation
------------

```sh
composer require giosh94mhz/simple-pre-authenticator-bundle:2.3.*
```

Register the bundle in `app/AppKernel.php`:

```php
// app/AppKernel.php
public function registerBundles()
{
    return array(
        // ...
        new Giosh94mhz\SimplePreAuthenticatorBundle\Giosh94mhzSimplePreAuthenticatorBundle(),
    );
}
```

Usage
------------
Everything should work out-of-the-box.

To create an ApiKeyAuthenticator, just [follow the official symfony cookbook](http://symfony.com/doc/current/cookbook/security/api_key_authentication.html)


License
-------

This bundle is released under the MIT license. See the complete license in the
bundle:

    Resources/meta/LICENSE
