# BMWtoKML

This is a PowerShell script that can convert BMW Drive Recorder Metadata.json files 
into Google Earth KML format so it can be inspected on [Google Earth](https://earth.google.com) or other GIS software.

## usage

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
