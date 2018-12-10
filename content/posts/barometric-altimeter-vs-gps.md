---
title: "Barometric Altimeter vs. GPS: A comparison"
date: 2018-12-10T13:46:23+02:00
---

[Universal Altimeter](https://itunes.apple.com/us/app/universal-altimeter/id1439008837?ls=1&mt=8) provides two ways to measure elevation: by utilising iPhones barometric sensor (available in all iPhone models since iPhone 6) and by using GPS receiver. How are they different? When one of these measurement modes is to be preferred over the other? Let's find out!

Barometric altimetry relies on atmospheric pressure measurement. This makes it efficient in terms of battery life, as energy usage of barometric sensor is fairly low. Furthermore, it can be used even when GPS usage is problematic (more on that later). However, barometric altimetry requires periodic recalibration - one must update reference values of altitude, pressure and air temperatures to keep measurements accurate. It is recommended to do so at least daily. This imposes an inconvenience to the user.

GPS altimetry is a special case of GPS geolocation - it relies on signal timing measurement and geometric computations, but only altitude (height above Earth) is being provided to the user. GPS based altimetry does not require calibration, but takes a toll on battery life, as GPS receiver contains some power hungry RF circuitry. Depending on terrain, exact location of the user, atmospheric and weather conditions, receiving signals from GPS satellites might be problematic. For example, the Earth block the direct visibility to satellites, which is necessary for good vertical accuracy. Bad signal reception will cause inaccurate altitude readings. Rule of thumb in geospatial industry is that vertical error of GPS positioning is about three times the horizontal error.

Should you use barometric altimeter feature of our elevation app? Yes, provided that you are able to keep recalibrating to known and trusted reference values of pressure, altitude and air temperature (we provide a convenience feature to do so automatically, but recommend manual calibration whenever possible). This will provide a combination of high accuracy and low power usage, with no need to access any services over internet - great for backcountry or mountain trips.

Should you use GPS-based altimetry? Well, it depends. It does not require calibration, but is far more expensive in terms of energy use and may prove to be unreliable in some situations.


