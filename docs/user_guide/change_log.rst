Change Log
==========

0.5.2
-----

ngshare:

- Update helm chart to allow configuring the `accessMode` of ngshare's PVC via `pvc.accessModes`. The PVC will be mounted `ReadWriteMany` by default unless you override this value. (Thanks [pcfens](https://github.com/pcfens) for the [PR](https://github.com/LibreTexts/ngshare/pull/120)!)

0.5.1
-----

ngshare:

- Update helm chart with clearer installation instructions
- Misc. documentation updates to help with installation
- Transfer repository ownership to LibreTexts, change all GitHub links and tokens related to Travis, PyPI, etc
- Test Travis autopublishing a stable release

ngshare_exchange:

- Drastically increase test coverage
- Removed some dead code
- Several important bugfixes and typo fixes in the exchange classes and course management tool
- Transfer repository ownership to LibreTexts, change all GitHub links and tokens related to Travis, PyPI, etc
- Test Travis autopublishing a stable release

0.5.0
-----
Initial release intended for the public.

