
<!--#echo json="package.json" key="name" underline="=" -->
nodemcu-firmware-daily-vanilla
==============================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Minimum demo of `nodemcu-firmware-build-as-github-action` (BAGA), using
all-defaults config.
<!--/#echo -->

See also: [the BAGA repo][baga]

Using a separate repo because the Github Actions cron trigger
seems to only be able to build the master branch.

The only important file here is `.github/workflows/build_firmware.yaml`.
The top-level symlink `build_firmware.yaml` is just for my convenience.




ESP8266 legacy build config
---------------------------

I consider the `user_*.h` build config header files "legacy" because
I'm working on a better way to configure it.
Put them in `esp8266.app.include/`, just without the `user_` prefix.


ESP32 SDK config
----------------

see [esp32.sdkcfg/](esp32.sdkcfg/)





&nbsp;

  [baga]: https://github.com/mk-pmb/nodemcu-firmware-build-as-github-action



License
-------
<!--#echo json="package.json" key=".license" -->
MIT
<!--/#echo -->
