---
title: "ExifProperties"
second_title: "Aspose.PSD för Java API-referens"
description: "Lista över Exif-taggar"
type: docs
weight: 11
url: /sv/java/com.aspose.psd.exif/exifproperties/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Lista över Exif-taggar
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ApertureValue](#ApertureValue) | Linsens bländarvärde. |
| [Artist](#Artist) | Denna tagg registrerar namnet på kamerans ägare, fotograf eller bildskapare. |
| [BitsPerSample](#BitsPerSample) | Antalet bitar per bildkomponent. |
| [BodySerialNumber](#BodySerialNumber) | Innehåller kamerahusets serienummer |
| [BrightnessValue](#BrightnessValue) | Ljusstyrkevärdet. |
| [CFAPattern](#CFAPattern) | Anger färgfilterarrayens (CFA) geometriska mönster för bildsensorn när en enkelskikts färgområdessensor används. |
| [CameraOwnerName](#CameraOwnerName) | Innehåller kamerans ägarnamn |
| [ColorSpace](#ColorSpace) | Färgrymdsinformations-taggen (ColorSpace) registreras alltid som färgrymdsspecifikator. |
| [ComponentsConfiguration](#ComponentsConfiguration) | Komponenternas konfiguration. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Specifikt för komprimerad data; anger de komprimerade bitarna per pixel. |
| [Compression](#Compression) | Komprimeringsschemat som används för bilddata. |
| [Contrast](#Contrast) | Denna tagg anger riktningen för kontrastbehandling som kameran tillämpade när bilden togs. |
| [Copyright](#Copyright) | Upphovsrättsinformation. |
| [CustomRendered](#CustomRendered) | Denna tagg anger användning av speciell bearbetning av bilddata, såsom rendering anpassad för utdata. |
| [DateTime](#DateTime) | Datum och tid för bildskapande. |
| [DateTimeDigitized](#DateTimeDigitized) | Datum och tid för digitalisering. |
| [DateTimeOriginal](#DateTimeOriginal) | Datumet och tiden då de ursprungliga bilddata genererades. |
| [DeviceSettingDescription](#DeviceSettingDescription) | Denna tagg indikerar information om bildtagningsförhållandena för en viss kameramodell. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Denna tagg indikerar den digitala zoomförhållandet när bilden togs. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExifIfdPointer](#ExifIfdPointer) | En pekare till Exif IFD. |
| [ExifVersion](#ExifVersion) | Exif-versionen. |
| [ExposureBiasValue](#ExposureBiasValue) | Exponeringsbiasvärdet. |
| [ExposureIndex](#ExposureIndex) | Indikerar exponeringsindexet som valdes på kameran eller inmatningsenheten när bilden fångas. |
| [ExposureMode](#ExposureMode) | Denna tagg indikerar exponeringsläget som sattes när bilden togs. |
| [ExposureProgram](#ExposureProgram) | Klassen för programmet som kameran använder för att ställa in exponeringen när bilden tas. |
| [ExposureTime](#ExposureTime) | Exponeringstid, angiven i sekunder. |
| [FNumber](#FNumber) | F-talet. |
| [FileSource](#FileSource) | Filkällan. |
| [Flash](#Flash) | Indikerar blixtens status när bilden togs. |
| [FlashEnergy](#FlashEnergy) | Indikerar strobenenergin vid tidpunkten då bilden fångas, mätt i Beam Candle Power Seconds (BCPS). |
| [FlashpixVersion](#FlashpixVersion) | Flashpix-formatversionen som stöds av en FPXR-fil. |
| [FocalLength](#FocalLength) | Den faktiska brännvidden på linsen, i mm. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Denna tagg indikerar den ekvivalenta brännvidden under antagandet av en 35 mm filmkamera, i mm. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indikerar enheten för att mäta FocalPlaneXResolution och FocalPlaneYResolution. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indikerar antalet pixlar i bildens bredd (X)-riktning per FocalPlaneResolutionUnit på kamerans fokalplan. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indikerar antalet pixlar i bildens höjd (Y)-riktning per FocalPlaneResolutionUnit på kamerans fokalplan. |
| [GPSAltitude](#GPSAltitude) | Indikerar höjden baserat på referensen i GPSAltitudeRef. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Indikerar höjden som används som referenshöjd. |
| [GPSAreaInformation](#GPSAreaInformation) | En teckensträng som registrerar namnet på GPS-området. |
| [GPSDOP](#GPSDOP) | Indikerar GPS DOP (dataprecisionsgrad). |
| [GPSDateStamp](#GPSDateStamp) | En teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). |
| [GPSDestBearing](#GPSDestBearing) | Indikerar bäringen till destinationspunkten. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Indikerar referensen som används för att ange bäringen till destinationspunkten. |
| [GPSDestDistance](#GPSDestDistance) | Indikerar avståndet till destinationspunkten. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Indikerar enheten som används för att uttrycka avståndet till destinationspunkten. |
| [GPSDestLatitude](#GPSDestLatitude) | Indikerar latituden för destinationspunkten. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Indikerar om latituden för destinationspunkten är nordlig eller sydlig latitud. |
| [GPSDestLongitude](#GPSDestLongitude) | Indikerar longituden för destinationspunkten. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Indikerar om longituden för destinationspunkten är östlig eller västlig longitud. |
| [GPSDifferential](#GPSDifferential) | Indikerar om differentialkorrektion tillämpas på GPS-mottagaren. |
| [GPSIfdPointer](#GPSIfdPointer) | gps IFD‑pekaren. |
| [GPSImgDirection](#GPSImgDirection) | Indikerar bildens riktning när den togs. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Indikerar referensen för att ange bildens riktning när den tas. |
| [GPSLatitude](#GPSLatitude) | Indikerar latituden. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Indikerar om latituden är nordlig eller sydlig. |
| [GPSLongitude](#GPSLongitude) | Indikerar longituden. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Indikerar om longituden är östlig eller västlig. |
| [GPSMapDatum](#GPSMapDatum) | Indikerar de geodetiska kartdata som används av GPS-mottagaren. |
| [GPSMeasureMode](#GPSMeasureMode) | Indikerar GPS‑mätningsläget. |
| [GPSProcessingMethod](#GPSProcessingMethod) | En teckensträng som registrerar namnet på den metod som används för positionsbestämning. |
| [GPSSatellites](#GPSSatellites) | Indikerar de GPS‑satelliter som används för mätningar. |
| [GPSSpeed](#GPSSpeed) | Indikerar hastigheten för GPS‑mottagarens rörelse. |
| [GPSSpeedRef](#GPSSpeedRef) | Indikerar enheten som används för att uttrycka GPS‑mottagarens rörelsehastighet. |
| [GPSStatus](#GPSStatus) | Indikerar GPS‑mottagarens status när bilden spelas in. |
| [GPSTimestamp](#GPSTimestamp) | Indikerar tiden som UTC (Coordinated Universal Time). |
| [GPSTrack](#GPSTrack) | Indikerar GPS‑mottagarens rörelseriktning. |
| [GPSTrackRef](#GPSTrackRef) | Anger referensen för att ange riktningen för GPS-mottagarens rörelse. |
| [GPSVersionID](#GPSVersionID) | Anger versionen av GPSInfoIFD. |
| [GainControl](#GainControl) | Denna tagg anger graden av total bildförstärkningsjustering. |
| [Gamma](#Gamma) | Gammavärde |
| [ISOSpeed](#ISOSpeed) | Information om ISO-hastighetsvärde enligt ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Denna tagg anger ISO-hastighetslatitud yyy-värde enligt ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Denna tagg anger ISO-hastighetslatitud zzz-värde enligt ISO 12232 |
| [ImageDescription](#ImageDescription) | En teckensträng som ger bildens titel. |
| [ImageLength](#ImageLength) | Antalet rader av bilddata. |
| [ImageUniqueID](#ImageUniqueID) | Bildens unika ID. |
| [ImageWidth](#ImageWidth) | Antalet kolumner av bilddata, lika med antalet pixlar per rad. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | Förskjutningen till startbyten (SOI) för JPEG-komprimerad miniatyrbildsdata. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | Antalet byte av JPEG-komprimerad miniatyrbildsdata. |
| [LensMake](#LensMake) | Denna tagg registrerar objektivtillverkare |
| [LensModel](#LensModel) | Denna tagg registrerar objektivets modellnamn och modellnummer |
| [LensSerialNumber](#LensSerialNumber) | Denna tagg registrerar serienumret för utbytbart objektiv |
| [LensSpecification](#LensSpecification) | Denna tagg noterar minsta brännvidd, största brännvidd, lägsta bländartal vid minsta brännvidd och lägsta bländartal vid största brännvidd |
| [LightSource](#LightSource) | Typ av ljuskälla. |
| [Make](#Make) | Tillverkaren av inspelningsutrustningen. |
| [MakerNote](#MakerNote) | En tagg för tillverkare av Exif-skrivare att registrera önskad information. |
| [MaxApertureValue](#MaxApertureValue) | Det maximala bländartalet. |
| [MeteringMode](#MeteringMode) | Mätningsläget. |
| [Model](#Model) | Modellnamnet eller modellnumret på utrustningen. |
| [OECF](#OECF) | Anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524. |
| [Orientation](#Orientation) | Bildens orientering betraktad i termer av rader och kolumner. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Anger ISO‑hastigheten och ISO‑latituden för kameran eller inmatningsenheten enligt ISO 12232. |
| [PhotometricInterpretation](#PhotometricInterpretation) | Pixelkompositionen. |
| [PixelXDimension](#PixelXDimension) | Information specifik för komprimerad data. |
| [PixelYDimension](#PixelYDimension) | Information specifik för komprimerad data. |
| [PlanarConfiguration](#PlanarConfiguration) | Anger om pixelkomponenter lagras i ett chunky‑ eller planarformat. |
| [PrimaryChromaticities](#PrimaryChromaticities) | Kromaticiteten för bildens tre primära färger. |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Anger rekommenderat exponeringsindex |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Referensvärdet för svartpunkt och referensvärdet för vitpunkt. |
| [RelatedSoundFile](#RelatedSoundFile) | Den relaterade ljudfilen. |
| [ResolutionUnit](#ResolutionUnit) | Enheten för att mäta XResolution och YResolution. |
| [RowsPerStrip](#RowsPerStrip) | Antalet rader per strip. |
| [SamplesPerPixel](#SamplesPerPixel) | Antalet komponenter per pixel. |
| [Saturation](#Saturation) | Denna tagg anger riktningen för mättnadsbehandling som kameran tillämpade när bilden togs. |
| [SceneCaptureType](#SceneCaptureType) | Denna tagg anger vilken typ av scen som fotograferades. |
| [SceneType](#SceneType) | Anger scenens typ. |
| [SensingMethod](#SensingMethod) | Anger bildsensortypen på kameran eller inmatningsenheten. |
| [SensitivityType](#SensitivityType) | Typ av fotografisk känslighet |
| [Sharpness](#Sharpness) | Denna tagg anger riktningen för skärpebehandling som kameran tillämpade när bilden togs |
| [ShutterSpeedValue](#ShutterSpeedValue) | Värdet för slutartiden. |
| [Software](#Software) | Denna tagg registrerar namn och version av mjukvaran eller firmware för kameran eller bildinmatningsenheten som användes för att skapa bilden. |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Denna tagg registrerar kamerans eller inmatningsenhetens rumsliga frekvenstabell och SFR‑värden i bildens bredd‑, höjd‑ och diagonalriktning, enligt ISO 12233. |
| [SpectralSensitivity](#SpectralSensitivity) | Anger den spektrala känsligheten för varje kanal i den använda kameran. |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Anger standardutgångskänsligheten för kameran |
| [StripByteCounts](#StripByteCounts) | Det totala antalet byte i varje strip. |
| [StripOffsets](#StripOffsets) | För varje strip, byteoffset för den strippen. |
| [SubjectArea](#SubjectArea) | Denna tagg anger platsen och området för huvudmotivet i den övergripande scenen. |
| [SubjectDistance](#SubjectDistance) | Avståndet till motivet, angivet i meter. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Denna tagg anger avståndet till motivet. |
| [SubjectLocation](#SubjectLocation) | Anger platsen för huvudmotivet i scenen. |
| [SubsecTime](#SubsecTime) | En tagg som används för att registrera bråkdelar av sekunder för taggen DateTime. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | En tagg som används för att registrera bråkdelar av sekunder för taggen DateTimeDigitized. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | En tagg som används för att registrera bråkdelar av sekunder för taggen DateTimeOriginal. |
| [TransferFunction](#TransferFunction) | En överföringsfunktion för bilden, beskriven i tabellformat. |
| [UserComment](#UserComment) | En tagg för Exif-användare att skriva nyckelord eller kommentarer på bilden förutom de i ImageDescription, och utan teckenkodningsbegränsningarna för taggen ImageDescription. |
| [WhiteBalance](#WhiteBalance) | Denna tagg anger vitbalansläget som sattes när bilden togs. |
| [WhitePoint](#WhitePoint) | Kromaticiteten för bildens vitpunkt. |
| [XResolution](#XResolution) | Antalet pixlar per ResolutionUnit i ImageWidth-riktningen. |
| [YCbCrCoefficients](#YCbCrCoefficients) | Matriskoefficienterna för transformation från RGB till YCbCr-bilddata. |
| [YCbCrPositioning](#YCbCrPositioning) | Positionen för krominanskomponenterna i förhållande till luminanskomponenten. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten. |
| [YResolution](#YResolution) | Antalet pixlar per ResolutionUnit i ImageLength-riktningen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames()](#getNames--) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues()](#getValues--) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [getValues(Class<?> arg0)](#getValues-java.lang.Class----) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, String arg1)](#isDefined-java.lang.Class----java.lang.String-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [toString(long arg0)](#toString-long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


Linsens bländarvärde.

### Artist {#Artist}
```
public static final int Artist
```


Denna tagg registrerar namnet på kamerans ägare, fotograf eller bildskapare. Det detaljerade formatet är inte specificerat, men det rekommenderas att informationen skrivs enligt exemplet nedan för interoperabilitetens skull. När fältet lämnas tomt behandlas det som okänt. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James"

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Antalet bitar per bildkomponent. I denna standard är varje komponent i bilden 8 bitar, så värdet för denna tagg är 8.

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Innehåller kamerahusets serienummer

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


Ljusstyrkevärdet.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Anger färgfilterarrayens (CFA) geometriska mönster för bildsensorn när en enkelskikts färgområdessensor används. Det gäller inte alla avkänningsmetoder.

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Innehåller kamerans ägarnamn

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


Färgrymdsinformations-taggen (ColorSpace) registreras alltid som färgrymdsspecifikator.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


Komponenternas konfiguration.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Specifikt för komprimerad data; anger de komprimerade bitarna per pixel.

### Compression {#Compression}
```
public static final int Compression
```


Komprimeringsschemat som används för bilddata. När en primär bild är JPEG-komprimerad är denna beteckning onödig och utelämnas.

### Contrast {#Contrast}
```
public static final int Contrast
```


Denna tagg anger riktningen för kontrastbehandling som kameran tillämpade när bilden togs.

### Copyright {#Copyright}
```
public static final int Copyright
```


Upphovsrättsinformation. I denna standard används taggen för att ange både fotografens och redaktörens upphovsrätt. Det är upphovsrättsmeddelandet från den person eller organisation som gör anspråk på bilden. Interoperabilitetens upphovsrättsdeklaration inklusive datum och rättigheter ska skrivas i detta fält; t.ex. "Copyright, John Smith, 19xx. All rights reserved.". I denna standard registrerar fältet både fotografens och redaktörens upphovsrätt, där varje registreras i en separat del av deklarationen. När det finns en tydlig skillnad mellan fotografens och redaktörens upphovsrätt ska de skrivas i ordning fotograf följt av redaktör, separerade med NULL (i detta fall, eftersom deklarationen också avslutas med en NULL, finns två NULL-koder). När endast fotografens upphovsrätt anges, avslutas den med en NULL-kod. När endast redaktörens upphovsrätt anges, består fotografens upphovsrättsdel av ett mellanslag följt av en avslutande NULL-kod, sedan anges redaktörens upphovsrätt. När fältet lämnas tomt behandlas det som okänt.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Denna tagg anger användning av speciell bearbetning på bilddata, såsom rendering anpassad för utdata. När speciell bearbetning utförs förväntas läsaren inaktivera eller minimera ytterligare bearbetning.

### DateTime {#DateTime}
```
public static final int DateTime
```


Datum och tid för bildskapande. Enligt Exif-standarden är det datum och tid då filen ändrades.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


Datum och tid för digitalisering.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


Datumet och tiden då de ursprungliga bilddata genererades.

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Denna tagg indikerar information om fotograferingsförhållandena för en viss kameramodell. Taggen används endast för att ange fotograferingsförhållandena i läsaren.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Denna tagg anger det digitala zoomförhållandet när bilden togs. Om täljaren i det registrerade värdet är 0 indikerar det att digitalt zoom inte användes.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


En pekare till Exif IFD. Interoperabilitet, Exif IFD har samma struktur som IFD specificerad i TIFF. Vanligtvis innehåller den dock inte bilddata som i fallet med TIFF.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Exif-versionen.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


Exponeringsbiasvärdet.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Indikerar exponeringsindexet som valdes på kameran eller inmatningsenheten när bilden fångas.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Denna tagg anger exponeringsläget som sattes när bilden togs. I auto‑bracketing‑läge tar kameran en serie bilder av samma scen med olika exponeringsinställningar.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


Klassen för programmet som kameran använder för att ställa in exponeringen när bilden tas.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Exponeringstid, angiven i sekunder.

### FNumber {#FNumber}
```
public static final int FNumber
```


F-talet.

### FileSource {#FileSource}
```
public static final int FileSource
```


Filkällan.

### Flash {#Flash}
```
public static final int Flash
```


Indikerar blixtens status när bilden togs.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Indikerar strobenenergin vid tidpunkten då bilden fångas, mätt i Beam Candle Power Seconds (BCPS).

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


Flashpix-formatversionen som stöds av en FPXR-fil.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


Den faktiska brännvidden på linsen, i mm.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Denna tagg anger den ekvivalenta brännvidden för en 35 mm filmkamera, i mm. Ett värde på 0 betyder att brännvidden är okänd. Observera att denna tagg skiljer sig från FocalLength‑taggen.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Anger enheten för mätning av FocalPlaneXResolution och FocalPlaneYResolution. Detta värde är detsamma som ResolutionUnit.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Indikerar antalet pixlar i bildens bredd (X)-riktning per FocalPlaneResolutionUnit på kamerans fokalplan.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Indikerar antalet pixlar i bildens höjd (Y)-riktning per FocalPlaneResolutionUnit på kamerans fokalplan.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Anger höjden baserat på referensen i GPSAltitudeRef. Höjden uttrycks som ett RATIONAL‑värde. Referensenheten är meter.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Anger den höjd som används som referenshöjd. Om referensen är havsnivå och höjden är över havsnivå anges 0. Om höjden är under havsnivå anges värdet 1 och höjden anges som ett absolut värde i GPSAltitude‑taggen.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


En teckensträng som registrerar namnet på GPS‑området. Den första byten anger den använda teckenkoden, och därefter följer namnet på GPS‑området.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Anger GPS DOP (dataprecisionsgrad). Ett HDOP‑värde skrivs under tvådimensionell mätning och PDOP under tredimensionell mätning.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


En teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). Formatet är ÅÅÅÅ:MM:DD.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Anger kursen till destinationspunkten. Värdeintervallet är från 0,00 till 359,99.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Anger referensen som används för att ange kursen till destinationspunkten. 'T' betyder sann riktning och 'M' är magnetisk riktning.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Indikerar avståndet till destinationspunkten.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Anger enheten som används för att uttrycka avståndet till destinationspunkten. 'K', 'M' och 'N' representerar kilometer, miles och knop.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Anger latituden för destinationspunkten. Latituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder respektive. Om latituden uttrycks i grader, minuter och sekunder är ett typiskt format dd/1,mm/1,ss/1. När grader och minuter används och t.ex. bråkdelar av minuter anges med två decimaler, blir formatet dd/1,mmmm/100,0/1.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Anger om latituden för destinationspunkten är norra eller södra latitud. ASCII‑värdet 'N' betyder norra latitud och 'S' betyder södra latitud.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Anger longituden för destinationspunkten. Longituden uttrycks som tre RATIONAL-värden som ger grader, minuter och sekunder, i den ordningen. Om longitud uttrycks i grader, minuter och sekunder, skulle ett typiskt format vara ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med upp till två decimaler, skulle formatet vara ddd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Anger om longituden för destinationspunkten är östlig eller västlig. ASCII 'E' indikerar östlig longitud, och 'W' är västlig longitud.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Indikerar om differentialkorrektion tillämpas på GPS-mottagaren.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


gps IFD‑pekaren.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Anger bildens riktning när den togs. Värdeintervallet är från 0.00 till 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Anger referensen för att ange bildens riktning när den tas. 'T' betecknar sann riktning och 'M' är magnetisk riktning.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Anger latituden. Latituden uttrycks som tre RATIONAL-värden som ger grader, minuter och sekunder, i den ordningen. Om latitud uttrycks i grader, minuter och sekunder, skulle ett typiskt format vara dd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med upp till två decimaler, skulle formatet vara dd/1,mmmm/100,0/1.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Indikerar om latituden är nordlig eller sydlig.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Anger longituden. Longituden uttrycks som tre RATIONAL-värden som ger grader, minuter och sekunder, i den ordningen. Om longitud uttrycks i grader, minuter och sekunder, skulle ett typiskt format vara ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med upp till två decimaler, skulle formatet vara ddd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Indikerar om longituden är östlig eller västlig.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Indikerar de geodetiska kartdata som används av GPS-mottagaren.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Anger GPS-mätningsläget. - 2- eller 3-dimensionellt.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


En teckensträng som registrerar namnet på den metod som används för positionsbestämning. Den första byten indikerar den teckenkod som används, och detta följs av metodens namn.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Anger de GPS-satelliter som används för mätningar. Denna tagg kan användas för att beskriva antalet satelliter, deras ID-nummer, höjdvinkel, azimut, SNR och annan information i ASCII-notation. Formatet är inte specificerat. Om GPS-mottagaren inte kan utföra mätningar ska taggens värde sättas till NULL.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Indikerar hastigheten för GPS‑mottagarens rörelse.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Anger enheten som används för att uttrycka GPS-mottagarens rörelsehastighet. 'K', 'M' och 'N' representerar kilometer per timme, miles per timme och knop.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Indikerar GPS‑mottagarens status när bilden spelas in.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Anger tiden som UTC (Coordinated Universal Time). Tidsstämpeln uttrycks som tre RATIONAL-värden som ger timme, minut och sekund.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Anger GPS-mottagarens rörelseriktning. Värdeintervallet är från 0.00 till 359.99.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Anger referensen för att ange GPS-mottagarens rörelseriktning. 'T' betecknar sann riktning och 'M' är magnetisk riktning.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Anger versionen av GPSInfoIFD.

### GainControl {#GainControl}
```
public static final int GainControl
```


Denna tagg anger graden av total bildförstärkningsjustering.

### Gamma {#Gamma}
```
public static final int Gamma
```


Gammavärde

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Information om ISO-hastighetsvärde enligt ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Denna tagg anger ISO-hastighetslatitud yyy-värde enligt ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Denna tagg anger ISO-hastighetslatitud zzz-värde enligt ISO 12232

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


En teckensträng som ger bildens titel. Det kan vara en kommentar såsom "1988 company picnic" eller liknande.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Antalet rader av bilddata.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


Bildens unika ID.

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Antalet kolumner av bilddata, lika med antalet pixlar per rad.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


Förskjutningen till startbyten (SOI) för JPEG-komprimerad miniatyrbildsdata. Detta används inte för primära bildens JPEG-data.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


Antalet byte av JPEG-komprimerad miniatyrbildsdata. Detta används inte för primära bild-JPEG-data. JPEG-miniatyrbilder delas inte utan registreras som en kontinuerlig JPEG-bitström från SOI till EOI. Appn- och COM-markörer bör inte registreras. Komprimerade miniatyrbilder får inte registreras i mer än 64 Kbyte, inklusive all annan data som ska registreras i APP1.

### LensMake {#LensMake}
```
public static final int LensMake
```


Denna tagg registrerar objektivtillverkare

### LensModel {#LensModel}
```
public static final int LensModel
```


Denna tagg registrerar objektivets modellnamn och modellnummer

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Denna tagg registrerar serienumret för utbytbart objektiv

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Denna tagg noterar minsta brännvidd, största brännvidd, lägsta bländartal vid minsta brännvidd och lägsta bländartal vid största brännvidd

### LightSource {#LightSource}
```
public static final int LightSource
```


Typ av ljuskälla.

### Make {#Make}
```
public static final int Make
```


Tillverkaren av inspelningsutrustningen. Detta är tillverkaren av DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


En tagg för tillverkare av Exif‑skrivare att registrera valfri information. Innehållet bestäms av tillverkaren, men denna tagg bör inte användas för annat än dess avsedda syfte.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


Det maximala bländartalet.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


Mätningsläget.

### Model {#Model}
```
public static final int Model
```


Modellnamnet eller modellnumret på utrustningen. Detta är modellnamnet eller -numret på DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt.

### OECF {#OECF}
```
public static final int OECF
```


Anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524.

### Orientation {#Orientation}
```
public static final int Orientation
```


Bildens orientering betraktad i termer av rader och kolumner.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Anger ISO‑hastigheten och ISO‑latituden för kameran eller inmatningsenheten enligt ISO 12232.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


Pixelkompositionen.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Information som är specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga bredden på den meningsfulla bilden registreras i denna tagg, oavsett om det finns utfyllnadsdata eller en omstartsmarkör.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Information som är specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga höjden på den meningsfulla bilden registreras i denna tagg.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Anger om pixelelement registreras i ett chunky- eller planarformat. Om detta fält inte finns antas TIFF‑standardvärdet 1 (chunky).

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


Färgens kromaticitet för bildens tre primära färger. Normalt är denna tagg onödig, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace‑taggen.

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Anger rekommenderat exponeringsindex

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


Referensvärdet för svartpunkt och referensvärdet för vitpunkt. Inga standardvärden ges i TIFF, men värdena nedan anges som standard här. Färgrymden deklareras i en färgrymdsinformations‑tagg, där standardvärdet är det som ger de optimala bildegenskaperna för interoperabilitet under dessa förhållanden.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


Den relaterade ljudfilen.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


Enheten för mätning av XResolution och YResolution. Samma enhet används för både XResolution och YResolution. Om bildens upplösning är okänd anges 2 (tum).

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Antalet rader per strip. Detta är antalet rader i bilden för en strip när en bild delas upp i strips.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Antalet komponenter per pixel. Eftersom denna standard gäller för RGB- och YCbCr‑bilder är värdet för denna tagg 3.

### Saturation {#Saturation}
```
public static final int Saturation
```


Denna tagg anger riktningen för mättnadsbehandling som kameran tillämpade när bilden togs.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Denna tagg anger vilken typ av scen som fotograferades. Den kan också användas för att registrera vilket läge bilden togs i.

### SceneType {#SceneType}
```
public static final int SceneType
```


Anger scenens typ. Om en DSC registrerade bilden ska detta taggvärde alltid vara 1, vilket indikerar att bilden fotograferades direkt.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Anger bildsensortypen på kameran eller inmatningsenheten.

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Typ av fotografisk känslighet

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Denna tagg anger riktningen för skärpebehandling som kameran tillämpade när bilden togs

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


Värdet för slutartiden.

### Software {#Software}
```
public static final int Software
```


Denna tagg registrerar namn och version på programvaran eller firmware för kameran eller bildinmatningsenheten som användes för att skapa bilden. Det detaljerade formatet är inte specificerat, men det rekommenderas att följa exemplet nedan. När fältet lämnas tomt behandlas det som okänt.

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Denna tagg registrerar kamerans eller inmatningsenhetens rumsliga frekvenstabell och SFR‑värden i bildens bredd‑, höjd‑ och diagonalriktning, enligt ISO 12233.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Anger den spektrala känsligheten för varje kanal i den använda kameran.

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Anger standardutgångskänsligheten för kameran

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Det totala antalet byte i varje strip.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


För varje strip, byte‑offseten för den strippen. Det rekommenderas att detta väljs så att antalet strip‑byte inte överstiger 64 Kbyte. Aux‑tagg.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Denna tagg anger platsen och området för huvudmotivet i den övergripande scenen.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


Avståndet till motivet, angivet i meter.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Denna tagg anger avståndet till motivet.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Anger platsen för huvudobjektet i scenen. Värdet för denna tagg representerar pixeln i mitten av huvudobjektet relativt till vänster kant, före rotationsbearbetning enligt Rotation‑taggen.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


En tagg som används för att registrera bråkdelar av sekunder för taggen DateTime.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


En tagg som används för att registrera bråkdelar av sekunder för taggen DateTimeDigitized.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


En tagg som används för att registrera bråkdelar av sekunder för taggen DateTimeOriginal.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


En överföringsfunktion för bilden, beskriven i tabellformat. Normalt är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen ColorSpace‑tagg.

### UserComment {#UserComment}
```
public static final int UserComment
```


En tagg för Exif-användare att skriva nyckelord eller kommentarer på bilden förutom de i ImageDescription, och utan teckenkodningsbegränsningarna för taggen ImageDescription.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Denna tagg anger vitbalansläget som sattes när bilden togs.

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


Kromaticiteten för bildens vitpunkt. Normalt är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen ColorSpace‑tagg.

### XResolution {#XResolution}
```
public static final int XResolution
```


Antalet pixlar per ResolutionUnit i ImageWidth‑riktningen. När bildens upplösning är okänd anges 72 [dpi].

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


Matriskoefficienterna för transformation från RGB till YCbCr-bilddata.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


Placeringen av krominanskomponenterna i förhållande till luminanskomponenten. Detta fält är avsett endast för JPEG-komprimerad data eller okomprimerad YCbCr-data. TIFF‑standardvärdet är 1 (centrerat); men när Y:Cb:Cr = 4:2:2 rekommenderas i denna standard att 2 (sido‑placerat) används för att lagra data, för att förbättra bildkvaliteten vid visning på TV‑system. När detta fält saknas ska läsaren anta TIFF‑standardvärdet. I fallet Y:Cb:Cr = 4:2:0 rekommenderas TIFF‑standardvärdet (centrerat). Om läsaren inte har möjlighet att stödja båda typerna av YCbCrPositioning ska den följa TIFF‑standardvärdet oavsett värdet i detta fält. Det är önskvärt att läsare kan stödja både centrerad och sido‑placerad positionering.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten.

### YResolution {#YResolution}
```
public static final int YResolution
```


Antalet pixlar per ResolutionUnit i ImageLength‑riktningen. Samma värde som XResolution anges.

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames() {#getNames--}
```
public String[] getNames()
```




**Returns:**
java.lang.String[]
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues() {#getValues--}
```
public Long[] getValues()
```




**Returns:**
java.lang.Long[]
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Long[]
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, String arg1) {#isDefined-java.lang.Class----java.lang.String-}
```
public static boolean isDefined(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### toString(long arg0) {#toString-long-}
```
public String toString(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

