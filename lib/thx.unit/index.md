---
name: thx.unit
license: MIT
path: thx/unit
tags: 
  - thx
  - math
  - dimension
  - unit
  - cross
layout: library
classPath: src
description: Units library
contributors: 
  - fponticelli
releasenote: Better documentation
version: 0.3.5
url: "https://github.com/fponticelli/thx.unit"
title: thx.unit
dependencies: 
  thx.core: ""

---

# thx.unit

[![Build Status](https://travis-ci.org/fponticelli/thx.unit.svg)](https://travis-ci.org/fponticelli/thx.unit)

The library contains type definitions for several kind of units. They are defined as asbtract types to siplify their usage as much as possible.

```haxe
(10 : Millimetre) * 100 == (1 : Metre);
// other example
var f = (27 : Celsius).toFahrenheit()
```

The following units are currently supported:

  * amount of substance: [`Mole`](http://thx-lib.org/api/thx/unit/amountofsubstance/Mole.html), [`PoundMole`](http://thx-lib.org/api/thx/unit/amountofsubstance/PoundMole.html).
  * angle: [`BinaryDegree`](http://thx-lib.org/api/thx/unit/angle/BinaryDegree.html), [`Degree`](http://thx-lib.org/api/thx/unit/angle/Degree.html), [`Grad`](http://thx-lib.org/api/thx/unit/angle/Grad.html), [`HourAngle`](http://thx-lib.org/api/thx/unit/angle/HourAngle.html), [`MinuteOfArc`](http://thx-lib.org/api/thx/unit/angle/MinuteOfArc.html), [`Point`](http://thx-lib.org/api/thx/unit/angle/Point.html), [`Quadrant`](http://thx-lib.org/api/thx/unit/angle/Quadrant.html), [`Radian`](http://thx-lib.org/api/thx/unit/angle/Radian.html), [`Revolution`](http://thx-lib.org/api/thx/unit/angle/Revolution.html), [`SecondOfArc`](http://thx-lib.org/api/thx/unit/angle/SecondOfArc.html), [`Sextant`](http://thx-lib.org/api/thx/unit/angle/Sextant.html), [`Turn`](http://thx-lib.org/api/thx/unit/angle/Turn.html).
  * current: [`Ampere`](http://thx-lib.org/api/thx/unit/current/Ampere.html).
  * digital: [`Byte`](http://thx-lib.org/api/thx/unit/digital/Byte.html), [`Exabit`](http://thx-lib.org/api/thx/unit/digital/Exabit.html), [`Exabyte`](http://thx-lib.org/api/thx/unit/digital/Exabyte.html), [`Gigabit`](http://thx-lib.org/api/thx/unit/digital/Gigabit.html), [`Gigabyte`](http://thx-lib.org/api/thx/unit/digital/Gigabyte.html), [`Kilobit`](http://thx-lib.org/api/thx/unit/digital/Kilobit.html), [`Kilobyte`](http://thx-lib.org/api/thx/unit/digital/Kilobyte.html), [`Megabit`](http://thx-lib.org/api/thx/unit/digital/Megabit.html), [`Megabyte`](http://thx-lib.org/api/thx/unit/digital/Megabyte.html), [`Petabit`](http://thx-lib.org/api/thx/unit/digital/Petabit.html), [`Petabyte`](http://thx-lib.org/api/thx/unit/digital/Petabyte.html), [`Terabit`](http://thx-lib.org/api/thx/unit/digital/Terabit.html), [`Terabyte`](http://thx-lib.org/api/thx/unit/digital/Terabyte.html), [`Yottabit`](http://thx-lib.org/api/thx/unit/digital/Yottabit.html), [`Yottabyte`](http://thx-lib.org/api/thx/unit/digital/Yottabyte.html), [`Zettabit`](http://thx-lib.org/api/thx/unit/digital/Zettabit.html), [`Zettabyte`](http://thx-lib.org/api/thx/unit/digital/Zettabyte.html).
  * length:  [`AstronomicalUnit`](http://thx-lib.org/api/thx/unit/length/AstronomicalUnit.html), [`Centimeter`](http://thx-lib.org/api/thx/unit/length/Centimeter.html), [`Centimetre`](http://thx-lib.org/api/thx/unit/length/Centimetre.html), [`Chain`](http://thx-lib.org/api/thx/unit/length/Chain.html), [`EarthRadius`](http://thx-lib.org/api/thx/unit/length/EarthRadius.html), [`Fathom`](http://thx-lib.org/api/thx/unit/length/Fathom.html), [`Foot`](http://thx-lib.org/api/thx/unit/length/Foot.html), [`Furlong`](http://thx-lib.org/api/thx/unit/length/Furlong.html), [`Inch`](http://thx-lib.org/api/thx/unit/length/Inch.html), [`Kilometer`](http://thx-lib.org/api/thx/unit/length/Kilometer.html), [`Kilometre`](http://thx-lib.org/api/thx/unit/length/Kilometre.html), [`League`](http://thx-lib.org/api/thx/unit/length/League.html), [`LightYear`](http://thx-lib.org/api/thx/unit/length/LightYear.html), [`Line`](http://thx-lib.org/api/thx/unit/length/Line.html), [`Meter`](http://thx-lib.org/api/thx/unit/length/Meter.html), [`Metre`](http://thx-lib.org/api/thx/unit/length/Metre.html), [`Micrometer`](http://thx-lib.org/api/thx/unit/length/Micrometer.html), [`Micrometre`](http://thx-lib.org/api/thx/unit/length/Micrometre.html), [`Mile`](http://thx-lib.org/api/thx/unit/length/Mile.html), [`Millimeter`](http://thx-lib.org/api/thx/unit/length/Millimeter.html), [`Millimetre`](http://thx-lib.org/api/thx/unit/length/Millimetre.html), [`Nanometer`](http://thx-lib.org/api/thx/unit/length/Nanometer.html), [`Nanometre`](http://thx-lib.org/api/thx/unit/length/Nanometre.html), [`NauticalMile`](http://thx-lib.org/api/thx/unit/length/NauticalMile.html), [`Thou`](http://thx-lib.org/api/thx/unit/length/Thou.html), [`Yard`](http://thx-lib.org/api/thx/unit/length/Yard.html).
  * luminous intensity: [`Candela`](http://thx-lib.org/api/thx/unit/luminousintensity/Candela.html), [`Candlepower`](http://thx-lib.org/api/thx/unit/luminousintensity/Candlepower.html).
  * mass: [`Centigram`](http://thx-lib.org/api/thx/unit/mass/Centigram.html), [`Dalton`](http://thx-lib.org/api/thx/unit/mass/Dalton.html), [`Drachm`](http://thx-lib.org/api/thx/unit/mass/Drachm.html), [`Grain`](http://thx-lib.org/api/thx/unit/mass/Grain.html), [`Gram`](http://thx-lib.org/api/thx/unit/mass/Gram.html), [`Hundredweight`](http://thx-lib.org/api/thx/unit/mass/Hundredweight.html), [`Kilogram`](http://thx-lib.org/api/thx/unit/mass/Kilogram.html), [`Megagram`](http://thx-lib.org/api/thx/unit/mass/Megagram.html), [`Microgram`](http://thx-lib.org/api/thx/unit/mass/Microgram.html), [`Milligram`](http://thx-lib.org/api/thx/unit/mass/Milligram.html), [`Nanogram`](http://thx-lib.org/api/thx/unit/mass/Nanogram.html), [`Ounce`](http://thx-lib.org/api/thx/unit/mass/Ounce.html), [`Picogram`](http://thx-lib.org/api/thx/unit/mass/Picogram.html), [`PlankMass`](http://thx-lib.org/api/thx/unit/mass/PlankMass.html), [`Pound`](http://thx-lib.org/api/thx/unit/mass/Pound.html), [`Quarter`](http://thx-lib.org/api/thx/unit/mass/Quarter.html), [`Slug`](http://thx-lib.org/api/thx/unit/mass/Slug.html), [`SolarMass`](http://thx-lib.org/api/thx/unit/mass/SolarMass.html), [`Stone`](http://thx-lib.org/api/thx/unit/mass/Stone.html), [`Ton`](http://thx-lib.org/api/thx/unit/mass/Ton.html), [`Tonne`](http://thx-lib.org/api/thx/unit/mass/Tonne.html), [`UnifiedAtomicMassUnit`](http://thx-lib.org/api/thx/unit/mass/UnifiedAtomicMassUnit.html).
  * temperature: [`Celsius`](http://thx-lib.org/api/thx/unit/temperature/Celsius.html), [`Centrigrade`](http://thx-lib.org/api/thx/unit/temperature/Centrigrade.html), [`Delisle`](http://thx-lib.org/api/thx/unit/temperature/Delisle.html), [`Fahrenheit`](http://thx-lib.org/api/thx/unit/temperature/Fahrenheit.html), [`Kelvin`](http://thx-lib.org/api/thx/unit/temperature/Kelvin.html), [`Newton`](http://thx-lib.org/api/thx/unit/temperature/Newton.html), [`Rankine`](http://thx-lib.org/api/thx/unit/temperature/Rankine.html), [`Reaumur`](http://thx-lib.org/api/thx/unit/temperature/Reaumur.html), [`Romer`](http://thx-lib.org/api/thx/unit/temperature/Romer.html).
  * time: [`Centriday`](http://thx-lib.org/api/thx/unit/time/Centriday.html), [`Day`](http://thx-lib.org/api/thx/unit/time/Day.html), [`Fortnight`](http://thx-lib.org/api/thx/unit/time/Fortnight.html), [`Fourth`](http://thx-lib.org/api/thx/unit/time/Fourth.html), [`Gigasecond`](http://thx-lib.org/api/thx/unit/time/Gigasecond.html), [`Hour`](http://thx-lib.org/api/thx/unit/time/Hour.html), [`JiffyPhysics`](http://thx-lib.org/api/thx/unit/time/JiffyPhysics.html), [`JulianYear`](http://thx-lib.org/api/thx/unit/time/JulianYear.html), [`Ke`](http://thx-lib.org/api/thx/unit/time/Ke.html), [`Kilosecond`](http://thx-lib.org/api/thx/unit/time/Kilosecond.html), [`Megasecond`](http://thx-lib.org/api/thx/unit/time/Megasecond.html), [`Microsecond`](http://thx-lib.org/api/thx/unit/time/Microsecond.html), [`Millisecond`](http://thx-lib.org/api/thx/unit/time/Millisecond.html), [`Minute`](http://thx-lib.org/api/thx/unit/time/Minute.html), [`Nanosecond`](http://thx-lib.org/api/thx/unit/time/Nanosecond.html), [`Picosecond`](http://thx-lib.org/api/thx/unit/time/Picosecond.html), [`PlankTimeUnit`](http://thx-lib.org/api/thx/unit/time/PlankTimeUnit.html), [`Second`](http://thx-lib.org/api/thx/unit/time/Second.html), [`Shake`](http://thx-lib.org/api/thx/unit/time/Shake.html), [`Svedberg`](http://thx-lib.org/api/thx/unit/time/Svedberg.html), [`SynodicMonth`](http://thx-lib.org/api/thx/unit/time/SynodicMonth.html), [`Terasecond`](http://thx-lib.org/api/thx/unit/time/Terasecond.html), [`Third`](http://thx-lib.org/api/thx/unit/time/Third.html), [`TropicalMonth`](http://thx-lib.org/api/thx/unit/time/TropicalMonth.html), [`Week`](http://thx-lib.org/api/thx/unit/time/Week.html).

For now the library essentially helps with conversions and math operations. At some point derivative units might be introduced to make things more interesting.

Also notice that the types are automatically generated. If you want to contribute to the library make sure to make changes in the [definitions](https://github.com/fponticelli/thx.unit/blob/master/definitions/). The code is generated using this [generator](https://github.com/fponticelli/generator).

The library has not been exhaustively tested, please pay attention to the correctness of the results you get.

*Important*. This library should be used with the consciousness that converting values and perform some operations on the values might result in loss of precision. The limitation come from the fact that the underlying type is a `Float`. Converting `LightYear`s to `Millimitre`s might not work as well as you expect!
