# Heroku buildpack: Ruby-C

Use Ruby-C buildpack if your Heroku application needs to call C code from Ruby.

## Usage

To deploy a C extension with this buidlpack, put ```extconf.rb``` in a root folder named ```c```.
To avoid version conflicts, order the Ruby-C buildpack to run AFTER the main Ruby buildpack.

```sh
$> heroku buildpack:add https://github.com/dextersealy/heroku-buildpack-Ruby-C.git
```
