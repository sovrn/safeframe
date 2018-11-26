# Changelog
All notable changes to this project will be documented in this file.

Forked on 2018-11-23.

## 2018
### Changed

- added `sandbox` attribute to the iFrame on method _fire_pub_callback in
host.js.
- added a setTimeout in the _unbind_iframe_onload method in base.js. This calls the original onload
callback after a short period - incase the the iFrame is not visible.

## [1.0.0] - 2018-11-26
### Changed

- added fix in host.js, method - _handle_msg_from_outside to make sure the data attribute is
a string before executing indexOf on it.
- safeframe URLs now under 1.0.0
