# Heroku buildpack: Ruby-C

Use Ruby-C buildpack if your Heroku application needs to call C code from Ruby.

## Usage

NOTE: To deploy a C extension with this buidlpack, put ```extconf.rb``` in a root folder named ```c```.

```sh
$> heroku config:add BUILDPACK_URL=https://github.com/dextersealy/heroku-buildpack-Ruby-C.git
```
