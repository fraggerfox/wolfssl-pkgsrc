wolfssl-pkgsrc
===============

NetBSD pkgsrc script for wolfssl.

wolfSSL is a small, portable, embedded SSL/TLS library targeted for use by
embedded systems developers.

You can find wolfSSL [here][1]

NOTE: This package is not yet available in the pkgsrc tree.

Installation
------------

Copy `security/wolfssl` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any package.

`$ cd /usr/pkgsrc/security/wolfssl`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

Credits
-------

* Thanks to `leot@`, `nia@` and `kamil@` for reviewing the package in detail.

License
-------

BSD 2-clause. See LICENSE.

[1]: https://www.wolfssl.com/
[2]: https://github.com/wolfssl/wolfssl

