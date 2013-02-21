# Google Apps Sign-in for Drupal

This module lets you log into a Drupal site using your Google Apps
credentials.

## Configuration

In your `settings.php`:

    $conf['google_apps_signin_domain'] = 'example.com';
    $conf['google_apps_signin_user_roles'] = array('some_role', 'another_role');

## Dependencies

The Janrain [PHP OpenID](https://github.com/openid/php-openid/) library and Google's [OpenID Apps Discovery
extension](http://code.google.com/p/php-openid-apps-discovery/) need to be installed in your Drupal `libraries`
folder. You can use [this fork that combines the
two](https://github.com/kollegorna/php-openid) if you like.

## Acknowledgements

I would never have figured out how to do this if it wasn't for Constantin Bosneaga's [excellent post on the subject](http://a32.me/2011/03/google-apps-as-single-authentication-point-for-your-corporate-applications/).
