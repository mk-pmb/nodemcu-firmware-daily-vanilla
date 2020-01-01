
<!--#echo json="package.json" key="name" underline="=" -->
nodemcu-firmware-daily-vanilla
==============================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Minimum demo of `nodemcu-firmware-build-as-github-action`, using all-defaults
config.
<!--/#echo -->

Using a separate repo because the Github Actions cron trigger
seems to only be able to build the master branch.

The only important file here is `.github/workflows/build_firmware.yaml`.
The top-level symlink `build_firmware.yaml` is just for my convenience.



&nbsp;

  [baga]: https://github.com/mk-pmb/nodemcu-firmware-build-as-github-action



License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->
