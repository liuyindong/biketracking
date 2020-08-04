# BikeTracking

[__BikeTracking__](https://play.google.com/store/apps/details?id=org.biketracking) is a GPS tracking Android app for cycling activities created by a passionate bicycle developer.

I made this app focusing exclusively on the features that I consider necessary and important on the basis of my experience as an amateur cyclist, eliminating everything superfluous present in other similar apps, such as social sharing, vocal training, location sharing.

In addition, the app keeps GPS tracks inside the device, **without sending and saving your location data on external servers**.

As for the online altitude calculation, for Europe I use a service I created that does not store the coordinates of the users but only uses them to determine the DEM (Digital Elevation Measure) value, while outside Europe I use a similar service provided by MapBox ([see PRIVACY](./PRIVACY.md))

## Features

* measure realtime __distance__, __duration__, __speed__, __average__
* measure __altitude__ online via __DEM__ (Digital Elevation Measuring). For Europe best precision: 25m resolution with vertical accuracy: +/- 7 meters [Copernicus EU-DEM](https://land.copernicus.eu/imagery-in-situ/eu-dem)
* realtime __routing 3D__ on map
* __heartrate__ device integration via BLE (Bluethoot Low Energy)
* __automatic start-stop__
* __voice track summary__
* history of tracks with statistical data, __charts__ and map

## Support Us

* subscribe a tier on [github sponsors](https://github.com/sponsors/heyteacher)
* make a donation on [liberapay](https://liberapay.com/heyteacher)
* use [github issues](https://github.com/heyteacher/biketracking/issues) for __reporting bugs__ or __requesting features__

