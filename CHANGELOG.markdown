0.7
---
* Corrected the definition of `mignitude`.
* Added a notion of `distance` between intervals

0.6
---
* Added `Numeric.Interval.Exception`. For consistency, we tend to throw exceptions now instead of rely on `NaN` when working with empty intervals.

0.5.1.1
-------
* Misc `doctest` fixes.

0.5.1
-----
* Added `interval` to facilitate the construction of known non-empty intervals.

0.5
---
* The default `Numeric.Interval` now deals more conventionally with empty intervals.
* The old "Kaucher directed interval" behavior is available as `Numeric.Interval.Kaucher`.
* Strictly Non-Empty intervals are now contained in `Numeric.Interval.NonEmpty`
* Renamed `bisection` to `bisect`.
* Added `bisectIntegral`.

0.4.2
-----
* Added `clamp`

0.4
---
* Distributive Interval

0.3
---
* Removed dependency on `numeric-extras`

