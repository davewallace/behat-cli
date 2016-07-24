# Setup

Followed instructions here: http://docs.behat.org/en/v2.5/quick_intro.html

In order to install Composer correctly, I needed to find the right PHP install
(as I have 2 on system) and check PATH entry and modify php.ini to uncomment the
`php_openssl` extension. May also then need to uncomment the `extension_dir`,
ensuring it is pointing at the correct dir containing `php_openssl` extension.

Also, I modified the `test` directory in the above instructions to `example` for
my own preference in naming convention.

# Run the test
Using CLI, navigate into `test/ls_project` and run `behat`.
