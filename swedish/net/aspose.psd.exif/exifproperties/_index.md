---
title: "Enum ExifProperties"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Exif.ExifProperties-enum. Lista över Exif-taggar"
type: docs
weight: 1010
url: /sv/net/aspose.psd.exif/exifproperties/
---
{{< psd/tize >}}
## ExifProperties enumeration

Lista över Exif-taggar.

```csharp
public enum ExifProperties : ushort
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| ImageWidth | `256` | Antalet kolumner i bilddata, lika med antalet pixlar per rad. |
| ImageLength | `257` | Antalet rader i bilddata. |
| BitsPerSample | `258` | Antalet bitar per bildkomponent. I denna standard är varje komponent i bilden 8 bitar, så värdet för denna tagg är 8. |
| Compression | `259` | Komprimeringsschemat som används för bilddata. När en huvudbild är JPEG-komprimerad är denna beteckning inte nödvändig och utelämnas. |
| PhotometricInterpretation | `262` | Pixelkompositionen. |
| ImageDescription | `270` | En teckensträng som ger bildens titel. Det kan vara en kommentar som "1988 företagsutflykt" eller liknande. |
| Make | `271` | Tillverkaren av inspelningsutrustningen. Detta är tillverkaren av DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt. |
| Model | `272` | Modellnamnet eller modellnumret på utrustningen. Detta är modellnamnet eller -numret på DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt. |
| Orientation | `274` | Bildens orientering betraktad i termer av rader och kolumner. |
| SamplesPerPixel | `277` | Antalet komponenter per pixel. Eftersom denna standard gäller för RGB- och YCbCr-bilder är värdet för denna tagg 3. |
| XResolution | `282` | Antalet pixlar per ResolutionUnit i ImageWidth‑riktningen. När bildens upplösning är okänd, anges 72 [dpi]. |
| YResolution | `283` | Antalet pixlar per ResolutionUnit i ImageLength‑riktningen. Samma värde som XResolution anges. |
| PlanarConfiguration | `284` | Anger om pixelkomponenter lagras i chunky‑ eller planarformat. Om detta fält inte finns antas TIFF‑standardvärdet 1 (chunky). |
| ResolutionUnit | `296` | Enheten för att mäta XResolution och YResolution. Samma enhet används för både XResolution och YResolution. Om bildens upplösning är okänd, anges 2 (tum). |
| TransferFunction | `301` | En överföringsfunktion för bilden, beskriven i tabellformat. Vanligtvis behövs denna tagg inte, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace‑taggen. |
| Software | `305` | Denna tagg registrerar namn och version på programvaran eller firmware för kameran eller bildinmatningsenheten som användes för att skapa bilden. Det detaljerade formatet är inte specificerat, men det rekommenderas att följa exemplet nedan. När fältet lämnas tomt behandlas det som okänt. |
| DateTime | `306` | Datum och tid för bildens skapande. I Exif‑standarden är det datum och tid då filen ändrades. |
| Artist | `315` | Denna tagg registrerar namn på kamerans ägare, fotograf eller bildskapare. Det detaljerade formatet är inte specificerat, men det rekommenderas att informationen skrivas enligt exemplet nedan för att underlätta interoperabilitet. När fältet lämnas tomt behandlas det som okänt. Ex.) \"Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James\" |
| WhitePoint | `318` | Kromaticiteten för bildens vitpunkt. Vanligtvis behövs denna tagg inte, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace‑taggen. |
| PrimaryChromaticities | `319` | Kromaticiteten för bildens tre primära färger. Vanligtvis behövs denna tagg inte, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace‑taggen. |
| YCbCrCoefficients | `529` | Matriskoefficienterna för omvandling från RGB till YCbCr‑bilddata. |
| YCbCrSubSampling | `530` | Samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten. |
| YCbCrPositioning | `531` | Krominanskomponenternas position i förhållande till luminanskomponenten. Detta fält är endast avsett för JPEG‑komprimerad data eller okomprimerad YCbCr‑data. TIFF‑standardvärdet är 1 (centrerad); men när Y:Cb:Cr = 4:2:2 rekommenderas i denna standard att 2 (sido‑placerad) används för att lagra data, för att förbättra bildkvaliteten vid visning på TV‑system. När detta fält inte finns ska läsaren anta TIFF‑standardvärdet. I fallet Y:Cb:Cr = 4:2:0 rekommenderas TIFF‑standardvärdet (centrerad). Om läsaren inte har möjlighet att stödja båda typerna av YCbCrPositioning ska den följa TIFF‑standardvärdet oavsett värdet i detta fält. Det är önskvärt att läsare \" ska kunna stödja både centrerad och sido‑placerad positionering. |
| ReferenceBlackWhite | `532` | Referensvärdet för svartpunkt och referensvärdet för vitpunkt. Inga standardvärden anges i TIFF, men värdena nedan ges som standard här. Färgrymden deklareras i en färgrymdsinformations‑tagg, där standardvärdet är det som ger optimala bildegenskaper för interoperabilitet under dessa förhållanden. |
| Copyright | `33432` | Upphovsrättsinformation. I denna standard används taggen för att ange både fotografens och redaktörens upphovsrätt. Det är upphovsrättsmeddelandet från personen eller organisationen som gör anspråk på bilden. Interoperabilitetens upphovsrättsdeklaration inklusive datum och rättigheter ska skrivas i detta fält; t.ex., "Copyright, John Smith, 19xx. All rights reserved.". I denna standard registrerar fältet både fotografens och redaktörens upphovsrätt, där varje registreras i en separat del av deklarationen. När det finns en tydlig skillnad mellan fotografens och redaktörens upphovsrätt ska de skrivas i ordning fotograf följt av redaktörs upphovsrätt, separerade med NULL (i detta fall, eftersom deklarationen också avslutas med en NULL, finns två NULL‑koder). När endast fotografens upphovsrätt anges avslutas den med en NULL‑kod. När endast redaktörens upphovsrätt anges består fotografens upphovsrättsdel av ett mellanslag följt av en avslutande NULL‑kod, sedan anges redaktörens upphovsrätt. När fältet lämnas tomt behandlas det som okänt. |
| ExposureTime | `33434` | Exponeringstid, given i sekunder. |
| FNumber | `33437` | F‑numret. |
| ExposureProgram | `34850` | Klassen för programmet som kameran använder för att ställa in exponeringen när bilden tas. |
| SpectralSensitivity | `34852` | Anger den spektrala känsligheten för varje kanal i den använda kameran. |
| PhotographicSensitivity | `34855` | Anger ISO‑hastigheten och ISO‑latituden för kameran eller inmatningsenheten enligt ISO 12232. |
| OECF | `34856` | Anger den opto‑elektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524. |
| ExifVersion | `36864` | Exif‑versionen. |
| DateTimeOriginal | `36867` | Datumet och tiden då den ursprungliga bilddata genererades. |
| DateTimeDigitized | `36868` | Datum och tid för digitalisering. |
| ComponentsConfiguration | `37121` | Komponentkonfigurationen. |
| CompressedBitsPerPixel | `37122` | Specifikt för komprimerad data; anger de komprimerade bitarna per pixel. |
| ShutterSpeedValue | `37377` | Värdet för slutartiden. |
| ApertureValue | `37378` | Värdet för objektivets bländare. |
| BrightnessValue | `37379` | Ljusstyrkevärdet. |
| ExposureBiasValue | `37380` | Värdet för exponeringskompensation. |
| MaxApertureValue | `37381` | Värdet för maximal bländare. |
| SubjectDistance | `37382` | Avståndet till motivet, angivet i meter. |
| MeteringMode | `37383` | Mätningsläget. |
| LightSource | `37384` | Typ av ljuskälla. |
| Flash | `37385` | Anger blixtens status när bilden togs. |
| FocalLength | `37386` | Den faktiska brännvidden för objektivet, i mm. |
| SubjectArea | `37396` | Denna tagg anger placeringen och området för huvudmotivet i hela scenen. |
| MakerNote | `37500` | En tagg för tillverkare av Exif‑skrivare att lagra önskad information. Innehållet bestäms av tillverkaren, men denna tagg bör inte användas för annat än dess avsedda syfte. |
| UserComment | `37510` | En tagg för Exif‑användare att skriva nyckelord eller kommentarer på bilden utöver de i ImageDescription, och utan teckenkodningsbegränsningarna i ImageDescription‑taggen. |
| SubsecTime | `37520` | En tagg som används för att registrera bråkdelar av sekunder för DateTime‑taggen. |
| SubsecTimeOriginal | `37521` | En tagg som används för att registrera bråkdelar av sekunder för DateTimeOriginal‑taggen. |
| SubsecTimeDigitized | `37522` | En tagg som används för att registrera bråkdelar av sekunder för DateTimeDigitized‑taggen. |
| FlashpixVersion | `40960` | Flashpix-formatversionen som stöds av en FPXR‑fil. |
| ColorSpace | `40961` | Färgrymdsinformations‑taggen (ColorSpace) registreras alltid som färgrymdsspecificeraren. |
| RelatedSoundFile | `40964` | Den relaterade ljudfilen. |
| FlashEnergy | `41483` | Anger strobenergin vid den tidpunkt bilden fångas, mätt i Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Denna tagg registrerar kamerans eller inmatningsenhetens spatialfrekvenstabell och SFR‑värden i bildens bredd-, höjd‑ och diagonalriktning, enligt ISO 12233. |
| FocalPlaneXResolution | `41486` | Anger antalet pixlar i bildens bredd (X) per FocalPlaneResolutionUnit på kamerans fokalplan. |
| FocalPlaneYResolution | `41487` | Anger antalet pixlar i bildens höjd (Y) per FocalPlaneResolutionUnit på kamerans fokalplan. |
| FocalPlaneResolutionUnit | `41488` | Anger enheten för mätning av FocalPlaneXResolution och FocalPlaneYResolution. Detta värde är detsamma som ResolutionUnit. |
| SubjectLocation | `41492` | Anger huvudobjektets position i scenen. Värdet för denna tagg representerar pixeln i centrum av huvudobjektet i förhållande till vänster kant, före roteringsbearbetning enligt Rotation‑taggen. |
| ExposureIndex | `41493` | Anger exponeringsindexet som valdes på kameran eller inmatningsenheten när bilden fångas. |
| SensingMethod | `41495` | Anger bildsensortypen på kameran eller inmatningsenheten. |
| FileSource | `41728` | Filkällan. |
| SceneType | `41729` | Anger scenens typ. Om en DSC spelade in bilden ska detta taggvärde alltid vara 1, vilket indikerar att bilden fotograferades direkt. |
| CFAPattern | `41730` | Anger färgfilterarrayens (CFA) geometriska mönster för bildsensorn när en enkelskikts färgområdessensor används. Det gäller inte alla avkänningsmetoder. |
| CustomRendered | `41985` | Denna tagg indikerar användning av specialbehandling av bilddata, såsom rendering anpassad för utdata. När specialbehandling utförs förväntas läsaren inaktivera eller minimera ytterligare bearbetning. |
| ExposureMode | `41986` | Denna tagg indikerar exponeringsläget som sattes när bilden togs. I auto‑bracketing‑läge tar kameran en serie bilder av samma scen med olika exponeringsinställningar. |
| WhiteBalance | `41987` | Denna tagg indikerar vitbalansläget som sattes när bilden togs. |
| DigitalZoomRatio | `41988` | Denna tagg indikerar den digitala zoomfaktorn när bilden togs. Om täljaren för det registrerade värdet är 0 betyder det att digital zoom inte användes. |
| FocalLengthIn35MmFilm | `41989` | Denna tagg indikerar den ekvivalenta brännvidden för en 35 mm filmkamera, i mm. Ett värde på 0 betyder att brännvidden är okänd. Observera att denna tagg skiljer sig från FocalLength‑taggen. |
| SceneCaptureType | `41990` | Denna tagg indikerar vilken typ av scen som fotograferades. Den kan också användas för att registrera vilket läge bilden togs i. |
| GainControl | `41991` | Denna tagg indikerar graden av total bildförstärkningsjustering. |
| Contrast | `41992` | Denna tagg indikerar riktningen för kontrastbehandling som kameran applicerade när bilden togs. |
| Saturation | `41993` | Denna tagg anger riktningen för mättnadsbehandling som kameran tillämpade när bilden togs. |
| Sharpness | `41994` | Denna tagg anger riktningen för skärpebehandling som kameran tillämpade när bilden togs. |
| DeviceSettingDescription | `41995` | Denna tagg anger information om fotograferingsförhållandena för en viss kameramodell. Taggen används endast för att ange fotograferingsförhållandena i läsaren. |
| SubjectDistanceRange | `41996` | Denna tagg anger avståndet till motivet. |
| ImageUniqueID | `42016` | Bildens unika ID. |
| GPSVersionID | `0` | Anger versionen av GPSInfoIFD. |
| GPSLatitudeRef | `1` | Anger om latituden är nordlig eller sydlig latitud. |
| GPSLatitude | `2` | Anger latituden. Latituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder, i den ordningen. Om latituden uttrycks i grader, minuter och sekunder är ett typiskt format dd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med två decimaler, är formatet dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Anger om longituden är östlig eller västlig longitud. |
| GPSLongitude | `4` | Anger longituden. Longituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder, i den ordningen. Om longituden uttrycks i grader, minuter och sekunder är ett typiskt format ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med två decimaler, är formatet ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Anger den höjd som används som referenshöjd. Om referensen är havsnivå och höjden är över havsnivå anges 0. Om höjden är under havsnivå anges värdet 1 och höjden anges som ett absolut värde i GPSAltitude‑taggen. |
| GPSAltitude | `6` | Anger höjden baserat på referensen i GPSAltitudeRef. Höjden uttrycks som ett RATIONAL‑värde. Referensenheten är meter. |
| GPSTimestamp | `7` | Anger tiden som UTC (Coordinated Universal Time). TimeStamp uttrycks som tre RATIONAL‑värden som ger timme, minut och sekund. |
| GPSSatellites | `8` | Anger de GPS‑satelliter som används för mätningar. Denna tagg kan användas för att beskriva antalet satelliter, deras ID‑nummer, höjdvinkel, azimut, SNR och annan information i ASCII‑notation. Formatet är inte specificerat. Om GPS‑mottagaren inte kan utföra mätningar ska taggens värde sättas till NULL. |
| GPSStatus | `9` | Anger GPS‑mottagarens status när bilden registreras. |
| GPSMeasureMode | `10` | Anger GPS‑mätningsläget. - 2‑ eller 3‑dimensionellt. |
| GPSDOP | `11` | Anger GPS‑DOP (data degree of precision). Ett HDOP‑värde skrivs under tvådimensionell mätning och PDOP under tredimensionell mätning. |
| GPSSpeedRef | `12` | Anger enheten som används för att uttrycka GPS‑mottagarens rörelsehastighet. 'K', 'M' och 'N' representerar kilometer per timme, miles per timme och knop. |
| GPSSpeed | `13` | Anger GPS‑mottagarens rörelsehastighet. |
| GPSTrackRef | `14` | Anger referensen för att ange GPS‑mottagarens rörelses riktning. 'T' betyder sann riktning och 'M' är magnetisk riktning. |
| GPSTrack | `15` | Anger GPS‑mottagarens rörelseriktning. Värdeintervallet är från 0.00 till 359.99. |
| GPSImgDirectionRef | `16` | Anger referensen för att ange bildens riktning när den tas. 'T' betyder sann riktning och 'M' är magnetisk riktning. |
| GPSImgDirection | `17` | Anger bildens riktning när den togs. Värdeintervallet är från 0.00 till 359.99. |
| GPSMapDatum | `18` | Anger de geodetiska kartläggningsdata som används av GPS-mottagaren. |
| GPSDestLatitudeRef | `19` | Anger om latituden för destinationspunkten är nordlig eller sydlig latitud. ASCII‑värdet 'N' indikerar nordlig latitud, och 'S' är sydlig latitud. |
| GPSDestLatitude | `20` | Anger latituden för destinationspunkten. Latituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder, i den ordningen. Om latituden uttrycks i grader, minuter och sekunder är ett typiskt format dd/1,mm/1,ss/1. När grader och minuter används och exempelvis minuter anges med bråk upp till två decimaler, blir formatet dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Anger om longituden för destinationspunkten är östlig eller västlig longitud. ASCII 'E' indikerar östlig longitud, och 'W' är västlig longitud. |
| GPSDestLongitude | `22` | Anger longituden för destinationspunkten. Longituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder, i den ordningen. Om longituden uttrycks i grader, minuter och sekunder är ett typiskt format ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis minuter anges med bråk upp till två decimaler, blir formatet ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Anger referensen som används för att ange kursen till destinationspunkten. 'T' betyder sann riktning och 'M' är magnetisk riktning. |
| GPSDestBearing | `24` | Anger kursen till destinationspunkten. Värdeintervallet är från 0.00 till 359.99. |
| GPSDestDistanceRef | `25` | Anger enheten som används för att uttrycka avståndet till destinationspunkten. 'K', 'M' och 'N' representerar kilometer, miles och knop. |
| GPSDestDistance | `26` | Anger avståndet till destinationspunkten. |
| GPSProcessingMethod | `27` | En teckensträng som registrerar namnet på metoden som används för positionsbestämning. Den första byten indikerar den teckenkod som används, och detta följs av metodens namn. |
| GPSAreaInformation | `28` | En teckensträng som registrerar namnet på GPS‑området. Den första byten indikerar den teckenkod som används, och detta följs av GPS‑områdets namn. |
| GPSDateStamp | `29` | En teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). Formatet är ÅÅÅÅ:MM:DD. |
| GPSDifferential | `30` | Anger om differentialkorrektion tillämpas på GPS‑mottagaren. |
| StripOffsets | `273` | För varje strip, byte‑offseten för den stripen. Det rekommenderas att detta väljs så att antalet strip‑byte inte överstiger 64 Kbyte. Aux‑tagg. |
| JPEGInterchangeFormat | `513` | Offseten till start‑byten (SOI) för JPEG‑komprimerad miniatyrbildsdata. Detta används inte för primär bild‑JPEG‑data. |
| JPEGInterchangeFormatLength | `514` | Antalet byte för JPEG‑komprimerad miniatyrbildsdata. Detta används inte för primär bild‑JPEG‑data. JPEG‑miniatyrer delas inte utan registreras som en kontinuerlig JPEG‑bitström från SOI till EOI. Appn‑ och COM‑markörer bör inte registreras. Komprimerade miniatyrer måste registreras på högst 64 Kbyte, inklusive all annan data som ska registreras i APP1. |
| ExifIfdPointer | `34665` | En pekare till Exif‑IFD. Interoperabilitet, Exif‑IFD har samma struktur som den IFD som specificeras i TIFF. Vanligtvis innehåller den dock inte bilddata som i fallet med TIFF. |
| GPSIfdPointer | `34853` | GPS‑IFD‑pekaren. |
| RowsPerStrip | `278` | Antalet rader per strip. Detta är antalet rader i bilden för en strip när en bild delas upp i strips. |
| StripByteCounts | `279` | Det totala antalet byte i varje strip. |
| PixelXDimension | `40962` | Information som är specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga bredden på den meningsfulla bilden registreras i den här taggen, oavsett om det finns utfyllnadsdata eller en omstartmarkör. |
| PixelYDimension | `40963` | Information som är specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga höjden på den meningsfulla bilden registreras i den här taggen. |
| Gamma | `42240` | Gamma-värde |
| SensitivityType | `34864` | Typ av fotografisk känslighet |
| StandardOutputSensitivity | `34865` | Anger kamerans standardutgångskänslighet |
| RecommendedExposureIndex | `34866` | Anger rekommenderat exponeringsindex |
| ISOSpeed | `34867` | Information om iso-hastighetsvärde enligt ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Denna tagg anger ISO-hastighetslatitud yyy-värde enligt ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Denna tagg anger ISO-hastighetslatitud zzz-värde enligt ISO 12232 |
| CameraOwnerName | `42032` | Innehåller kamerans ägarnamn |
| BodySerialNumber | `42033` | Innehåller kamerakroppens serienummer |
| LensMake | `42035` | Denna tagg registrerar linsens tillverkare |
| LensModel | `42036` | Denna tagg registrerar linsens modellnamn och modellnummer |
| LensSerialNumber | `42037` | Denna tagg registrerar serienumret för utbytbar lins |
| LensSpecification | `42034` | Denna tagg noterar minsta brännvidd, största brännvidd, minsta F-nummer vid minsta brännvidd och minsta F-nummer vid största brännvidd |

### Se även

* namespace [Aspose.PSD.Exif](../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../)


