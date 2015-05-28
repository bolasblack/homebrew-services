Homebrew Services
=================

Integrates homebrew formulae with MacOS X' `launchctl` manager.

## Installation ##

```
brew tap homebrew/services
```

## EXAMPLES ##
Install and start service mysql at login:

```
$ brew install mysql

$ brew services start mysql

# Assign UserName as root
$ sudo brew services start --root mysql
```

Stop service mysql:

```
$ brew services stop mysql
```
