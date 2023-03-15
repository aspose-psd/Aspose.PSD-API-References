---
title: Enum ExifProperties
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Exif.ExifProperties opsomming. Exiftaglijst
type: docs
weight: 1000
url: /nl/net/aspose.psd.exif/exifproperties/
---
## ExifProperties enumeration

Exif-taglijst

```csharp
public enum ExifProperties : ushort
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| ImageWidth | `256` | Het aantal kolommen met afbeeldingsgegevens, gelijk aan het aantal pixels per rij. |
| ImageLength | `257` | Het aantal rijen afbeeldingsgegevens. |
| BitsPerSample | `258` | Het aantal bits per afbeeldingscomponent. In deze standaard is elk onderdeel van de afbeelding 8 bits, dus de waarde voor deze tag is 8. |
| Compression | `259` | Het compressieschema dat wordt gebruikt voor de afbeeldingsgegevens. Wanneer een primaire afbeelding JPEG-gecomprimeerd is, is deze aanduiding niet nodig en wordt deze weggelaten. |
| PhotometricInterpretation | `262` | De pixelsamenstelling. |
| ImageDescription | `270` | Een tekenreeks die de titel van de afbeelding aangeeft. Het kan een opmerking zijn zoals "Bedrijfspicknick uit 1988" of iets dergelijks. |
| Make | `271` | De fabrikant van de opnameapparatuur. Dit is de fabrikant van de DSC, scanner, videodigitizer of andere apparatuur die het beeld heeft gegenereerd. Als het veld leeg wordt gelaten, wordt het behandeld als onbekend. |
| Model | `272` | De modelnaam of het modelnummer van het apparaat. Dit is de modelnaam of het nummer van de DSC, scanner, videodigitizer of andere apparatuur die de afbeelding heeft gegenereerd. Als het veld leeg wordt gelaten, wordt het behandeld als onbekend. |
| Orientation | `274` | De afbeeldingsoriëntatie weergegeven in termen van rijen en kolommen. |
| SamplesPerPixel | `277` | Het aantal componenten per pixel. Aangezien deze standaard van toepassing is op RGB- en YCbCr-afbeeldingen, is de ingestelde waarde voor deze tag 3. |
| XResolution | `282` | Het aantal pixels per ResolutionUnit in de richting ImageWidth. Wanneer de afbeeldingsresolutie onbekend is, wordt 72 [dpi] aangeduid. |
| YResolution | `283` | Het aantal pixels per ResolutionUnit in de richting ImageLength. Dezelfde waarde als XResolution wordt aangeduid. |
| PlanarConfiguration | `284` | Geeft aan of pixelcomponenten zijn vastgelegd in een chunky of planar formaat. Als dit veld niet bestaat, wordt aangenomen dat de TIFF-standaard 1 (chunky) is. |
| ResolutionUnit | `296` | De eenheid voor het meten van XResolution en YResolution. Dezelfde eenheid wordt gebruikt voor zowel XResolution als YResolution. Als de beeldresolutie onbekend is, wordt 2 (inch) aangeduid. |
| TransferFunction | `301` | Een overdrachtsfunctie voor de afbeelding, beschreven in tabelvorm. Normaal gesproken is deze tag niet nodig, aangezien de kleurruimte wordt gespecificeerd in de kleurruimte-informatie ColorSpace-tag. |
| Software | `305` | Deze tag registreert de naam en versie van de software of firmware van de camera of het beeldinvoerapparaat dat is gebruikt om het beeld te genereren. Het gedetailleerde formaat wordt niet gespecificeerd, maar het wordt aanbevolen om het onderstaande voorbeeld te volgen. Als het veld leeg wordt gelaten, wordt het behandeld als onbekend. |
| DateTime | `306` | De datum en tijd waarop de afbeelding is gemaakt. In Exif-standaard is dit de datum en tijd waarop het bestand is gewijzigd. |
| Artist | `315` | Deze tag registreert de naam van de camera-eigenaar, fotograaf of beeldmaker. Het gedetailleerde formaat is niet gespecificeerd, maar het wordt aanbevolen om de informatie te schrijven zoals in het onderstaande voorbeeld om interoperabiliteit te vergemakkelijken. Als het veld leeg wordt gelaten, wordt het behandeld als onbekend. Bijv.) "Camera-eigenaar, John Smith; Fotograaf, Michael Brown; Beeldmaker, Ken James" |
| WhitePoint | `318` | De kleurkwaliteit van het witpunt van de afbeelding. Normaal gesproken is deze tag niet nodig, aangezien de kleurruimte wordt gespecificeerd in de kleurruimte-informatie ColorSpace-tag. |
| PrimaryChromaticities | `319` | De kleurkwaliteit van de drie primaire kleuren van de afbeelding. Normaal gesproken is deze tag niet nodig, aangezien de kleurruimte wordt opgegeven in de kleurruimte-informatie ColorSpace-tag. |
| YCbCrCoefficients | `529` | De matrixcoëfficiënten voor transformatie van RGB- naar YCbCr-beeldgegevens. |
| YCbCrSubSampling | `530` | De bemonsteringsratio van chrominantiecomponenten in relatie tot de luminantiecomponent. |
| YCbCrPositioning | `531` | De positie van chrominantiecomponenten ten opzichte van de luminantiecomponent. Dit veld is alleen bestemd voor JPEG-gecomprimeerde gegevens of niet-gecomprimeerde YCbCr-gegevens. De standaard TIFF is 1 (gecentreerd); maar wanneer Y:Cb:Cr = 4:2:2 wordt in deze standaard aanbevolen om 2 (co-sited) te gebruiken om gegevens op te nemen, om de beeldkwaliteit te verbeteren bij weergave op tv-systemen. Als dit veld niet bestaat, zal de lezer de TIFF-standaard aannemen. In het geval van Y:Cb:Cr = 4:2:0, wordt de standaardwaarde TIFF (gecentreerd) aanbevolen. Als de reader niet in staat is om beide soorten YCbCrPositioning te ondersteunen, zal hij de TIFF-standaard volgen, ongeacht van de waarde in dit veld. Het verdient de voorkeur dat lezers " zowel gecentreerde als co-sited positionering kunnen ondersteunen. |
| ReferenceBlackWhite | `532` | De referentie zwartpuntwaarde en referentie witpunt waarde. In TIFF worden geen standaardwaarden gegeven, maar de onderstaande waarden worden hier als standaardwaarden gegeven. De kleurruimte wordt gedeclareerd in een informatielabel voor de kleurruimte, waarbij default de waarde is die de optimale afbeeldingskenmerken geeft Interoperabiliteit deze voorwaarden |
| Copyright | `33432` | Copyright-informatie. In deze standaard wordt de tag gebruikt om de auteursrechten van zowel de fotograaf als de redacteur aan te geven. Het is de copyrightmelding van de persoon of organisatie die claimt de rechten op de afbeelding. De interoperabiliteit copyright -verklaring inclusief datum en rechten moet in dit -veld worden geschreven; bijv. "Copyright, John Smith, 19xx. Alle rechten voorbehouden.". In deze standaard legt het veld de copyrights van zowel de fotograaf als de redacteur vast, elk vastgelegd in een apart deel van de verklaring. Wanneer er een duidelijk onderscheid is tussen de fotograaf en de editor copyrights, moeten deze worden geschreven in de volgorde van fotograaf gevolgd door editor copyright, gescheiden door NULL (in dit geval omdat de verklaring ook eindigt met een NULL, zijn er twee NULL codes ). Wanneer alleen het copyright van photograph wordt gegeven, wordt het beëindigd door één NULL-code. Wanneer alleen het copyright van de editor wordt gegeven, bestaat het copyright van de fotograaf part uit één spatie gevolgd door een afsluitende NULL-code, then wordt het copyright van de editor gegeven. Als het veld leeg wordt gelaten, wordt het behandeld als onbekend. |
| ExposureTime | `33434` | Belichtingstijd, gegeven in seconden. |
| FNumber | `33437` | Het F-nummer. |
| ExposureProgram | `34850` | De klasse van het programma dat door de camera wordt gebruikt om de belichting in te stellen wanneer de foto wordt gemaakt. |
| SpectralSensitivity | `34852` | Geeft de spectrale gevoeligheid aan van elk kanaal van de gebruikte camera. |
| PhotographicSensitivity | `34855` | Geeft de ISO-snelheid en ISO-breedtegraad van de camera of het invoerapparaat aan zoals gespecificeerd in ISO 12232. |
| OECF | `34856` | Geeft de opto-elektrische conversiefunctie (OECF) aan gespecificeerd in ISO 14524. |
| ExifVersion | `36864` | De exif-versie. |
| DateTimeOriginal | `36867` | De datum en tijd waarop de oorspronkelijke afbeeldingsgegevens zijn gegenereerd. |
| DateTimeDigitized | `36868` | De datum tijd gedigitaliseerd. |
| ComponentsConfiguration | `37121` | De componentenconfiguratie. |
| CompressedBitsPerPixel | `37122` | Specifiek voor gecomprimeerde gegevens; vermeldt de gecomprimeerde bits per pixel. |
| ShutterSpeedValue | `37377` | De sluitertijdwaarde. |
| ApertureValue | `37378` | De diafragmawaarde van de lens. |
| BrightnessValue | `37379` | De helderheidswaarde. |
| ExposureBiasValue | `37380` | De belichtingsbiaswaarde. |
| MaxApertureValue | `37381` | De maximale diafragmawaarde. |
| SubjectDistance | `37382` | De afstand tot het onderwerp, gegeven in meters. |
| MeteringMode | `37383` | De meetmodus. |
| LightSource | `37384` | De vriendelijke lichtbron. |
| Flash | `37385` | Geeft de status van de flitser aan toen de foto werd gemaakt. |
| FocalLength | `37386` | De werkelijke brandpuntsafstand van de lens, in mm. |
| SubjectArea | `37396` | Deze tag geeft de locatie en het gebied van het hoofdonderwerp in de algehele scène aan. |
| MakerNote | `37500` | Een tag voor fabrikanten van Exif-schrijvers om alle gewenste informatie vast te leggen. De inhoud is aan de fabrikant, maar deze tag mag alleen voor het beoogde doel worden gebruikt. |
| UserComment | `37510` | Een tag voor Exif-gebruikers om trefwoorden of commentaar op de afbeelding te schrijven naast die in ImageDescription, en zonder de tekencodebeperkingen van de ImageDescription-tag. |
| SubsecTime | `37520` | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTime-tag. |
| SubsecTimeOriginal | `37521` | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTimeOriginal-tag. |
| SubsecTimeDigitized | `37522` | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTimeDigitized-tag. |
| FlashpixVersion | `40960` | De versie in Flashpix-indeling die wordt ondersteund door een FPXR-bestand. |
| ColorSpace | `40961` | De kleurruimte-informatietag (ColorSpace) wordt altijd geregistreerd als de kleurruimtespecificatie. |
| RelatedSoundFile | `40964` | Het gerelateerde geluidsbestand. |
| FlashEnergy | `41483` | Geeft de stroboscoopenergie aan op het moment dat het beeld wordt vastgelegd, zoals gemeten in Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Deze tag registreert de ruimtelijke frequentietabel van de camera of het invoerapparaat en SFR-waarden in de richting van beeldbreedte, beeldhoogte en diagonale richting, zoals gespecificeerd in ISO 12233. |
| FocalPlaneXResolution | `41486` | Geeft het aantal pixels aan in de beeldbreedterichting (X) per FocalPlaneResolutionUnit op het brandvlak van de camera. |
| FocalPlaneYResolution | `41487` | Geeft het aantal pixels aan in de richting van de beeldhoogte (Y) per FocalPlaneResolutionUnit op het brandvlak van de camera. |
| FocalPlaneResolutionUnit | `41488` | Geeft de eenheid aan voor het meten van FocalPlaneXResolution en FocalPlaneYResolution. Deze waarde is gelijk aan de ResolutionUnit. |
| SubjectLocation | `41492` | Geeft de locatie van het hoofdonderwerp in de scène aan. De waarde van deze tag vertegenwoordigt de pixel in het midden van het hoofdonderwerp ten opzichte van de linkerrand, voorafgaand aan de rotatieverwerking volgens de Rotation-tag. |
| ExposureIndex | `41493` | Geeft de belichtingsindex aan die is geselecteerd op de camera of het invoerapparaat op het moment dat de foto wordt gemaakt. |
| SensingMethod | `41495` | Geeft het type beeldsensor op de camera of het invoerapparaat aan. |
| FileSource | `41728` | De bestandsbron. |
| SceneType | `41729` | Geeft het type scène aan. Als een DSC het beeld heeft opgenomen, moet deze tagwaarde altijd op 1 worden gezet, wat aangeeft dat het beeld direct is gefotografeerd. |
| CFAPattern | `41730` | Geeft het geometrische patroon van de kleurfilterarray (CFA) van de beeldsensor aan wanneer een één-chip kleurgebiedsensor wordt gebruikt. Het is niet van toepassing op alle detectiemethoden. |
| CustomRendered | `41985` | Deze tag geeft het gebruik van speciale verwerking van beeldgegevens aan, zoals renderen gericht op uitvoer. Wanneer speciale verwerking wordt uitgevoerd, wordt van de lezer verwacht dat hij verdere verwerking uitschakelt of minimaliseert. |
| ExposureMode | `41986` | Deze tag geeft de belichtingsmodus aan die was ingesteld toen de foto werd gemaakt. In de auto-bracketing-modus maakt de camera een reeks frames van dezelfde scène met verschillende belichtingsinstellingen. |
| WhiteBalance | `41987` | Deze tag geeft de witbalansmodus aan die was ingesteld toen de foto werd gemaakt. |
| DigitalZoomRatio | `41988` | Deze tag geeft de digitale zoomverhouding aan toen de foto werd gemaakt. Als de teller van de geregistreerde waarde 0 is, betekent dit dat er geen digitale zoom is gebruikt. |
| FocalLengthIn35MmFilm | `41989` | Deze tag geeft de equivalente brandpuntsafstand aan, uitgaande van een 35 mm filmcamera, in mm. Een waarde van 0 betekent dat de brandpuntsafstand onbekend is. Merk op dat deze tag verschilt van de FocalLength-tag. |
| SceneCaptureType | `41990` | Deze tag geeft het type scène aan dat is opgenomen. Het kan ook worden gebruikt om de modus vast te leggen waarin de foto is gemaakt. |
| GainControl | `41991` | Deze tag geeft de mate van algehele aanpassing van de beeldversterking aan. |
| Contrast | `41992` | Deze tag geeft de richting aan van de contrastverwerking die door de camera werd toegepast toen de foto werd gemaakt. |
| Saturation | `41993` | Deze tag geeft de richting aan van de verzadigingsverwerking die door de camera is toegepast toen de foto werd gemaakt. |
| Sharpness | `41994` | Deze tag geeft de richting aan van de scherpteverwerking toegepast door de camera toen de foto werd gemaakt |
| DeviceSettingDescription | `41995` | Deze tag geeft informatie over de opnameomstandigheden van een bepaald cameramodel. De tag wordt alleen gebruikt om de omstandigheden voor het maken van foto's in de lezer aan te geven. |
| SubjectDistanceRange | `41996` | Deze tag geeft de afstand tot het onderwerp aan. |
| ImageUniqueID | `42016` | De unieke id van de afbeelding. |
| GPSVersionID | `0` | Geeft de versie aan van GPSInfoIFD. |
| GPSLatitudeRef | `1` | Geeft aan of de breedtegraad noord- of zuiderbreedte is. |
| GPSLatitude | `2` | Geeft de breedtegraad aan. De breedtegraad wordt uitgedrukt als drie RATIONELE waarden die respectievelijk de graden, minuten en seconden geven. Als de breedtegraad wordt uitgedrukt in graden, minuten en seconden, is een typisch formaat dd/1,mm/1,ss/1. Wanneer graden en minuten worden gebruikt en bijvoorbeeld fracties van minuten worden gegeven tot twee decimalen, is het formaat dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Geeft aan of de lengtegraad oost- of westlengte is. |
| GPSLongitude | `4` | Geeft de lengtegraad aan. De lengtegraad wordt uitgedrukt als drie RATIONELE waarden die respectievelijk de graden, minuten en seconden geven. Als de lengtegraad wordt uitgedrukt in graden, minuten en seconden, is een typisch formaat ddd/1,mm/1,ss/1. Wanneer graden en minuten worden gebruikt en bijvoorbeeld fracties van minuten worden opgegeven tot twee decimalen, is het formaat ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Geeft de hoogte aan die als referentiehoogte wordt gebruikt. Als de referentie zeeniveau is en de hoogte boven zeeniveau, wordt 0 gegeven. Als de hoogte onder zeeniveau ligt, wordt de waarde 1 gegeven en wordt de hoogte aangegeven als een absolute waarde in de GPSAltitude-tag. |
| GPSAltitude | `6` | Geeft de hoogte aan op basis van de referentie in GPSAltitudeRef. Hoogte wordt uitgedrukt als één RATIONELE waarde. De referentie-eenheid is meters. |
| GPSTimestamp | `7` | Geeft de tijd aan als UTC (Coordinated Universal Time). Tijdstempel wordt uitgedrukt als drie RATIONELE waarden die het uur, de minuut en de seconde geven. |
| GPSSatellites | `8` | Geeft de GPS-satellieten aan die voor metingen worden gebruikt. Deze tag kan worden gebruikt om het aantal satellieten, hun ID-nummer, elevatiehoek, azimut, SNR en andere informatie in ASCII-notatie te beschrijven. Het formaat is not gespecificeerd. Als de GPS-ontvanger geen metingen kan uitvoeren, wordt de waarde van de tag ingesteld op NULL. |
| GPSStatus | `9` | Geeft de status van de GPS-ontvanger aan wanneer het beeld wordt opgenomen. |
| GPSMeasureMode | `10` | Geeft de GPS-meetmodus aan. - 2- of 3-dimensionaal. |
| GPSDOP | `11` | Geeft de GPS DOP (gegevensprecisiegraad) aan. Een HDOP-waarde wordt geschreven tijdens tweedimensionale meting, en PDOP tijdens driedimensionale meting. |
| GPSSpeedRef | `12` | Geeft de eenheid aan die wordt gebruikt om de bewegingssnelheid van de GPS-ontvanger uit te drukken. 'K' 'M' en 'N' staat voor kilometers per uur, mijlen per uur en knopen. |
| GPSSpeed | `13` | Geeft de snelheid van de beweging van de GPS-ontvanger aan. |
| GPSTrackRef | `14` | Geeft de referentie aan voor het aangeven van de richting van de beweging van de GPS-ontvanger. 'T' geeft ware richting aan en 'M' is magnetische richting. |
| GPSTrack | `15` | Geeft de bewegingsrichting van de GPS-ontvanger aan. Het waardenbereik loopt van 0,00 tot 359,99. |
| GPSImgDirectionRef | `16` | Geeft de referentie aan voor het aangeven van de richting van het beeld wanneer het wordt vastgelegd. 'T' geeft ware richting aan en 'M' is magnetische richting. |
| GPSImgDirection | `17` | Geeft de richting van het beeld aan toen het werd vastgelegd. Het waardenbereik loopt van 0,00 tot 359,99. |
| GPSMapDatum | `18` | Geeft de geodetische onderzoeksgegevens aan die door de GPS-ontvanger worden gebruikt. |
| GPSDestLatitudeRef | `19` | Geeft aan of de breedtegraad van het bestemmingspunt noord- of zuiderbreedte is. De ASCII-waarde 'N' geeft noord breedtegraad aan en 'S' is zuiderbreedte. |
| GPSDestLatitude | `20` | Geeft de breedtegraad van het bestemmingspunt aan. De breedtegraad wordt uitgedrukt als drie RATIONELE waarden die respectievelijk de graden, minuten en seconden opleveren. Als de breedtegraad wordt uitgedrukt in graden, minuten en seconden, is een typisch formaat dd/1,mm/1,ss/1. Als graden en minuten worden gebruikt en bijvoorbeeld fracties van minuten zijn tot op twee decimalen gegeven, is het formaat dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Geeft aan of de lengtegraad van het bestemmingspunt oost- of westlengte is. ASCII 'E' geeft oosterlengte aan, en 'W' is westerlengte. |
| GPSDestLongitude | `22` | Geeft de lengtegraad van het bestemmingspunt aan. De lengtegraad wordt uitgedrukt als drie RATIONELE waarden die respectievelijk de graden, minuten en seconden opleveren. Als de lengtegraad wordt uitgedrukt in graden, minuten en seconden, is een typisch formaat ddd/1,mm/1,ss/1. Wanneer graden en minuten worden gebruikt en bijvoorbeeld fracties van minuten zijn tot op twee decimalen gegeven, is het formaat ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Geeft de referentie aan die wordt gebruikt om de peiling naar het bestemmingspunt te geven. 'T' geeft ware richting aan en 'M' is magnetische richting. |
| GPSDestBearing | `24` | Geeft de peiling naar het bestemmingspunt aan. Het waardenbereik loopt van 0,00 tot 359,99. |
| GPSDestDistanceRef | `25` | Geeft de eenheid aan die wordt gebruikt om de afstand tot het bestemmingspunt uit te drukken. 'K', 'M' en 'N' staan voor kilometers, mijlen en knopen. |
| GPSDestDistance | `26` | Geeft de afstand tot het bestemmingspunt aan. |
| GPSProcessingMethod | `27` | Een tekenreeks die de naam vastlegt van de methode die wordt gebruikt voor het vinden van een locatie. De eerste byte geeft de gebruikte tekencode aan, gevolgd door de naam van de methode. |
| GPSAreaInformation | `28` | Een tekenreeks die de naam van het GPS-gebied vastlegt. De eerste byte geeft de gebruikte tekencode aan, gevolgd door de naam van het GPS-gebied. |
| GPSDateStamp | `29` | Een tekenreeks die datum- en tijdinformatie vastlegt ten opzichte van UTC (Coordinated Universal Time). Het formaat is JJJJ:MM:DD. |
| GPSDifferential | `30` | Geeft aan of differentiële correctie wordt toegepast op de GPS-ontvanger. |
| StripOffsets | `273` | Voor elke strip, de byte-offset van die strip. Het wordt aanbevolen om dit zo te selecteren dat het aantal stripbytes niet groter is dan 64 Kbytes. Aux-tag. |
| JPEGInterchangeFormat | `513` | De offset ten opzichte van de startbyte (SOI) van JPEG-gecomprimeerde miniatuurgegevens. Dit wordt niet gebruikt voor JPEG-gegevens van primaire afbeeldingen. |
| JPEGInterchangeFormatLength | `514` | Het aantal bytes aan JPEG-gecomprimeerde miniatuurgegevens. Dit wordt niet gebruikt voor JPEG-gegevens van primaire afbeeldingen. JPEG-thumbnails zijn niet verdeeld, maar worden opgenomen als een continue JPEG-bitstream van SOI naar EOI. Appn- en COM-markeringen mogen niet worden opgenomen. Gecomprimeerde miniaturen moeten worden opgenomen in niet meer dan 64 Kbytes, inclusief alle andere gegevens die moeten worden opgenomen in APP1. |
| ExifIfdPointer | `34665` | Een verwijzing naar de Exif IFD. Interoperabiliteit, Exif IFD heeft dezelfde structuur als die van de IFD gespecificeerd in TIFF. normaal gesproken bevat het echter geen afbeeldingsgegevens zoals in het geval van TIFF. |
| GPSIfdPointer | `34853` | De gps-ifd-aanwijzer. |
| RowsPerStrip | `278` | Het aantal rijen per strip. Dit is het aantal rijen in de afbeelding van één strook wanneer een afbeelding in stroken is verdeeld. |
| StripByteCounts | `279` | Het totale aantal bytes in elke strip. |
| PixelXDimension | `40962` | Informatie specifiek voor gecomprimeerde gegevens. Wanneer een gecomprimeerd bestand wordt opgenomen, wordt de geldige breedte van de betekenisvolle afbeelding in deze tag vastgelegd, ongeacht of er opvulgegevens of een herstartmarkering zijn. |
| PixelYDimension | `40963` | Informatie specifiek voor gecomprimeerde gegevens. Wanneer een gecomprimeerd bestand wordt opgenomen, wordt de geldige hoogte van de betekenisvolle afbeelding vastgelegd in deze tag |
| Gamma | `42240` | Gammawaarde |
| SensitivityType | `34864` | Soort fotografische gevoeligheid |
| StandardOutputSensitivity | `34865` | Geeft standaard uitvoergevoeligheid van camera aan |
| RecommendedExposureIndex | `34866` | Geeft de aanbevolen blootstellingsindex aan |
| ISOSpeed | `34867` | Informatie over ISO-snelheidswaarde zoals gedefinieerd in ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Deze tag geeft de ISO-snelheid latitude yyy-waarde aan zoals gedefinieerd in ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Deze tag geeft de ISO-snelheid breedtegraad zzz-waarde aan zoals gedefinieerd in ISO 12232 |
| CameraOwnerName | `42032` | Bevat naam camera-eigenaar |
| BodySerialNumber | `42033` | Bevat serienummer camerabehuizing |
| LensMake | `42035` | Deze tag registreert lensfabrikant |
| LensModel | `42036` | Deze tag registreert de modelnaam en het modelnummer van de lens |
| LensSerialNumber | `42037` | Deze tag registreert het serienummer van verwisselbare lens |
| LensSpecification | `42034` | Deze tag vermeldt minimale brandpuntsafstand, maximale brandpuntsafstand, minimum F-getal in de minimale brandpuntsafstand en minimum F-getal in maximale brandpuntsafstand |

### Zie ook

* naamruimte [Aspose.PSD.Exif](../../aspose.psd.exif/)
* montage [Aspose.PSD](../../)


