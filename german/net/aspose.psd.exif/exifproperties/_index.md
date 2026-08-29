---
title: "Enum ExifProperties"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Exif.ExifProperties Enum. Liste der Exif-Tags"
type: docs
weight: 1010
url: /de/net/aspose.psd.exif/exifproperties/
---
{{< psd/tize >}}
## ExifProperties enumeration

Exif-Tag-Liste

```csharp
public enum ExifProperties : ushort
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ImageWidth | `256` | Die Anzahl der Spalten von Bilddaten, gleich der Anzahl der Pixel pro Zeile. |
| ImageLength | `257` | Die Anzahl der Zeilen der Bilddaten. |
| BitsPerSample | `258` | Die Anzahl der Bits pro Bildkomponente. In diesem Standard ist jede Komponente des Bildes 8 Bit, daher ist der Wert für dieses Tag 8. |
| Compression | `259` | Das Komprimierungsschema, das für die Bilddaten verwendet wird. Wenn ein primäres Bild JPEG-komprimiert ist, ist diese Bezeichnung nicht erforderlich und wird weggelassen. |
| PhotometricInterpretation | `262` | Die Pixelzusammensetzung. |
| ImageDescription | `270` | Eine Zeichenkette, die den Titel des Bildes angibt. Sie kann ein Kommentar wie "1988 Firmenpicknick" oder Ähnliches sein. |
| Make | `271` | Der Hersteller der Aufzeichnungsgeräte. Dies ist der Hersteller des DSC, Scanners, Video-Digitalisierers oder anderer Geräte, die das Bild erzeugt haben. Wenn das Feld leer gelassen wird, gilt es als unbekannt. |
| Model | `272` | Der Modellname oder die Modellnummer des Geräts. Dies ist der Modellname oder die Nummer des DSC, Scanners, Video-Digitalisierers oder anderer Geräte, die das Bild erzeugt haben. Wenn das Feld leer gelassen wird, gilt es als unbekannt. |
| Orientation | `274` | Die Bildorientierung, betrachtet in Bezug auf Zeilen und Spalten. |
| SamplesPerPixel | `277` | Die Anzahl der Komponenten pro Pixel. Da dieser Standard für RGB- und YCbCr-Bilder gilt, ist der für dieses Tag festgelegte Wert 3. |
| XResolution | `282` | Die Anzahl der Pixel pro Auflösungseinheit in Richtung Bildbreite. Wenn die Bildauflösung unbekannt ist, wird 72 [dpi] angegeben. |
| YResolution | `283` | Die Anzahl der Pixel pro Auflösungseinheit in Richtung Bildlänge. Der gleiche Wert wie bei XResolution wird angegeben. |
| PlanarConfiguration | `284` | Gibt an, ob Pixelkomponenten im Chunky- oder Planarformat aufgezeichnet werden. Wenn dieses Feld nicht existiert, wird der TIFF-Standardwert 1 (Chunky) angenommen. |
| ResolutionUnit | `296` | Die Einheit zur Messung von XResolution und YResolution. Für beide wird dieselbe Einheit verwendet. Wenn die Bildauflösung unbekannt ist, wird 2 (Zoll) angegeben. |
| TransferFunction | `301` | Eine Transferfunktion für das Bild, beschrieben in tabellarischer Form. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum im Farbraum-Informations-Tag ColorSpace angegeben wird. |
| Software | `305` | Dieses Tag zeichnet den Namen und die Version der Software oder Firmware der Kamera oder des Bildaufnahmegeräts auf, das das Bild erzeugt hat. Das genaue Format ist nicht festgelegt, es wird jedoch empfohlen, dem unten gezeigten Beispiel zu folgen. Wenn das Feld leer gelassen wird, gilt es als unbekannt. |
| DateTime | `306` | Datum und Uhrzeit der Bild­erstellung. Im Exif‑Standard ist dies das Datum und die Uhrzeit, zu der die Datei geändert wurde. |
| Artist | `315` | Dieses Tag zeichnet den Namen des Kamerabesitzers, Fotografen oder Bildschöpfers auf. Das genaue Format ist nicht festgelegt, es wird jedoch empfohlen, die Informationen wie im unten stehenden Beispiel für bessere Interoperabilität zu schreiben. Wenn das Feld leer gelassen wird, gilt es als unbekannt. Beispiel: "Kamerabesitzer, John Smith; Fotograf, Michael Brown; Bildschöpfer, Ken James" |
| WhitePoint | `318` | Die Chromatik des Weißpunkts des Bildes. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum im Farbraum‑Informations‑Tag ColorSpace angegeben wird. |
| PrimaryChromaticities | `319` | Die Chromatik der drei Primärfarben des Bildes. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum im Farbraum‑Informations‑Tag ColorSpace angegeben wird. |
| YCbCrCoefficients | `529` | Die Matrixkoeffizienten für die Transformation von RGB- zu YCbCr-Bilddaten. |
| YCbCrSubSampling | `530` | Das Abtastverhältnis der Chrominanzkomponenten im Verhältnis zur Luminanzkomponente. |
| YCbCrPositioning | `531` | Die Position der Chrominanzkomponenten im Verhältnis zur Luminanzkomponente. Dieses Feld ist nur für JPEG‑komprimierte Daten oder unkomprimierte YCbCr‑Daten vorgesehen. Der TIFF‑Standardwert ist 1 (zentriert); bei Y:Cb:Cr = 4:2:2 wird in diesem Standard empfohlen, 2 (nebeneinander) zu verwenden, um Daten zu speichern, um die Bildqualität bei Anzeige auf TV‑Systemen zu verbessern. Existiert dieses Feld nicht, muss der Leser den TIFF‑Standardwert annehmen. Im Fall von Y:Cb:Cr = 4:2:0 wird der TIFF‑Standardwert (zentriert) empfohlen. Wenn der Leser nicht in der Lage ist, beide Arten von YCbCrPositioning zu unterstützen, muss er unabhängig vom Wert in diesem Feld dem TIFF‑Standardwert folgen. Es ist vorzuziehen, dass Leser \" in der Lage sind, sowohl zentrierte als auch nebeneinander liegende Positionierung zu unterstützen. |
| ReferenceBlackWhite | `532` | Der Referenzschwarzpunktwert und der Referenzweißpunktwert. In TIFF werden keine Vorgaben gemacht, aber die untenstehenden Werte werden hier als Vorgaben angegeben. Der Farbraum wird in einem Farbraum‑Informations‑Tag deklariert, wobei der Standardwert derjenige ist, der die optimalen Bildmerkmale für Interoperabilität unter diesen Bedingungen liefert. |
| Copyright | `33432` | Copyright-Information. In diesem Standard wird das Tag verwendet, um sowohl die Urheberrechte des Fotografen als auch des Editors anzugeben. Es ist der Urheberrechtshinweis der Person oder Organisation, die Rechte an dem Bild beansprucht. Die Interoperabilitäts‑Urheberrechtserklärung inklusive Datum und Rechte sollte in diesem Feld geschrieben werden; z. B. \"Copyright, John Smith, 19xx. All rights reserved.\". In diesem Standard zeichnet das Feld sowohl die Urheberrechte des Fotografen als auch des Editors auf, wobei jeder Teil der Erklärung separat gespeichert wird. Wenn eine klare Unterscheidung zwischen den Urheberrechten des Fotografen und des Editors besteht, werden sie in der Reihenfolge Fotograf gefolgt vom Editor‑Urheberrecht geschrieben, getrennt durch NULL (in diesem Fall, da die Erklärung ebenfalls mit einem NULL endet, gibt es zwei NULL‑Codes). Wenn nur das Urheberrecht des Fotografen angegeben ist, wird es durch einen NULL‑Code beendet. Wenn nur das Urheberrecht des Editors angegeben ist, besteht der Fotograf‑Urheberrechtsteil aus einem Leerzeichen, gefolgt von einem abschließenden NULL‑Code, danach wird das Editor‑Urheberrecht angegeben. Wenn das Feld leer gelassen wird, gilt es als unbekannt. |
| ExposureTime | `33434` | Belichtungszeit, angegeben in Sekunden. |
| FNumber | `33437` | Die Blendenzahl. |
| ExposureProgram | `34850` | Die Klasse des Programms, das von der Kamera verwendet wird, um die Belichtung beim Aufnehmen des Bildes einzustellen. |
| SpectralSensitivity | `34852` | Gibt die spektrale Empfindlichkeit jedes Kanals der verwendeten Kamera an. |
| PhotographicSensitivity | `34855` | Gibt die ISO‑Geschwindigkeit und ISO‑Latitud der Kamera oder des Eingabegeräts an, wie in ISO 12232 festgelegt. |
| OECF | `34856` | Gibt die opto‑elektrische Umwandlungsfunktion (OECF) an, wie in ISO 14524 spezifiziert. |
| ExifVersion | `36864` | Die EXIF‑Version. |
| DateTimeOriginal | `36867` | Datum und Uhrzeit, zu denen die Original‑Bilddaten erzeugt wurden. |
| DateTimeDigitized | `36868` | Das Digitalisierungsdatum und die -uhrzeit. |
| ComponentsConfiguration | `37121` | Die Komponenten‑Konfiguration. |
| CompressedBitsPerPixel | `37122` | Spezifisch für komprimierte Daten; gibt die komprimierten Bits pro Pixel an. |
| ShutterSpeedValue | `37377` | Der Wert der Verschlusszeit. |
| ApertureValue | `37378` | Der Wert der Objektivblende. |
| BrightnessValue | `37379` | Der Helligkeitswert. |
| ExposureBiasValue | `37380` | Der Belichtungswert. |
| MaxApertureValue | `37381` | Der maximale Blendenwert. |
| SubjectDistance | `37382` | Der Abstand zum Motiv, angegeben in Metern. |
| MeteringMode | `37383` | Der Messmodus. |
| LightSource | `37384` | Die sanfte Lichtquelle. |
| Flash | `37385` | Gibt den Blitzstatus zum Zeitpunkt der Aufnahme an. |
| FocalLength | `37386` | Die tatsächliche Brennweite des Objektivs in mm. |
| SubjectArea | `37396` | Dieses Tag gibt den Ort und den Bereich des Hauptmotivs in der gesamten Szene an. |
| MakerNote | `37500` | Ein Tag für Hersteller von Exif-Schreibern, um beliebige gewünschte Informationen zu speichern. Der Inhalt liegt im Ermessen des Herstellers, aber dieses Tag sollte nicht für andere Zwecke als den vorgesehenen verwendet werden. |
| UserComment | `37510` | Ein Tag für Exif‑Benutzer, um Schlüsselwörter oder Kommentare zum Bild zu schreiben, zusätzlich zu denen in ImageDescription, und ohne die Zeichenkodierungsbeschränkungen des ImageDescription‑Tags. |
| SubsecTime | `37520` | Ein Tag, das Bruchteile von Sekunden für das DateTime‑Tag speichert. |
| SubsecTimeOriginal | `37521` | Ein Tag, das Bruchteile von Sekunden für das DateTimeOriginal‑Tag speichert. |
| SubsecTimeDigitized | `37522` | Ein Tag, das Bruchteile von Sekunden für das DateTimeDigitized‑Tag speichert. |
| FlashpixVersion | `40960` | Die von einer FPXR‑Datei unterstützte Flashpix‑Formatversion. |
| ColorSpace | `40961` | Das Farb‑Raum‑Informations‑Tag (ColorSpace) wird stets als Farbraumspezifizierer gespeichert. |
| RelatedSoundFile | `40964` | Die zugehörige Audiodatei. |
| FlashEnergy | `41483` | Gibt die Blitzenergie zum Zeitpunkt der Aufnahme an, gemessen in Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Dieses Tag zeichnet die räumliche Frequenztafel und SFR‑Werte der Kamera oder des Eingabegeräts in Richtung Bildbreite, Bildhöhe und Diagonalrichtung auf, wie in ISO 12233 angegeben. |
| FocalPlaneXResolution | `41486` | Gibt die Anzahl der Pixel in Bildbreite‑Richtung (X) pro FocalPlaneResolutionUnit auf der Kamera‑Bildebene an. |
| FocalPlaneYResolution | `41487` | Gibt die Anzahl der Pixel in Bildhöhe‑Richtung (Y) pro FocalPlaneResolutionUnit auf der Kamera‑Bildebene an. |
| FocalPlaneResolutionUnit | `41488` | Gibt die Einheit zur Messung von FocalPlaneXResolution und FocalPlaneYResolution an. Dieser Wert entspricht dem ResolutionUnit. |
| SubjectLocation | `41492` | Gibt den Ort des Hauptmotivs in der Szene an. Der Wert dieses Tags stellt das Pixel im Zentrum des Hauptmotivs relativ zur linken Kante dar, vor der Rotationsverarbeitung gemäß dem Rotation‑Tag. |
| ExposureIndex | `41493` | Gibt den zum Zeitpunkt der Aufnahme gewählten Belichtungsindex der Kamera oder des Eingabegeräts an. |
| SensingMethod | `41495` | Gibt den Bildsensorsystemtyp der Kamera oder des Eingabegeräts an. |
| FileSource | `41728` | Die Dateiquelle. |
| SceneType | `41729` | Gibt den Szenentyp an. Wenn ein DSC das Bild aufgenommen hat, muss dieser Tag‑Wert stets auf 1 gesetzt sein, was bedeutet, dass das Bild direkt fotografiert wurde. |
| CFAPattern | `41730` | Gibt das geometrische Muster des Farbfilterarrays (CFA) des Bildsensors an, wenn ein Ein-Chip‑Farbflächen‑Sensor verwendet wird. Es gilt nicht für alle Sensormethoden. |
| CustomRendered | `41985` | Dieses Tag gibt die Verwendung spezieller Verarbeitung von Bilddaten an, z. B. für die Ausgabe optimiertes Rendering. Wird eine spezielle Verarbeitung durchgeführt, sollte der Leser weitere Verarbeitungen deaktivieren oder minimieren. |
| ExposureMode | `41986` | Dieses Tag gibt den beim Aufnehmen eingestellten Belichtungsmodus an. Im Auto‑Bracketing‑Modus nimmt die Kamera eine Reihe von Aufnahmen derselben Szene mit unterschiedlichen Belichtungseinstellungen auf. |
| WhiteBalance | `41987` | Dieses Tag gibt den Weißabgleichmodus an, der beim Aufnehmen des Bildes eingestellt wurde. |
| DigitalZoomRatio | `41988` | Dieses Tag gibt das digitale Zoomverhältnis beim Aufnehmen des Bildes an. Ist der Zähler des aufgezeichneten Wertes 0, bedeutet dies, dass kein digitaler Zoom verwendet wurde. |
| FocalLengthIn35MmFilm | `41989` | Dieses Tag gibt die äquivalente Brennweite an, angenommen eine 35‑mm-Filmkamera, in mm. Ein Wert von 0 bedeutet, dass die Brennweite unbekannt ist. Hinweis: Dieses Tag unterscheidet sich vom Tag FocalLength. |
| SceneCaptureType | `41990` | Dieses Tag gibt den Typ der aufgenommenen Szene an. Es kann auch verwendet werden, um den Aufnahmemodus des Bildes zu speichern. |
| GainControl | `41991` | Dieses Tag gibt den Grad der Gesamtabstimmung der Bildverstärkung an. |
| Contrast | `41992` | Dieses Tag gibt die Richtung der vom Kamerasystem beim Aufnehmen des Bildes angewendeten Kontrastverarbeitung an. |
| Saturation | `41993` | Dieses Tag gibt die Richtung der vom Kamerasystem beim Aufnehmen des Bildes angewendeten Sättigungsverarbeitung an. |
| Sharpness | `41994` | Dieses Tag gibt die Richtung der vom Kamerasystem beim Aufnehmen des Bildes angewendeten Schärfungsverarbeitung an. |
| DeviceSettingDescription | `41995` | Dieses Tag gibt Informationen zu den Aufnahmebedingungen eines bestimmten Kameramodells an. Das Tag wird nur verwendet, um die Aufnahmebedingungen im Reader anzuzeigen. |
| SubjectDistanceRange | `41996` | Dieses Tag gibt die Entfernung zum Motiv an. |
| ImageUniqueID | `42016` | Die eindeutige Bild‑ID. |
| GPSVersionID | `0` | Gibt die Version von GPSInfoIFD an. |
| GPSLatitudeRef | `1` | Gibt an, ob die Breite nördlich oder südlich ist. |
| GPSLatitude | `2` | Gibt die Breite an. Die Breite wird als drei RATIONAL‑Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen. Wird die Breite in Grad, Minuten und Sekunden ausgedrückt, hat das typische Format dd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Minutenbruchteile bis zu zwei Dezimalstellen angegeben, lautet das Format dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Gibt an, ob die Länge östlich oder westlich ist. |
| GPSLongitude | `4` | Gibt die Länge an. Die Länge wird als drei RATIONAL‑Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen. Wird die Länge in Grad, Minuten und Sekunden ausgedrückt, hat das typische Format ddd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Minutenbruchteile bis zu zwei Dezimalstellen angegeben, lautet das Format ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Gibt die als Referenz verwendete Höhe an. Ist die Referenz Meereshöhe und liegt die Höhe über dem Meeresspiegel, wird 0 angegeben. Liegt die Höhe unter dem Meeresspiegel, wird der Wert 1 angegeben und die Höhe wird als absoluter Wert im Tag GPSAltitude angegeben. |
| GPSAltitude | `6` | Gibt die Höhe basierend auf der Referenz in GPSAltitudeRef an. Die Höhe wird als ein RATIONAL‑Wert angegeben. Die Referenzeinheit ist Meter. |
| GPSTimestamp | `7` | Gibt die Zeit als UTC (Coordinated Universal Time) an. Der Zeitstempel wird als drei RATIONAL‑Werte angegeben, die Stunde, Minute und Sekunde darstellen. |
| GPSSatellites | `8` | Gibt die für Messungen verwendeten GPS‑Satelliten an. Dieses Tag kann verwendet werden, um die Anzahl der Satelliten, deren ID‑Nummer, Elevationswinkel, Azimut, SNR und weitere Informationen in ASCII‑Notation zu beschreiben. Das Format ist nicht festgelegt. Ist der GPS‑Empfänger nicht in der Lage, Messungen durchzuführen, muss der Tag‑Wert auf NULL gesetzt werden. |
| GPSStatus | `9` | Gibt den Status des GPS‑Empfängers zum Zeitpunkt der Bildaufnahme an. |
| GPSMeasureMode | `10` | Gibt den GPS-Messmodus an. - 2- oder 3- dimensional. |
| GPSDOP | `11` | Gibt den GPS-DOP (Datengrad der Präzision) an. Ein HDOP‑Wert wird bei zweidimensionaler Messung geschrieben und ein PDOP‑Wert bei dreidimensionaler Messung. |
| GPSSpeedRef | `12` | Gibt die Einheit an, die zur Angabe der Geschwindigkeit des GPS‑Empfängers verwendet wird. 'K', 'M' und 'N' stehen für Kilometer pro Stunde, Meilen pro Stunde und Knoten. |
| GPSSpeed | `13` | Gibt die Geschwindigkeit der GPS‑Empfängerbewegung an. |
| GPSTrackRef | `14` | Gibt die Referenz für die Angabe der Richtung der GPS‑Empfängerbewegung an. 'T' bezeichnet die wahre Richtung und 'M' die magnetische Richtung. |
| GPSTrack | `15` | Gibt die Richtung der GPS‑Empfängerbewegung an. Der Wertebereich liegt zwischen 0.00 und 359.99. |
| GPSImgDirectionRef | `16` | Gibt die Referenz für die Angabe der Bildrichtung bei der Aufnahme an. 'T' bezeichnet die wahre Richtung und 'M' die magnetische Richtung. |
| GPSImgDirection | `17` | Gibt die Richtung des Bildes bei der Aufnahme an. Der Wertebereich liegt zwischen 0.00 und 359.99. |
| GPSMapDatum | `18` | Gibt die vom GPS‑Empfänger verwendeten geodätischen Vermessungsdaten an. |
| GPSDestLatitudeRef | `19` | Gibt an, ob die Breite des Zielpunkts nördliche oder südliche Breite ist. Der ASCII‑Wert 'N' steht für nördliche Breite, und 'S' für südliche Breite. |
| GPSDestLatitude | `20` | Gibt die Breite des Zielpunkts an. Die Breite wird als drei RATIONAL‑Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen. Wenn die Breite in Grad, Minuten und Sekunden ausgedrückt wird, wäre ein typisches Format dd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Minutenbruchteile bis zu zwei Dezimalstellen angegeben, lautet das Format dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Gibt an, ob die Länge des Zielpunkts östliche oder westliche Länge ist. ASCII 'E' steht für östliche Länge, und 'W' für westliche Länge. |
| GPSDestLongitude | `22` | Gibt die Länge des Zielpunkts an. Die Länge wird als drei RATIONAL‑Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen. Wenn die Länge in Grad, Minuten und Sekunden ausgedrückt wird, wäre ein typisches Format ddd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Minutenbruchteile bis zu zwei Dezimalstellen angegeben, lautet das Format ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Gibt die für die Angabe des Kurses zum Zielpunkt verwendete Referenz an. 'T' bezeichnet die wahre Richtung und 'M' die magnetische Richtung. |
| GPSDestBearing | `24` | Gibt den Kurs zum Zielpunkt an. Der Wertebereich liegt zwischen 0.00 und 359.99. |
| GPSDestDistanceRef | `25` | Gibt die Einheit an, die zur Angabe der Entfernung zum Zielpunkt verwendet wird. 'K', 'M' und 'N' stehen für Kilometer, Meilen und Knoten. |
| GPSDestDistance | `26` | Gibt die Entfernung zum Zielpunkt an. |
| GPSProcessingMethod | `27` | Eine Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet. Das erste Byte gibt den verwendeten Zeichencode an, gefolgt vom Namen der Methode. |
| GPSAreaInformation | `28` | Eine Zeichenkette, die den Namen des GPS‑Gebiets aufzeichnet. Das erste Byte gibt den verwendeten Zeichencode an, gefolgt vom Namen des GPS‑Gebiets. |
| GPSDateStamp | `29` | Eine Zeichenkette, die Datums- und Zeitinformationen relativ zu UTC (Coordinated Universal Time) aufzeichnet. Das Format ist JJJJ:MM:TT. |
| GPSDifferential | `30` | Gibt an, ob eine Differenzkorrektur auf den GPS‑Empfänger angewendet wird. |
| StripOffsets | `273` | Für jeden Streifen den Byte-Offset dieses Streifens. Es wird empfohlen, diesen so zu wählen, dass die Anzahl der Streifen-Bytes 64 KB nicht überschreitet. Aux-Tag. |
| JPEGInterchangeFormat | `513` | Der Offset zum Startbyte (SOI) der JPEG‑komprimierten Vorschaudaten. Dieser wird nicht für die primären JPEG‑Bilddaten verwendet. |
| JPEGInterchangeFormatLength | `514` | Die Anzahl der Bytes der JPEG‑komprimierten Vorschaudaten. Dieser wird nicht für die primären JPEG‑Bilddaten verwendet. JPEG‑Vorschaubilder werden nicht aufgeteilt, sondern als durchgehender JPEG‑Bitstrom vom SOI bis zum EOI aufgezeichnet. Appn‑ und COM‑Marker sollten nicht aufgezeichnet werden. Komprimierte Vorschaubilder müssen in nicht mehr als 64 KB aufgezeichnet werden, einschließlich aller anderen Daten, die in APP1 aufgezeichnet werden sollen. |
| ExifIfdPointer | `34665` | Ein Zeiger auf das Exif‑IFD. Interoperabilität, das Exif‑IFD hat dieselbe Struktur wie das im TIFF spezifizierte IFD. Gewöhnlich enthält es jedoch keine Bilddaten, wie im Fall von TIFF. |
| GPSIfdPointer | `34853` | Der GPS‑IFD‑Zeiger. |
| RowsPerStrip | `278` | Die Anzahl der Zeilen pro Streifen. Dies ist die Zeilenanzahl im Bild eines Streifens, wenn ein Bild in Streifen aufgeteilt wird. |
| StripByteCounts | `279` | Die Gesamtzahl der Bytes in jedem Streifen. |
| PixelXDimension | `40962` | Informationen, die sich speziell auf komprimierte Daten beziehen. Wenn eine komprimierte Datei aufgezeichnet wird, soll die gültige Breite des sinnvollen Bildes in diesem Tag gespeichert werden, unabhängig davon, ob Padding‑Daten oder ein Neustart‑Marker vorhanden sind. |
| PixelYDimension | `40963` | Informationen, die sich speziell auf komprimierte Daten beziehen. Wenn eine komprimierte Datei aufgezeichnet wird, soll die gültige Höhe des sinnvollen Bildes in diesem Tag gespeichert werden. |
| Gamma | `42240` | Gamma‑Wert |
| SensitivityType | `34864` | Typ der fotografischen Empfindlichkeit |
| StandardOutputSensitivity | `34865` | Gibt die standardmäßige Ausgangsempfindlichkeit der Kamera an |
| RecommendedExposureIndex | `34866` | Gibt den empfohlenen Belichtungsindex an |
| ISOSpeed | `34867` | Informationen zum ISO‑Geschwindigkeitswert gemäß ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Dieses Tag gibt den ISO‑Geschwindigkeits‑Latitude‑YYY‑Wert gemäß ISO 12232 an |
| ISOSpeedLatitudeZZZ | `34869` | Dieses Tag gibt den ISO‑Geschwindigkeits‑Latitude‑ZZZ‑Wert gemäß ISO 12232 an |
| CameraOwnerName | `42032` | Enthält den Namen des Kamerabesitzers |
| BodySerialNumber | `42033` | Enthält die Seriennummer des Kameragehäuses |
| LensMake | `42035` | Dieses Tag zeichnet den Linsenhersteller auf |
| LensModel | `42036` | Dieses Tag zeichnet den Modellnamen und die Modellnummer des Objektivs auf |
| LensSerialNumber | `42037` | Dieses Tag zeichnet die Seriennummer des austauschbaren Objektivs auf |
| LensSpecification | `42034` | Dieses Tag gibt die minimale Brennweite, die maximale Brennweite, die minimale Blendenzahl bei der minimalen Brennweite und die minimale Blendenzahl bei der maximalen Brennweite an |

### Siehe auch

* namespace [Aspose.PSD.Exif](../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../)


