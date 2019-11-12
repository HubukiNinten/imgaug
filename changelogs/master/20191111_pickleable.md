# All Augmenters Pickle-able

* Added function `imgaug.testutils.runtest_pickleable_uint8_img()`.
* Fixed `imgaug.augmenters.blur.MotionBlur` not being pickle-able.
* Fixed `imgaug.augmenters.meta.AssertLambda` not being pickle-able.
* Fixed `imgaug.augmenters.color.MultiplyHueAndSaturation` not supporting
  all standard RNG datatypes for `random_state`.
