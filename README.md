Symfony Polyfill / Php70
========================

This component provides functions unavailable in releases prior to PHP 7.0:

- [`intdiv`](http://php.net/intdiv)
- [`preg_replace_callback_array`](http://php.net/preg_replace_callback_array)
- [`error_clear_last`](http://php.net/error_clear_last)
- `random_bytes` and `random_int` (from [paragonie/random_compat](https://github.com/paragonie/random_compat))
- [`*Error` throwable classes](http://php.net/Error)

More information can be found in the 
[main Polyfill README](https://github.com/symfony/polyfill/blob/master/README.md).

License
=======

This library is released under the [MIT license](LICENSE).