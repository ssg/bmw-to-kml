# BMW to KML

This is both an interactive web page PWA app, and a PowerShell script that can convert BMW Drive Recorder Metadata.json files 
into Google Earth KML format so it can be inspected on [Google Earth](https://earth.google.com) or other GIS software.

## interactive web page

You can try it out at https://kod.ssg.dev/bmw-to-kml. You can also install
it as a local PWA app if you plan on using it frequently.

## PowerShell script usage

```
.\BMWtoKML -OutputKml somefilename.kml
```

Converts `Metadata.json` in the current directory into `somefilename.kml`.

```
.\BMWtoKML -InputJson PathToMetadata.json -OutputKml blabla.kml
```

Converts `Metadata.json` somewhere else into `blabla.kml`.

(NOTE: BMW Drive Recorder names all JSON files `Metadata.json`)

## license
GNU GPLv3. See [LICENSE](LICENSE) file for details.
