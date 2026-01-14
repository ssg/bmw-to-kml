# BMW to KML

This is both an interactive web page PWA app, and a PowerShell script that can convert BMW Drive Recorder Metadata.json files 
into Google Earth KML format so it can be inspected on [Google Earth](https://earth.google.com) or other GIS software.

<img width="800" height="480" alt="screenshot of google earth showing BMW drive recorder data" src="https://github.com/user-attachments/assets/2ba05990-dbba-42e1-8a64-8b8748956813" />

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
