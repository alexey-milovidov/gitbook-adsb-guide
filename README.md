# ADS-B Reception, Decoding & Sharing with Docker

Automatic Dependent Surveillance-Broadcast \(ADS-B\) is a surveillance technology in which an aircraft determines its position via satellite navigation and periodically broadcasts it, enabling it to be tracked.

This ADSB-B data can be received by ~~nerds~~ enthusiasts using Software Defined Radio \(SDR\), and used for fun and profit. For example:

**Fun:**

* [ADSBExchange](https://adsbexchange.com/)
* [OpenSky Network](https://opensky-network.org)
* [ADSBHub](https://www.adsbhub.org)
* [https://plane.watch/](https://plane.watch/)
* [https://twinfan.gitbook.io/livetraffic/](https://twinfan.gitbook.io/livetraffic/)

**Profit:**

* [https://flightaware.com/adsb/piaware/](https://flightaware.com/adsb/piaware/)
* [https://www.flightradar24.com/share-your-data](https://www.flightradar24.com/share-your-data)
* [https://www.radarbox.com](https://www.radarbox.com)
* [https://planefinder.net](https://planefinder.net)

This guide will walk you through the process to deploy and configure Docker containers to allow reception and decoding of ADS-B data, as well as submission to various flight tracking services, both open and commercial, and the visualisation of this data.

This guide is made available under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).



