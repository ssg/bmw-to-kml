# BMWtoKML

This is a PowerShell script that can convert BMW Drive Recorder Metadata.json files 
into Google Earth KML format so it can be inspected on [Google Earth](https://earth.google.com) or other GIS software.

## usage

```
.\BMWtoKML -InputJson Metadata.json -OutputKml blabla.kml
```

(InputJson parameter can be fully omitted as all JSON files are named "Metadata.json"
with BMW driver recorder)

## license
GNU GPLv3. See [LICENSE](LICENSE) file for details.