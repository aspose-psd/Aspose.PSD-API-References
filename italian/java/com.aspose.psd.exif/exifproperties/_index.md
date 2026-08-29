---
title: "ExifProperties"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Elenco dei tag EXIF"
type: docs
weight: 11
url: /it/java/com.aspose.psd.exif/exifproperties/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Elenco dei tag EXIF
## Campi

| Campo | Descrizione |
| --- | --- |
| [ApertureValue](#ApertureValue) | Il valore dell'apertura dell'obiettivo. |
| [Artist](#Artist) | Questo tag registra il nome del proprietario della fotocamera, del fotografo o del creatore dell'immagine. |
| [BitsPerSample](#BitsPerSample) | Il numero di bit per componente dell'immagine. |
| [BodySerialNumber](#BodySerialNumber) | Contiene il numero di serie del corpo della fotocamera |
| [BrightnessValue](#BrightnessValue) | Il valore di luminosità. |
| [CFAPattern](#CFAPattern) | Indica il motivo geometrico della matrice di filtro colore (CFA) del sensore d'immagine quando viene utilizzato un sensore a zona colore a chip unico. |
| [CameraOwnerName](#CameraOwnerName) | Contiene il nome del proprietario della fotocamera |
| [ColorSpace](#ColorSpace) | Il tag di informazione dello spazio colore (ColorSpace) è sempre registrato come specificatore dello spazio colore. |
| [ComponentsConfiguration](#ComponentsConfiguration) | La configurazione dei componenti. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Specifico per dati compressi; indica i bit compressi per pixel. |
| [Compression](#Compression) | Lo schema di compressione utilizzato per i dati dell'immagine. |
| [Contrast](#Contrast) | Questo tag indica la direzione dell'elaborazione del contrasto applicata dalla fotocamera quando l'immagine è stata scattata. |
| [Copyright](#Copyright) | Informazioni sul copyright. |
| [CustomRendered](#CustomRendered) | Questo tag indica l'uso di elaborazioni speciali sui dati dell'immagine, come il rendering orientato all'output. |
| [DateTime](#DateTime) | La data e l'ora di creazione dell'immagine. |
| [DateTimeDigitized](#DateTimeDigitized) | La data e l'ora di digitalizzazione. |
| [DateTimeOriginal](#DateTimeOriginal) | La data e l'ora in cui sono stati generati i dati originali dell'immagine. |
| [DeviceSettingDescription](#DeviceSettingDescription) | Questo tag indica informazioni sulle condizioni di scatto di un modello di fotocamera specifico. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Questo tag indica il rapporto di zoom digitale al momento dello scatto dell'immagine. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExifIfdPointer](#ExifIfdPointer) | Un puntatore all'IFD Exif. |
| [ExifVersion](#ExifVersion) | La versione Exif. |
| [ExposureBiasValue](#ExposureBiasValue) | Il valore di compensazione dell'esposizione. |
| [ExposureIndex](#ExposureIndex) | Indica l'indice di esposizione selezionato sulla fotocamera o sul dispositivo di input al momento della cattura dell'immagine. |
| [ExposureMode](#ExposureMode) | Questo tag indica la modalità di esposizione impostata al momento dello scatto dell'immagine. |
| [ExposureProgram](#ExposureProgram) | La classe del programma usato dalla fotocamera per impostare l'esposizione quando viene scattata la foto. |
| [ExposureTime](#ExposureTime) | Tempo di esposizione, espresso in secondi. |
| [FNumber](#FNumber) | Il numero F. |
| [FileSource](#FileSource) | La fonte del file. |
| [Flash](#Flash) | Indica lo stato del flash al momento dello scatto dell'immagine. |
| [FlashEnergy](#FlashEnergy) | Indica l'energia dello stroboscopio al momento della cattura dell'immagine, misurata in Beam Candle Power Seconds (BCPS). |
| [FlashpixVersion](#FlashpixVersion) | La versione del formato Flashpix supportata da un file FPXR. |
| [FocalLength](#FocalLength) | La lunghezza focale effettiva dell'obiettivo, in mm. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Questo tag indica la lunghezza focale equivalente assumendo una fotocamera a pellicola da 35 mm, in mm. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indica l'unità di misura per FocalPlaneXResolution e FocalPlaneYResolution. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indica il numero di pixel nella direzione della larghezza (X) dell'immagine per FocalPlaneResolutionUnit sul piano focale della fotocamera. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indica il numero di pixel nella direzione dell'altezza (Y) dell'immagine per FocalPlaneResolutionUnit sul piano focale della fotocamera. |
| [GPSAltitude](#GPSAltitude) | Indica l'altitudine basata sul riferimento in GPSAltitudeRef. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Indica l'altitudine usata come altitudine di riferimento. |
| [GPSAreaInformation](#GPSAreaInformation) | Una stringa di caratteri che registra il nome dell'area GPS. |
| [GPSDOP](#GPSDOP) | Indica il GPS DOP (grado di precisione dei dati). |
| [GPSDateStamp](#GPSDateStamp) | Una stringa di caratteri che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale). |
| [GPSDestBearing](#GPSDestBearing) | Indica la rotta verso il punto di destinazione. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Indica il riferimento usato per fornire la rotta al punto di destinazione. |
| [GPSDestDistance](#GPSDestDistance) | Indica la distanza al punto di destinazione. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Indica l'unità usata per esprimere la distanza al punto di destinazione. |
| [GPSDestLatitude](#GPSDestLatitude) | Indica la latitudine del punto di destinazione. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Indica se la latitudine del punto di destinazione è nord o sud. |
| [GPSDestLongitude](#GPSDestLongitude) | Indica la longitudine del punto di destinazione. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Indica se la longitudine del punto di destinazione è est o ovest. |
| [GPSDifferential](#GPSDifferential) | Indica se la correzione differenziale è applicata al ricevitore GPS. |
| [GPSIfdPointer](#GPSIfdPointer) | Il puntatore gps ifd. |
| [GPSImgDirection](#GPSImgDirection) | Indica la direzione dell'immagine al momento della cattura. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Indica il riferimento per fornire la direzione dell'immagine al momento della cattura. |
| [GPSLatitude](#GPSLatitude) | Indica la latitudine. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Indica se la latitudine è nord o sud. |
| [GPSLongitude](#GPSLongitude) | Indica la longitudine. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Indica se la longitudine è est o ovest. |
| [GPSMapDatum](#GPSMapDatum) | Indica i dati di rilievo geodetico usati dal ricevitore GPS. |
| [GPSMeasureMode](#GPSMeasureMode) | Indica la modalità di misura GPS. |
| [GPSProcessingMethod](#GPSProcessingMethod) | Una stringa di caratteri che registra il nome del metodo usato per la ricerca della posizione. |
| [GPSSatellites](#GPSSatellites) | Indica i satelliti GPS usati per le misurazioni. |
| [GPSSpeed](#GPSSpeed) | Indica la velocità del movimento del ricevitore GPS. |
| [GPSSpeedRef](#GPSSpeedRef) | Indica l'unità usata per esprimere la velocità di movimento del ricevitore GPS. |
| [GPSStatus](#GPSStatus) | Indica lo stato del ricevitore GPS quando l'immagine è registrata. |
| [GPSTimestamp](#GPSTimestamp) | Indica l'ora come UTC (Tempo Coordinato Universale). |
| [GPSTrack](#GPSTrack) | Indica la direzione del movimento del ricevitore GPS. |
| [GPSTrackRef](#GPSTrackRef) | Indica il riferimento per fornire la direzione del movimento del ricevitore GPS. |
| [GPSVersionID](#GPSVersionID) | Indica la versione di GPSInfoIFD. |
| [GainControl](#GainControl) | Questo tag indica il grado di regolazione del guadagno complessivo dell'immagine. |
| [Gamma](#Gamma) | Valore gamma |
| [ISOSpeed](#ISOSpeed) | Informazioni sul valore di velocità ISO come definito nella ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Questo tag indica il valore di latitudine della velocità ISO yyy come definito nella ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Questo tag indica il valore di latitudine della velocità ISO zzz come definito nella ISO 12232 |
| [ImageDescription](#ImageDescription) | Una stringa di caratteri che fornisce il titolo dell'immagine. |
| [ImageLength](#ImageLength) | Il numero di righe dei dati dell'immagine. |
| [ImageUniqueID](#ImageUniqueID) | L'ID univoco dell'immagine. |
| [ImageWidth](#ImageWidth) | Il numero di colonne dei dati dell'immagine, pari al numero di pixel per riga. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | L'offset al byte di inizio (SOI) dei dati della miniatura compressa JPEG. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | Il numero di byte dei dati della miniatura compressa JPEG. |
| [LensMake](#LensMake) | Questo tag registra il produttore dell'obiettivo |
| [LensModel](#LensModel) | Questo tag registra il nome modello e il numero modello dell'obiettivo |
| [LensSerialNumber](#LensSerialNumber) | Questo tag registra il numero di serie dell'obiettivo intercambiabile |
| [LensSpecification](#LensSpecification) | Questo tag indica la lunghezza focale minima, la lunghezza focale massima, il numero F minimo alla lunghezza focale minima e il numero F minimo alla lunghezza focale massima |
| [LightSource](#LightSource) | Il tipo di sorgente luminosa. |
| [Make](#Make) | Il produttore dell'attrezzatura di registrazione. |
| [MakerNote](#MakerNote) | Un tag per i produttori di scrittori Exif per registrare qualsiasi informazione desiderata. |
| [MaxApertureValue](#MaxApertureValue) | Il valore dell'apertura massima. |
| [MeteringMode](#MeteringMode) | La modalità di misurazione. |
| [Model](#Model) | Il nome modello o il numero modello dell'attrezzatura. |
| [OECF](#OECF) | Indica la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| [Orientation](#Orientation) | L'orientamento dell'immagine visualizzato in termini di righe e colonne. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Indica la velocità ISO e la latitudine ISO della fotocamera o del dispositivo di input come specificato nella ISO 12232. |
| [PhotometricInterpretation](#PhotometricInterpretation) | La composizione dei pixel. |
| [PixelXDimension](#PixelXDimension) | Informazioni specifiche sui dati compressi. |
| [PixelYDimension](#PixelYDimension) | Informazioni specifiche sui dati compressi. |
| [PlanarConfiguration](#PlanarConfiguration) | Indica se i componenti dei pixel sono registrati in formato chunk o planare. |
| [PrimaryChromaticities](#PrimaryChromaticities) | La cromaticità dei tre colori primari dell'immagine. |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Indica l'indice di esposizione consigliato |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Il valore del punto nero di riferimento e il valore del punto bianco di riferimento. |
| [RelatedSoundFile](#RelatedSoundFile) | Il file audio correlato. |
| [ResolutionUnit](#ResolutionUnit) | L'unità di misura per XResolution e YResolution. |
| [RowsPerStrip](#RowsPerStrip) | Il numero di righe per striscia. |
| [SamplesPerPixel](#SamplesPerPixel) | Il numero di componenti per pixel. |
| [Saturation](#Saturation) | Questo tag indica la direzione dell'elaborazione della saturazione applicata dalla fotocamera quando l'immagine è stata scattata. |
| [SceneCaptureType](#SceneCaptureType) | Questo tag indica il tipo di scena che è stata scattata. |
| [SceneType](#SceneType) | Indica il tipo di scena. |
| [SensingMethod](#SensingMethod) | Indica il tipo di sensore d'immagine sulla fotocamera o sul dispositivo di input. |
| [SensitivityType](#SensitivityType) | Tipo di sensibilità fotografica |
| [Sharpness](#Sharpness) | Questo tag indica la direzione dell'elaborazione della nitidezza applicata dalla fotocamera quando l'immagine è stata scattata |
| [ShutterSpeedValue](#ShutterSpeedValue) | Il valore della velocità dell'otturatore. |
| [Software](#Software) | Questo tag registra il nome e la versione del software o del firmware della fotocamera o del dispositivo di input immagine utilizzato per generare l'immagine. |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Questo tag registra la tabella di frequenza spaziale della fotocamera o del dispositivo di input e i valori SFR nella direzione della larghezza dell'immagine, dell'altezza dell'immagine e della direzione diagonale, come specificato nella ISO 12233. |
| [SpectralSensitivity](#SpectralSensitivity) | Indica la sensibilità spettrale di ciascun canale della fotocamera utilizzata. |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Indica la sensibilità di uscita standard della fotocamera |
| [StripByteCounts](#StripByteCounts) | Il numero totale di byte in ogni striscia. |
| [StripOffsets](#StripOffsets) | Per ogni striscia, l'offset in byte di quella striscia. |
| [SubjectArea](#SubjectArea) | Questo tag indica la posizione e l'area del soggetto principale nella scena complessiva. |
| [SubjectDistance](#SubjectDistance) | La distanza dal soggetto, espressa in metri. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Questo tag indica la distanza dal soggetto. |
| [SubjectLocation](#SubjectLocation) | Indica la posizione del soggetto principale nella scena. |
| [SubsecTime](#SubsecTime) | Un tag usato per registrare le frazioni di secondo per il tag DateTime. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | Un tag usato per registrare le frazioni di secondo per il tag DateTimeDigitized. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | Un tag usato per registrare le frazioni di secondo per il tag DateTimeOriginal. |
| [TransferFunction](#TransferFunction) | Una funzione di trasferimento per l'immagine, descritta in forma tabellare. |
| [UserComment](#UserComment) | Un tag per gli utenti Exif per scrivere parole chiave o commenti sull'immagine oltre a quelli in ImageDescription, e senza le limitazioni di codifica dei caratteri del tag ImageDescription. |
| [WhiteBalance](#WhiteBalance) | Questo tag indica la modalità di bilanciamento del bianco impostata quando l'immagine è stata scattata. |
| [WhitePoint](#WhitePoint) | La cromaticità del punto bianco dell'immagine. |
| [XResolution](#XResolution) | Il numero di pixel per ResolutionUnit nella direzione ImageWidth. |
| [YCbCrCoefficients](#YCbCrCoefficients) | I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr. |
| [YCbCrPositioning](#YCbCrPositioning) | La posizione dei componenti di crominanza rispetto al componente di luminanza. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza. |
| [YResolution](#YResolution) | Il numero di pixel per ResolutionUnit nella direzione ImageLength. |
## Metodi

| Metodo | Descrizione |
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


Il valore dell'apertura dell'obiettivo.

### Artist {#Artist}
```
public static final int Artist
```


Questo tag registra il nome del proprietario della fotocamera, del fotografo o del creatore dell'immagine. Il formato dettagliato non è specificato, ma si raccomanda di scrivere le informazioni come nell'esempio seguente per facilitare l'Interoperabilità. Quando il campo è lasciato vuoto, viene considerato sconosciuto. Es.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James"

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Il numero di bit per componente dell'immagine. In questo standard ogni componente dell'immagine è di 8 bit, quindi il valore per questo tag è 8.

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Contiene il numero di serie del corpo della fotocamera

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


Il valore di luminosità.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indica il modello geometrico della matrice di filtri colore (CFA) del sensore d'immagine quando viene utilizzato un sensore a zona colore a chip singolo. Non si applica a tutti i metodi di rilevamento.

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Contiene il nome del proprietario della fotocamera

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


Il tag di informazione dello spazio colore (ColorSpace) è sempre registrato come specificatore dello spazio colore.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


La configurazione dei componenti.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Specifico per dati compressi; indica i bit compressi per pixel.

### Compression {#Compression}
```
public static final int Compression
```


Lo schema di compressione usato per i dati dell'immagine. Quando un'immagine primaria è compressa JPEG, questa designazione non è necessaria e viene omessa.

### Contrast {#Contrast}
```
public static final int Contrast
```


Questo tag indica la direzione dell'elaborazione del contrasto applicata dalla fotocamera quando l'immagine è stata scattata.

### Copyright {#Copyright}
```
public static final int Copyright
```


Informazioni sul copyright. In questo standard il tag è usato per indicare sia i diritti d'autore del fotografo sia quelli dell'editore. È l'avviso di copyright della persona o dell'organizzazione che rivendica i diritti sull'immagine. L'affermazione di copyright per l'Interoperabilità, inclusi data e diritti, dovrebbe essere scritta in questo campo; ad esempio, "Copyright, John Smith, 19xx. All rights reserved.". In questo standard il campo registra sia i diritti d'autore del fotografo sia quelli dell'editore, ciascuno registrato in una parte separata della dichiarazione. Quando c'è una chiara distinzione tra i diritti d'autore del fotografo e dell'editore, questi devono essere scritti nell'ordine fotografo seguito dal copyright dell'editore, separati da NULL (in questo caso, poiché la dichiarazione termina anche con un NULL, ci sono due codici NULL). Quando è fornito solo il copyright del fotografo, viene terminato da un codice NULL. Quando è fornito solo il copyright dell'editore, la parte del copyright del fotografo consiste in uno spazio seguito da un codice NULL terminante, poi viene fornito il copyright dell'editore. Quando il campo è lasciato vuoto, viene considerato sconosciuto.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Questo tag indica l'uso di elaborazioni speciali sui dati dell'immagine, come il rendering orientato all'output. Quando viene eseguita un'elaborazione speciale, ci si aspetta che il lettore disabiliti o minimizzi ulteriori elaborazioni.

### DateTime {#DateTime}
```
public static final int DateTime
```


La data e l'ora di creazione dell'immagine. Nello standard Exif, è la data e l'ora in cui il file è stato modificato.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


La data e l'ora di digitalizzazione.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


La data e l'ora in cui sono stati generati i dati originali dell'immagine.

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Questo tag indica informazioni sulle condizioni di scatto di un modello di fotocamera specifico. Il tag è usato solo per indicare le condizioni di scatto nel lettore.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Questo tag indica il rapporto di zoom digitale quando l'immagine è stata scattata. Se il numeratore del valore registrato è 0, ciò indica che lo zoom digitale non è stato utilizzato.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Un puntatore al Exif IFD. L'Interoperabilità, Exif IFD ha la stessa struttura dell'IFD specificato in TIFF. Tuttavia, normalmente non contiene dati immagine come nel caso di TIFF.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


La versione Exif.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


Il valore di compensazione dell'esposizione.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Indica l'indice di esposizione selezionato sulla fotocamera o sul dispositivo di input al momento della cattura dell'immagine.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Questo tag indica la modalità di esposizione impostata quando l'immagine è stata scattata. In modalità auto-bracketing, la fotocamera scatta una serie di fotogrammi della stessa scena con impostazioni di esposizione diverse.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


La classe del programma usato dalla fotocamera per impostare l'esposizione quando viene scattata la foto.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Tempo di esposizione, espresso in secondi.

### FNumber {#FNumber}
```
public static final int FNumber
```


Il numero F.

### FileSource {#FileSource}
```
public static final int FileSource
```


La fonte del file.

### Flash {#Flash}
```
public static final int Flash
```


Indica lo stato del flash al momento dello scatto dell'immagine.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Indica l'energia dello stroboscopio al momento della cattura dell'immagine, misurata in Beam Candle Power Seconds (BCPS).

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


La versione del formato Flashpix supportata da un file FPXR.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


La lunghezza focale effettiva dell'obiettivo, in mm.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Questo tag indica la lunghezza focale equivalente assumendo una fotocamera a pellicola da 35 mm, in mm. Un valore di 0 indica che la lunghezza focale è sconosciuta. Nota che questo tag differisce dal tag FocalLength.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indica l'unità di misura per FocalPlaneXResolution e FocalPlaneYResolution. Questo valore è lo stesso di ResolutionUnit.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Indica il numero di pixel nella direzione della larghezza (X) dell'immagine per FocalPlaneResolutionUnit sul piano focale della fotocamera.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Indica il numero di pixel nella direzione dell'altezza (Y) dell'immagine per FocalPlaneResolutionUnit sul piano focale della fotocamera.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Indica l'altitudine basata sul riferimento in GPSAltitudeRef. L'altitudine è espressa come un valore RATIONAL. L'unità di riferimento è il metro.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Indica l'altitudine usata come altitudine di riferimento. Se il riferimento è il livello del mare e l'altitudine è sopra il livello del mare, viene fornito 0. Se l'altitudine è sotto il livello del mare, viene fornito 1 e l'altitudine è indicata come valore assoluto nel tag GPSAltitude.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


Una stringa di caratteri che registra il nome dell'area GPS. Il primo byte indica il codice dei caratteri usato, seguito dal nome dell'area GPS.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Indica il GPS DOP (degree of precision dei dati). Un valore HDOP viene registrato durante la misurazione bidimensionale, e PDOP durante la misurazione tridimensionale.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


Una stringa di caratteri che registra le informazioni di data e ora relative a UTC (Coordinated Universal Time). Il formato è YYYY:MM:DD.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Indica la direzione verso il punto di destinazione. L'intervallo di valori è da 0,00 a 359,99.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Indica il riferimento usato per fornire la direzione verso il punto di destinazione. 'T' indica la direzione vera e 'M' la direzione magnetica.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Indica la distanza al punto di destinazione.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Indica l'unità usata per esprimere la distanza al punto di destinazione. 'K', 'M' e 'N' rappresentano chilometri, miglia e nodi.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Indica la latitudine del punto di destinazione. La latitudine è espressa come tre valori RATIONAL che forniscono i gradi, i minuti e i secondi, rispettivamente. Se la latitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe dd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due cifre decimali, il formato sarebbe dd/1,mmmm/100,0/1.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Indica se la latitudine del punto di destinazione è nord o sud. Il valore ASCII 'N' indica latitudine nord, e 'S' indica latitudine sud.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Indica la longitudine del punto di destinazione. La longitudine è espressa come tre valori RATIONAL che forniscono i gradi, i minuti e i secondi, rispettivamente. Se la longitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe ddd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due cifre decimali, il formato sarebbe ddd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Indica se la longitudine del punto di destinazione è est o ovest. L'ASCII 'E' indica longitudine est, e 'W' indica longitudine ovest.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Indica se la correzione differenziale è applicata al ricevitore GPS.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


Il puntatore gps ifd.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Indica la direzione dell'immagine al momento della cattura. L'intervallo di valori è da 0,00 a 359,99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Indica il riferimento per fornire la direzione dell'immagine al momento della cattura. 'T' indica la direzione vera e 'M' la direzione magnetica.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indica la latitudine. La latitudine è espressa come tre valori RATIONAL che forniscono i gradi, i minuti e i secondi, rispettivamente. Se la latitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe dd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due cifre decimali, il formato sarebbe dd/1,mmmm/100,0/1.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Indica se la latitudine è nord o sud.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Indica la longitudine. La longitudine è espressa come tre valori RATIONAL che forniscono i gradi, i minuti e i secondi, rispettivamente. Se la longitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe ddd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due cifre decimali, il formato sarebbe ddd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Indica se la longitudine è est o ovest.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Indica i dati di rilievo geodetico usati dal ricevitore GPS.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Indica la modalità di misurazione GPS. - 2- o 3-dimensionale.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


Una stringa di caratteri che registra il nome del metodo utilizzato per la ricerca della posizione. Il primo byte indica il codice carattere usato, seguito dal nome del metodo.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Indica i satelliti GPS utilizzati per le misurazioni. Questo tag può essere usato per descrivere il numero di satelliti, il loro ID, l'angolo di elevazione, l'azimut, il SNR e altre informazioni in notazione ASCII. Il formato non è specificato. Se il ricevitore GPS non è in grado di effettuare misurazioni, il valore del tag deve essere impostato a NULL.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Indica la velocità del movimento del ricevitore GPS.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Indica l'unità usata per esprimere la velocità di movimento del ricevitore GPS. 'K', 'M' e 'N' rappresentano chilometri all'ora, miglia all'ora e nodi.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Indica lo stato del ricevitore GPS quando l'immagine è registrata.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Indica l'ora in UTC (Coordinated Universal Time). Il TimeStamp è espresso come tre valori RATIONAL che forniscono ora, minuto e secondo.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Indica la direzione del movimento del ricevitore GPS. L'intervallo di valori è da 0,00 a 359,99.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Indica il riferimento per fornire la direzione del movimento del ricevitore GPS. 'T' denota la direzione vera e 'M' la direzione magnetica.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Indica la versione di GPSInfoIFD.

### GainControl {#GainControl}
```
public static final int GainControl
```


Questo tag indica il grado di regolazione del guadagno complessivo dell'immagine.

### Gamma {#Gamma}
```
public static final int Gamma
```


Valore gamma

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Informazioni sul valore di velocità ISO come definito nella ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Questo tag indica il valore di latitudine della velocità ISO yyy come definito nella ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Questo tag indica il valore di latitudine della velocità ISO zzz come definito nella ISO 12232

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Una stringa di caratteri che fornisce il titolo dell'immagine. Può essere un commento come "1988 company picnic" o simili.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Il numero di righe dei dati dell'immagine.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


L'ID univoco dell'immagine.

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Il numero di colonne dei dati dell'immagine, pari al numero di pixel per riga.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


L'offset al byte di inizio (SOI) dei dati della miniatura JPEG compressa. Questo non è usato per i dati JPEG dell'immagine principale.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


Il numero di byte dei dati della miniatura JPEG compressa. Questo non è usato per i dati JPEG dell'immagine principale. Le miniature JPEG non sono divise ma sono registrate come un flusso continuo JPEG dal SOI all'EOI. I marker Appn e COM non devono essere registrati. Le miniature compresse devono essere registrate in non più di 64 Kbyte, includendo tutti gli altri dati da registrare in APP1.

### LensMake {#LensMake}
```
public static final int LensMake
```


Questo tag registra il produttore dell'obiettivo

### LensModel {#LensModel}
```
public static final int LensModel
```


Questo tag registra il nome modello e il numero modello dell'obiettivo

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Questo tag registra il numero di serie dell'obiettivo intercambiabile

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Questo tag indica la lunghezza focale minima, la lunghezza focale massima, il numero F minimo alla lunghezza focale minima e il numero F minimo alla lunghezza focale massima

### LightSource {#LightSource}
```
public static final int LightSource
```


Il tipo di sorgente luminosa.

### Make {#Make}
```
public static final int Make
```


Il produttore dell'attrezzatura di registrazione. Questo è il produttore del DSC, scanner, digitalizzatore video o altra attrezzatura che ha generato l'immagine. Quando il campo è lasciato vuoto, viene considerato sconosciuto.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Un tag per i produttori di scrittori Exif per registrare qualsiasi informazione desiderata. Il contenuto è a discrezione del produttore, ma questo tag non dovrebbe essere usato per altro scopo rispetto a quello previsto.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


Il valore dell'apertura massima.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


La modalità di misurazione.

### Model {#Model}
```
public static final int Model
```


Il nome modello o il numero modello dell'attrezzatura. Questo è il nome o il numero modello del DSC, scanner, digitalizzatore video o altra attrezzatura che ha generato l'immagine. Quando il campo è lasciato vuoto, viene considerato sconosciuto.

### OECF {#OECF}
```
public static final int OECF
```


Indica la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

### Orientation {#Orientation}
```
public static final int Orientation
```


L'orientamento dell'immagine visualizzato in termini di righe e colonne.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Indica la velocità ISO e la latitudine ISO della fotocamera o del dispositivo di input come specificato nella ISO 12232.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


La composizione dei pixel.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Informazioni specifiche per i dati compressi. Quando un file compresso è registrato, la larghezza valida dell'immagine significativa deve essere registrata in questo tag, indipendentemente dalla presenza di dati di riempimento o di un marker di riavvio.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Informazioni specifiche per i dati compressi. Quando un file compresso è registrato, l'altezza valida dell'immagine significativa deve essere registrata in questo tag.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Indica se i componenti dei pixel sono registrati in formato chunky o planar. Se questo campo non esiste, si assume il valore predefinito TIFF di 1 (chunky).

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


La cromaticità dei tre colori primari dell'immagine. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag informativo ColorSpace.

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Indica l'indice di esposizione consigliato

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


Il valore del punto nero di riferimento e del punto bianco di riferimento. Non sono forniti valori predefiniti in TIFF, ma i valori qui sotto sono indicati come predefiniti. Lo spazio colore è dichiarato in un tag informativo sullo spazio colore, con il valore predefinito che fornisce le caratteristiche ottimali dell'immagine Interoperability in queste condizioni.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


Il file audio correlato.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


L'unità di misura per XResolution e YResolution. La stessa unità è usata sia per XResolution che per YResolution. Se la risoluzione dell'immagine è sconosciuta, viene designata 2 (pollici).

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Il numero di righe per striscia. Questo è il numero di righe nell'immagine di una striscia quando un'immagine è divisa in strisce.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Il numero di componenti per pixel. Poiché questo standard si applica a immagini RGB e YCbCr, il valore impostato per questo tag è 3.

### Saturation {#Saturation}
```
public static final int Saturation
```


Questo tag indica la direzione dell'elaborazione della saturazione applicata dalla fotocamera quando l'immagine è stata scattata.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Questo tag indica il tipo di scena che è stata fotografata. Può anche essere usato per registrare la modalità in cui l'immagine è stata scattata.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indica il tipo di scena. Se un DSC ha registrato l'immagine, il valore di questo tag deve sempre essere impostato a 1, indicando che l'immagine è stata fotografata direttamente.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Indica il tipo di sensore d'immagine sulla fotocamera o sul dispositivo di input.

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Tipo di sensibilità fotografica

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Questo tag indica la direzione dell'elaborazione della nitidezza applicata dalla fotocamera quando l'immagine è stata scattata

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


Il valore della velocità dell'otturatore.

### Software {#Software}
```
public static final int Software
```


Questo tag registra il nome e la versione del software o del firmware della fotocamera o del dispositivo di acquisizione immagine utilizzato per generare l'immagine. Il formato dettagliato non è specificato, ma si consiglia di seguire l'esempio mostrato di seguito. Quando il campo è lasciato vuoto, viene considerato sconosciuto.

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Questo tag registra la tabella di frequenza spaziale della fotocamera o del dispositivo di input e i valori SFR nella direzione della larghezza dell'immagine, dell'altezza dell'immagine e della direzione diagonale, come specificato nella ISO 12233.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Indica la sensibilità spettrale di ciascun canale della fotocamera utilizzata.

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Indica la sensibilità di uscita standard della fotocamera

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Il numero totale di byte in ogni striscia.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Per ogni strip, l'offset in byte di quella strip. Si consiglia di selezionare questo in modo che il numero di byte della strip non superi i 64 Kbyte. Tag Aux.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Questo tag indica la posizione e l'area del soggetto principale nella scena complessiva.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


La distanza dal soggetto, espressa in metri.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Questo tag indica la distanza dal soggetto.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indica la posizione del soggetto principale nella scena. Il valore di questo tag rappresenta il pixel al centro del soggetto principale rispetto al bordo sinistro, prima dell'elaborazione di rotazione secondo il tag Rotation.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


Un tag usato per registrare le frazioni di secondo per il tag DateTime.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


Un tag usato per registrare le frazioni di secondo per il tag DateTimeDigitized.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


Un tag usato per registrare le frazioni di secondo per il tag DateTimeOriginal.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Una funzione di trasferimento per l'immagine, descritta in forma tabellare. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag di informazione sullo spazio colore ColorSpace.

### UserComment {#UserComment}
```
public static final int UserComment
```


Un tag per gli utenti Exif per scrivere parole chiave o commenti sull'immagine oltre a quelli in ImageDescription, e senza le limitazioni di codifica dei caratteri del tag ImageDescription.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Questo tag indica la modalità di bilanciamento del bianco impostata quando l'immagine è stata scattata.

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


La cromaticità del punto bianco dell'immagine. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag di informazione sullo spazio colore ColorSpace.

### XResolution {#XResolution}
```
public static final int XResolution
```


Il numero di pixel per ResolutionUnit nella direzione ImageWidth. Quando la risoluzione dell'immagine è sconosciuta, viene designato 72 [dpi].

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


La posizione dei componenti di crominanza rispetto al componente di luminanza. Questo campo è designato solo per dati compressi JPEG o dati YCbCr non compressi. Il valore predefinito TIFF è 1 (centrato); ma quando Y:Cb:Cr = 4:2:2 è consigliato in questo standard utilizzare 2 (co-sited) per registrare i dati, al fine di migliorare la qualità dell'immagine quando visualizzata su sistemi TV. Quando questo campo non esiste, il lettore deve assumere il valore predefinito TIFF. Nel caso di Y:Cb:Cr = 4:2:0, è consigliato il valore predefinito TIFF (centrato). Se il lettore non ha la capacità di supportare entrambi i tipi di YCbCrPositioning, deve seguire il valore predefinito TIFF indipendentemente dal valore in questo campo. È preferibile che i lettori siano in grado di supportare sia il posizionamento centrato sia quello co-sited.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

### YResolution {#YResolution}
```
public static final int YResolution
```


Il numero di pixel per ResolutionUnit nella direzione ImageLength. Viene designato lo stesso valore di XResolution.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

