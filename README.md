This is a fork of the excellent [joshclark/BlueEyes](https://github.com/joshclark/BlueEyes) repository for timeseries compression using Facebook's "Gorilla" encoding.

The following updates are available in this fork:

- Negative value handling
- Bug fix for some initial values
- Aligned control bit usage with paper linked below
- Upgdated to netcore3.0

Due to inactivity on the main branch, I've published this fork on a new Nuget feed:

[![Nuget](https://img.shields.io/nuget/v/GorillaDotNet)](https://www.nuget.org/packages/GorillaDotNet/)

---

A .NET implementation of the [paper “Gorilla: A Fast, Scalable, In-Memory Time Series Database”](http://www.vldb.org/pvldb/vol8/p1816-teller.pdf) 

This is implmentation is based on Facebook's open source implementation of this paper: [Beringei](https://github.com/facebookincubator/beringei/)
