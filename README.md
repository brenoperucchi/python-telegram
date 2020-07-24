# python-telegram

See original for documentation

This version has been adapted to be installed as a Python module named `telegram_api` instead of `telegram`. As it would otherwise conflict with a same-named module from the `python-telegram-bot` package.

In addition, in telegram_api/lib/linux, two libtdjson files can be found.
- `libtdjson_64.so`, for 64 bit systems.
- `libtdjson_armh7.so`, v1.6.0 compiled on a Raspberry pi with debian 10

Depending on what system you use, rename one of the two files to `libtdjson.so`, and then install with:
- `git clone https://github.com/thaije/python-telegram.git`
- change libtdjson to fit your system
- `python3 -m pip install python-telegram/`
