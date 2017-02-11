# ps-install-php
PHP Install Script for AppVeyor

## Script Arguments

### -Version

The PHP version to install. `-Version 7.1.1`

### -Highest

Select the highest PHP release of a specific build. 

`-Highest -Version 7.1`

The above will select the highest release of PHP 7.1.x.

### -Lowest

Select the lowest PHP release of a specific build.

`-Lowest -Version 7.1`

The above will select the lowest release of PHP 7.1.x.

### -Arch

Select a specific architecture type for PHP: x86, x64

`-Arch x64`

### -ThreadSafe

Use this switch to select the thread-safe PHP build.

### -InstallPath

The path to install PHP to. Defaults to `C:\tools\php`.

`-InstallPath "C:\Program Files\PHP\v7.0"`

### -Extensions

A comma separated list of extensions to enable by default in the PHP ini file.

`-Extensions ldap,mbstring,intl,openssl`
