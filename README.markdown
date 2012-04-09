# Smartdict

By [Sergey Potapov](https://github.com/greyblake).

## WTF?

It's a simple dictionary written in Ruby and GTK.

![Smartdict](http://i1078.photobucket.com/albums/w484/greyblake/smartdict.png)

## Installation

### Prerequisites


#### Debian/Ubuntu

On Debian/Ubuntu you need to install the next packages:

* libglib2.0-dev
* libatk1.0-dev
* libcairo-dev
* libsqlite3-dev
* libpango1.0-dev

To do that run:

```
apt-get install libglib2.0-dev libatk1.0-dev libcairo-dev libsqlite3-dev libpango1.0-dev
```

Please report if you have issues or it's not complete list of required dependencies.


### Ruby version

Tested on MRI 1.9.3-p125


### Install the gem

```
gem install smartdict
```


## Running

Command line:

```
smartdict --help
```

GUI:

```
smartdict-gtk
```


## Configuring / adding new languages

Take a look at `$HOME/.smartdict/configuration.yml`.



## Copyright

Copyright (c) 2012 Potapov Sergey. The software is distributed under
[GNU GeneralPublic License version 2](http://www.gnu.org/licenses/gpl-2.0.txt).
See GPL-LICENSE.txt file for more details.
