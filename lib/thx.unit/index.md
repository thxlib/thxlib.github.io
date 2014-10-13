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
version: 0.3.2
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

  * amount of substance: [`Mole`](/src/thx/unit/amountofsubstance/Mole.hx), [`PoundMole`](/src/thx/unit/amountofsubstance/PoundMole.hx).
  * angle: [`BinaryDegree`](/src/thx/unit/angle/BinaryDegree.hx), [`Degree`](/src/thx/unit/angle/Degree.hx), [`Grad`](/src/thx/unit/angle/Grad.hx), [`HourAngle`](/src/thx/unit/angle/HourAngle.hx), [`MinuteOfArc`](/src/thx/unit/angle/MinuteOfArc.hx), [`Point`](/src/thx/unit/angle/Point.hx), [`Quadrant`](/src/thx/unit/angle/Quadrant.hx), [`Radian`](/src/thx/unit/angle/Radian.hx), [`Revolution`](/src/thx/unit/angle/Revolution.hx), [`SecondOfArc`](/src/thx/unit/angle/SecondOfArc.hx), [`Sextant`](/src/thx/unit/angle/Sextant.hx), [`Turn`](/src/thx/unit/angle/Turn.hx).
  * current: [`Ampere`](/src/thx/unit/current/Ampere.hx).
  * digital: [`Byte`](/src/thx/unit/digital/Byte.hx), [`Exabit`](/src/thx/unit/digital/Exabit.hx), [`Exabyte`](/src/thx/unit/digital/Exabyte.hx), [`Gigabit`](/src/thx/unit/digital/Gigabit.hx), [`Gigabyte`](/src/thx/unit/digital/Gigabyte.hx), [`Kilobit`](/src/thx/unit/digital/Kilobit.hx), [`Kilobyte`](/src/thx/unit/digital/Kilobyte.hx), [`Megabit`](/src/thx/unit/digital/Megabit.hx), [`Megabyte`](/src/thx/unit/digital/Megabyte.hx), [`Petabit`](/src/thx/unit/digital/Petabit.hx), [`Petabyte`](/src/thx/unit/digital/Petabyte.hx), [`Terabit`](/src/thx/unit/digital/Terabit.hx), [`Terabyte`](/src/thx/unit/digital/Terabyte.hx), [`Yottabit`](/src/thx/unit/digital/Yottabit.hx), [`Yottabyte`](/src/thx/unit/digital/Yottabyte.hx), [`Zettabit`](/src/thx/unit/digital/Zettabit.hx), [`Zettabyte`](/src/thx/unit/digital/Zettabyte.hx).
  * length:  [`AstronomicalUnit`](/src/thx/unit/length/AstronomicalUnit.hx), [`Centimeter`](/src/thx/unit/length/Centimeter.hx), [`Centimetre`](/src/thx/unit/length/Centimetre.hx), [`Chain`](/src/thx/unit/length/Chain.hx), [`EarthRadius`](/src/thx/unit/length/EarthRadius.hx), [`Fathom`](/src/thx/unit/length/Fathom.hx), [`Foot`](/src/thx/unit/length/Foot.hx), [`Furlong`](/src/thx/unit/length/Furlong.hx), [`Inch`](/src/thx/unit/length/Inch.hx), [`Kilometer`](/src/thx/unit/length/Kilometer.hx), [`Kilometre`](/src/thx/unit/length/Kilometre.hx), [`League`](/src/thx/unit/length/League.hx), [`LightYear`](/src/thx/unit/length/LightYear.hx), [`Line`](/src/thx/unit/length/Line.hx), [`Meter`](/src/thx/unit/length/Meter.hx), [`Metre`](/src/thx/unit/length/Metre.hx), [`Micrometer`](/src/thx/unit/length/Micrometer.hx), [`Micrometre`](/src/thx/unit/length/Micrometre.hx), [`Mile`](/src/thx/unit/length/Mile.hx), [`Millimeter`](/src/thx/unit/length/Millimeter.hx), [`Millimetre`](/src/thx/unit/length/Millimetre.hx), [`Nanometer`](/src/thx/unit/length/Nanometer.hx), [`Nanometre`](/src/thx/unit/length/Nanometre.hx), [`NauticalMile`](/src/thx/unit/length/NauticalMile.hx), [`Thou`](/src/thx/unit/length/Thou.hx), [`Yard`](/src/thx/unit/length/Yard.hx).
  * luminous intensity: [`Candela`](/src/thx/unit/luminousintensity/Candela.hx), [`Candlepower`](/src/thx/unit/luminousintensity/Candlepower.hx).
  * mass: [`Centigram`](/src/thx/unit/mass/Centigram.hx), [`Dalton`](/src/thx/unit/mass/Dalton.hx), [`Drachm`](/src/thx/unit/mass/Drachm.hx), [`Grain`](/src/thx/unit/mass/Grain.hx), [`Gram`](/src/thx/unit/mass/Gram.hx), [`Hundredweight`](/src/thx/unit/mass/Hundredweight.hx), [`Kilogram`](/src/thx/unit/mass/Kilogram.hx), [`Megagram`](/src/thx/unit/mass/Megagram.hx), [`Microgram`](/src/thx/unit/mass/Microgram.hx), [`Milligram`](/src/thx/unit/mass/Milligram.hx), [`Nanogram`](/src/thx/unit/mass/Nanogram.hx), [`Ounce`](/src/thx/unit/mass/Ounce.hx), [`Picogram`](/src/thx/unit/mass/Picogram.hx), [`PlankMass`](/src/thx/unit/mass/PlankMass.hx), [`Pound`](/src/thx/unit/mass/Pound.hx), [`Quarter`](/src/thx/unit/mass/Quarter.hx), [`Slug`](/src/thx/unit/mass/Slug.hx), [`SolarMass`](/src/thx/unit/mass/SolarMass.hx), [`Stone`](/src/thx/unit/mass/Stone.hx), [`Ton`](/src/thx/unit/mass/Ton.hx), [`Tonne`](/src/thx/unit/mass/Tonne.hx), [`UnifiedAtomicMassUnit`](/src/thx/unit/mass/UnifiedAtomicMassUnit.hx).
  * temperature: [`Celsius`](/src/thx/unit/temperature/Celsius.hx), [`Centrigrade`](/src/thx/unit/temperature/Centrigrade.hx), [`Delisle`](/src/thx/unit/temperature/Delisle.hx), [`Fahrenheit`](/src/thx/unit/temperature/Fahrenheit.hx), [`Kelvin`](/src/thx/unit/temperature/Kelvin.hx), [`Newton`](/src/thx/unit/temperature/Newton.hx), [`Rankine`](/src/thx/unit/temperature/Rankine.hx), [`Reaumur`](/src/thx/unit/temperature/Reaumur.hx), [`Romer`](/src/thx/unit/temperature/Romer.hx).
  * time: [`Centriday`](/src/thx/unit/time/Centriday.hx), [`Day`](/src/thx/unit/time/Day.hx), [`Fortnight`](/src/thx/unit/time/Fortnight.hx), [`Fourth`](/src/thx/unit/time/Fourth.hx), [`Gigasecond`](/src/thx/unit/time/Gigasecond.hx), [`Hour`](/src/thx/unit/time/Hour.hx), [`JiffyPhysics`](/src/thx/unit/time/JiffyPhysics.hx), [`JulianYear`](/src/thx/unit/time/JulianYear.hx), [`Ke`](/src/thx/unit/time/Ke.hx), [`Kilosecond`](/src/thx/unit/time/Kilosecond.hx), [`Megasecond`](/src/thx/unit/time/Megasecond.hx), [`Microsecond`](/src/thx/unit/time/Microsecond.hx), [`Millisecond`](/src/thx/unit/time/Millisecond.hx), [`Minute`](/src/thx/unit/time/Minute.hx), [`Nanosecond`](/src/thx/unit/time/Nanosecond.hx), [`Picosecond`](/src/thx/unit/time/Picosecond.hx), [`PlankTimeUnit`](/src/thx/unit/time/PlankTimeUnit.hx), [`Second`](/src/thx/unit/time/Second.hx), [`Shake`](/src/thx/unit/time/Shake.hx), [`Svedberg`](/src/thx/unit/time/Svedberg.hx), [`SynodicMonth`](/src/thx/unit/time/SynodicMonth.hx), [`Terasecond`](/src/thx/unit/time/Terasecond.hx), [`Third`](/src/thx/unit/time/Third.hx), [`TropicalMonth`](/src/thx/unit/time/TropicalMonth.hx), [`Week`](/src/thx/unit/time/Week.hx).

For now the library essentially helps with conversions and math operations. At some point derivative units might be introduced to make things more interesting.

Also notice that the types are automatically generated. If you want to contribute to the library make sure to make changes in the [definitions](/definitions/). The code is generated using this [generator](https://github.com/fponticelli/generator).

The library has not been exhaustively tested, please pay attention to the correctness of the results you get.

*Important*. This library should be used with the consciousness that converting values and perform some operations on the values might result in loss of precision. The limitation come from the fact that the underlying type is a `Float`. Converting `LightYear`s to `Millimitre`s might not work as well as you expect!
