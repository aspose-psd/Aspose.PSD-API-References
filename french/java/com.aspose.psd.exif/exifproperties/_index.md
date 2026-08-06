---
title: "ExifProperties"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Liste des balises Exif"
type: docs
weight: 11
url: /fr/java/com.aspose.psd.exif/exifproperties/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Liste des balises Exif
## Champs

| Champ | Description |
| --- | --- |
| [ApertureValue](#ApertureValue) | La valeur d'ouverture de l'objectif. |
| [Artist](#Artist) | Cette balise enregistre le nom du propriétaire de l'appareil, du photographe ou du créateur de l'image. |
| [BitsPerSample](#BitsPerSample) | Le nombre de bits par composant d'image. |
| [BodySerialNumber](#BodySerialNumber) | Contient le numéro de série du boîtier de l'appareil photo |
| [BrightnessValue](#BrightnessValue) | La valeur de luminosité. |
| [CFAPattern](#CFAPattern) | Indique le motif géométrique du réseau de filtres de couleur (CFA) du capteur d'image lorsqu'un capteur couleur à zone à puce unique est utilisé. |
| [CameraOwnerName](#CameraOwnerName) | Contient le nom du propriétaire de l'appareil photo |
| [ColorSpace](#ColorSpace) | L'étiquette d'information de l'espace colorimétrique (ColorSpace) est toujours enregistrée comme le spécificateur d'espace colorimétrique. |
| [ComponentsConfiguration](#ComponentsConfiguration) | La configuration des composants. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Spécifique aux données compressées ; indique le nombre de bits compressés par pixel. |
| [Compression](#Compression) | Le schéma de compression utilisé pour les données d'image. |
| [Contrast](#Contrast) | Cette étiquette indique la direction du traitement du contraste appliqué par l'appareil photo lors de la prise de vue. |
| [Copyright](#Copyright) | Informations sur le droit d'auteur. |
| [CustomRendered](#CustomRendered) | Cette étiquette indique l'utilisation d'un traitement spécial sur les données d'image, comme un rendu orienté vers la sortie. |
| [DateTime](#DateTime) | La date et l'heure de création de l'image. |
| [DateTimeDigitized](#DateTimeDigitized) | La date et l'heure de numérisation. |
| [DateTimeOriginal](#DateTimeOriginal) | La date et l'heure auxquelles les données d'image originales ont été générées. |
| [DeviceSettingDescription](#DeviceSettingDescription) | Cette étiquette indique des informations sur les conditions de prise de vue d'un modèle d'appareil photo particulier. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Cette étiquette indique le rapport de zoom numérique lors de la prise de vue. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExifIfdPointer](#ExifIfdPointer) | Un pointeur vers l'IFD Exif. |
| [ExifVersion](#ExifVersion) | La version Exif. |
| [ExposureBiasValue](#ExposureBiasValue) | La valeur du biais d'exposition. |
| [ExposureIndex](#ExposureIndex) | Indique l'indice d'exposition sélectionné sur l'appareil photo ou le dispositif d'entrée au moment de la capture de l'image. |
| [ExposureMode](#ExposureMode) | Cette étiquette indique le mode d'exposition réglé lors de la prise de vue. |
| [ExposureProgram](#ExposureProgram) | La classe du programme utilisé par l'appareil photo pour régler l'exposition lors de la prise de la photo. |
| [ExposureTime](#ExposureTime) | Temps d'exposition, exprimé en secondes. |
| [FNumber](#FNumber) | Le nombre F. |
| [FileSource](#FileSource) | La source du fichier. |
| [Flash](#Flash) | Indique l'état du flash lors de la prise de vue. |
| [FlashEnergy](#FlashEnergy) | Indique l'énergie du stroboscope au moment de la capture de l'image, mesurée en Beam Candle Power Seconds (BCPS). |
| [FlashpixVersion](#FlashpixVersion) | La version du format Flashpix prise en charge par un fichier FPXR. |
| [FocalLength](#FocalLength) | La longueur focale réelle de l'objectif, en mm. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Cette balise indique la longueur focale équivalente en supposant un appareil photo à film 35 mm, en mm. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indique l'unité de mesure de FocalPlaneXResolution et FocalPlaneYResolution. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indique le nombre de pixels dans la direction de la largeur de l'image (X) par FocalPlaneResolutionUnit sur le plan focal de l'appareil. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indique le nombre de pixels dans la direction de la hauteur de l'image (Y) par FocalPlaneResolutionUnit sur le plan focal de l'appareil. |
| [GPSAltitude](#GPSAltitude) | Indique l'altitude basée sur la référence dans GPSAltitudeRef. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Indique l'altitude utilisée comme altitude de référence. |
| [GPSAreaInformation](#GPSAreaInformation) | Une chaîne de caractères enregistrant le nom de la zone GPS. |
| [GPSDOP](#GPSDOP) | Indique le GPS DOP (degré de précision des données). |
| [GPSDateStamp](#GPSDateStamp) | Une chaîne de caractères enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné). |
| [GPSDestBearing](#GPSDestBearing) | Indique le cap vers le point de destination. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Indique la référence utilisée pour donner le cap vers le point de destination. |
| [GPSDestDistance](#GPSDestDistance) | Indique la distance au point de destination. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Indique l'unité utilisée pour exprimer la distance au point de destination. |
| [GPSDestLatitude](#GPSDestLatitude) | Indique la latitude du point de destination. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Indique si la latitude du point de destination est nord ou sud. |
| [GPSDestLongitude](#GPSDestLongitude) | Indique la longitude du point de destination. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Indique si la longitude du point de destination est est ou ouest. |
| [GPSDifferential](#GPSDifferential) | Indique si une correction différentielle est appliquée au récepteur GPS. |
| [GPSIfdPointer](#GPSIfdPointer) | Le pointeur ifd GPS. |
| [GPSImgDirection](#GPSImgDirection) | Indique la direction de l'image lorsqu'elle a été capturée. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Indique la référence pour donner la direction de l'image lorsqu'elle est capturée. |
| [GPSLatitude](#GPSLatitude) | Indique la latitude. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Indique si la latitude est nord ou sud. |
| [GPSLongitude](#GPSLongitude) | Indique la longitude. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Indique si la longitude est orientée à l'est ou à l'ouest. |
| [GPSMapDatum](#GPSMapDatum) | Indique les données de levé géodésique utilisées par le récepteur GPS. |
| [GPSMeasureMode](#GPSMeasureMode) | Indique le mode de mesure GPS. |
| [GPSProcessingMethod](#GPSProcessingMethod) | Une chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation. |
| [GPSSatellites](#GPSSatellites) | Indique les satellites GPS utilisés pour les mesures. |
| [GPSSpeed](#GPSSpeed) | Indique la vitesse du mouvement du récepteur GPS. |
| [GPSSpeedRef](#GPSSpeedRef) | Indique l'unité utilisée pour exprimer la vitesse du mouvement du récepteur GPS. |
| [GPSStatus](#GPSStatus) | Indique l'état du récepteur GPS lorsque l'image est enregistrée. |
| [GPSTimestamp](#GPSTimestamp) | Indique l'heure en UTC (Temps Universel Coordonné). |
| [GPSTrack](#GPSTrack) | Indique la direction du mouvement du récepteur GPS. |
| [GPSTrackRef](#GPSTrackRef) | Indique la référence pour donner la direction du mouvement du récepteur GPS. |
| [GPSVersionID](#GPSVersionID) | Indique la version de GPSInfoIFD. |
| [GainControl](#GainControl) | Cette balise indique le degré d'ajustement global du gain de l'image. |
| [Gamma](#Gamma) | Valeur gamma |
| [ISOSpeed](#ISOSpeed) | Informations sur la valeur de vitesse ISO telle que définie dans la norme ISO 12232. |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Cette balise indique la valeur de latitude yyy de la vitesse ISO telle que définie dans la norme ISO 12232. |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Cette balise indique la valeur de latitude zzz de la vitesse ISO telle que définie dans la norme ISO 12232. |
| [ImageDescription](#ImageDescription) | Une chaîne de caractères donnant le titre de l'image. |
| [ImageLength](#ImageLength) | Le nombre de lignes de données d'image. |
| [ImageUniqueID](#ImageUniqueID) | L'identifiant unique de l'image. |
| [ImageWidth](#ImageWidth) | Le nombre de colonnes de données d'image, égal au nombre de pixels par ligne. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | Le décalage vers le octet de départ (SOI) des données de vignette compressées JPEG. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | Le nombre d'octets des données de vignette compressées JPEG. |
| [LensMake](#LensMake) | Cette balise enregistre le fabricant de l'objectif. |
| [LensModel](#LensModel) | Cette balise enregistre le nom du modèle de l'objectif et le numéro du modèle. |
| [LensSerialNumber](#LensSerialNumber) | Cette balise enregistre le numéro de série de l'objectif interchangeable |
| [LensSpecification](#LensSpecification) | Cette balise indique la distance focale minimale, la distance focale maximale, le nombre F minimal à la distance focale minimale et le nombre F minimal à la distance focale maximale |
| [LightSource](#LightSource) | Le type de source lumineuse. |
| [Make](#Make) | Le fabricant de l'équipement d'enregistrement. |
| [MakerNote](#MakerNote) | Une balise pour les fabricants de rédacteurs Exif afin d'enregistrer toute information souhaitée. |
| [MaxApertureValue](#MaxApertureValue) | La valeur d'ouverture maximale. |
| [MeteringMode](#MeteringMode) | Le mode de mesure. |
| [Model](#Model) | Le nom du modèle ou le numéro du modèle de l'équipement. |
| [OECF](#OECF) | Indique la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| [Orientation](#Orientation) | L'orientation de l'image vue en termes de lignes et de colonnes. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Indique la vitesse ISO et la latitude ISO de l'appareil photo ou du dispositif d'entrée tel que spécifié dans la norme ISO 12232. |
| [PhotometricInterpretation](#PhotometricInterpretation) | La composition des pixels. |
| [PixelXDimension](#PixelXDimension) | Informations spécifiques aux données compressées. |
| [PixelYDimension](#PixelYDimension) | Informations spécifiques aux données compressées. |
| [PlanarConfiguration](#PlanarConfiguration) | Indique si les composants des pixels sont enregistrés dans un format chunky ou planar. |
| [PrimaryChromaticities](#PrimaryChromaticities) | La chromaticité des trois couleurs primaires de l'image. |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Indique l'indice d'exposition recommandé |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | La valeur du point noir de référence et la valeur du point blanc de référence. |
| [RelatedSoundFile](#RelatedSoundFile) | Le fichier audio associé. |
| [ResolutionUnit](#ResolutionUnit) | L'unité de mesure de la résolution X et de la résolution Y. |
| [RowsPerStrip](#RowsPerStrip) | Le nombre de lignes par bande. |
| [SamplesPerPixel](#SamplesPerPixel) | Le nombre de composants par pixel. |
| [Saturation](#Saturation) | Cette balise indique la direction du traitement de saturation appliqué par l'appareil photo lors de la prise de vue. |
| [SceneCaptureType](#SceneCaptureType) | Cette balise indique le type de scène qui a été photographié. |
| [SceneType](#SceneType) | Indique le type de scène. |
| [SensingMethod](#SensingMethod) | Indique le type de capteur d'image sur l'appareil photo ou le dispositif d'entrée. |
| [SensitivityType](#SensitivityType) | Type de sensibilité photographique |
| [Sharpness](#Sharpness) | Cette balise indique la direction du traitement de netteté appliqué par l'appareil photo lors de la prise de vue de l'image |
| [ShutterSpeedValue](#ShutterSpeedValue) | La valeur de la vitesse d'obturation. |
| [Software](#Software) | Cette balise enregistre le nom et la version du logiciel ou du firmware de l'appareil photo ou du dispositif d'entrée d'image utilisé pour générer l'image. |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Cette balise enregistre le tableau de fréquence spatiale de l'appareil photo ou du dispositif d'entrée ainsi que les valeurs SFR dans les directions de la largeur de l'image, de la hauteur de l'image et de la direction diagonale, comme spécifié dans la norme ISO 12233. |
| [SpectralSensitivity](#SpectralSensitivity) | Indique la sensibilité spectrale de chaque canal de l'appareil photo utilisé. |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Indique la sensibilité de sortie standard de l'appareil photo |
| [StripByteCounts](#StripByteCounts) | Le nombre total d'octets dans chaque bande. |
| [StripOffsets](#StripOffsets) | Pour chaque bande, le décalage en octets de cette bande. |
| [SubjectArea](#SubjectArea) | Cette balise indique l'emplacement et la zone du sujet principal dans la scène globale. |
| [SubjectDistance](#SubjectDistance) | La distance au sujet, donnée en mètres. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Cette balise indique la distance au sujet. |
| [SubjectLocation](#SubjectLocation) | Indique l'emplacement du sujet principal dans la scène. |
| [SubsecTime](#SubsecTime) | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTime. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeDigitized. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeOriginal. |
| [TransferFunction](#TransferFunction) | Une fonction de transfert pour l'image, décrite sous forme tabulaire. |
| [UserComment](#UserComment) | Une balise pour les utilisateurs Exif afin d'écrire des mots‑clés ou des commentaires sur l'image en plus de ceux dans ImageDescription, et sans les limitations de jeu de caractères de la balise ImageDescription. |
| [WhiteBalance](#WhiteBalance) | Cette balise indique le mode de balance des blancs réglé lors de la prise de vue de l'image. |
| [WhitePoint](#WhitePoint) | La chromaticité du point blanc de l'image. |
| [XResolution](#XResolution) | Le nombre de pixels par ResolutionUnit dans la direction ImageWidth. |
| [YCbCrCoefficients](#YCbCrCoefficients) | Les coefficients matriciels pour la transformation des données d'image de RGB vers YCbCr. |
| [YCbCrPositioning](#YCbCrPositioning) | La position des composantes de chrominance par rapport à la composante de luminance. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Le rapport d'échantillonnage des composantes de chrominance par rapport à la composante de luminance. |
| [YResolution](#YResolution) | Le nombre de pixels par ResolutionUnit dans la direction ImageLength. |
## Méthodes

| Méthode | Description |
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


La valeur d'ouverture de l'objectif.

### Artist {#Artist}
```
public static final int Artist
```


Cette balise enregistre le nom du propriétaire de l'appareil photo, du photographe ou du créateur de l'image. Le format détaillé n'est pas spécifié, mais il est recommandé que l'information soit écrite comme dans l'exemple ci‑dessous pour faciliter l'interopérabilité. Lorsque le champ est laissé vide, il est considéré comme inconnu. Ex.) "Propriétaire de l'appareil, John Smith ; Photographe, Michael Brown ; Créateur de l'image, Ken James"

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Le nombre de bits par composant d'image. Dans cette norme, chaque composant de l'image est de 8 bits, donc la valeur pour cette balise est 8.

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Contient le numéro de série du boîtier de l'appareil photo

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


La valeur de luminosité.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indique le motif géométrique du réseau de filtres de couleur (CFA) du capteur d'image lorsqu'un capteur couleur à puce unique est utilisé. Cela ne s'applique pas à toutes les méthodes de détection.

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Contient le nom du propriétaire de l'appareil photo

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


L'étiquette d'information de l'espace colorimétrique (ColorSpace) est toujours enregistrée comme le spécificateur d'espace colorimétrique.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


La configuration des composants.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Spécifique aux données compressées ; indique le nombre de bits compressés par pixel.

### Compression {#Compression}
```
public static final int Compression
```


Le schéma de compression utilisé pour les données d'image. Lorsque l'image principale est compressée en JPEG, cette désignation n'est pas nécessaire et est omise.

### Contrast {#Contrast}
```
public static final int Contrast
```


Cette étiquette indique la direction du traitement du contraste appliqué par l'appareil photo lors de la prise de vue.

### Copyright {#Copyright}
```
public static final int Copyright
```


Informations de droits d'auteur. Dans cette norme, la balise est utilisée pour indiquer les droits d'auteur du photographe et de l'éditeur. Il s'agit de la mention de droit d'auteur de la personne ou de l'organisation revendiquant les droits sur l'image. La déclaration de droit d'auteur d'interopérabilité, incluant la date et les droits, doit être écrite dans ce champ ; par exemple, "Copyright, John Smith, 19xx. All rights reserved.". Dans cette norme, le champ enregistre les droits d'auteur du photographe et de l'éditeur, chacun étant enregistré dans une partie distincte de la déclaration. Lorsqu'il existe une distinction claire entre les droits du photographe et ceux de l'éditeur, ils doivent être écrits dans l'ordre photographe suivi du droit d'auteur de l'éditeur, séparés par NULL (dans ce cas, comme la déclaration se termine également par un NULL, il y a deux codes NULL). Lorsque seul le droit d'auteur du photographe est fourni, il est terminé par un code NULL. Lorsque seul le droit d'auteur de l'éditeur est fourni, la partie du droit d'auteur du photographe consiste en un espace suivi d'un code NULL de terminaison, puis le droit d'auteur de l'éditeur est donné. Lorsque le champ est laissé vide, il est considéré comme inconnu.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Cette balise indique l'utilisation d'un traitement spécial sur les données d'image, tel qu'un rendu orienté vers la sortie. Lorsque le traitement spécial est effectué, le lecteur doit désactiver ou minimiser tout traitement supplémentaire.

### DateTime {#DateTime}
```
public static final int DateTime
```


La date et l'heure de création de l'image. Dans la norme Exif, il s'agit de la date et de l'heure de la modification du fichier.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


La date et l'heure de numérisation.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


La date et l'heure auxquelles les données d'image originales ont été générées.

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Cette balise indique les informations sur les conditions de prise de vue d'un modèle d'appareil photo particulier. La balise est utilisée uniquement pour indiquer les conditions de prise de vue dans le lecteur.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Cette balise indique le rapport de zoom numérique lors de la prise de la photo. Si le numérateur de la valeur enregistrée est 0, cela indique que le zoom numérique n'a pas été utilisé.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Un pointeur vers l'IFD Exif. Interopérabilité, l'IFD Exif a la même structure que celle de l'IFD spécifié dans TIFF. Cependant, il ne contient généralement pas de données d'image comme dans le cas de TIFF.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


La version Exif.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


La valeur du biais d'exposition.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Indique l'indice d'exposition sélectionné sur l'appareil photo ou le dispositif d'entrée au moment de la capture de l'image.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Cette balise indique le mode d'exposition réglé lors de la prise de la photo. En mode auto-bracketing, l'appareil photo prend une série de cadres de la même scène avec des réglages d'exposition différents.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


La classe du programme utilisé par l'appareil photo pour régler l'exposition lors de la prise de la photo.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Temps d'exposition, exprimé en secondes.

### FNumber {#FNumber}
```
public static final int FNumber
```


Le nombre F.

### FileSource {#FileSource}
```
public static final int FileSource
```


La source du fichier.

### Flash {#Flash}
```
public static final int Flash
```


Indique l'état du flash lors de la prise de vue.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Indique l'énergie du stroboscope au moment de la capture de l'image, mesurée en Beam Candle Power Seconds (BCPS).

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


La version du format Flashpix prise en charge par un fichier FPXR.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


La longueur focale réelle de l'objectif, en mm.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Cette balise indique la longueur focale équivalente en supposant un appareil photo à film 35 mm, en mm. Une valeur de 0 signifie que la longueur focale est inconnue. Notez que cette balise diffère de la balise FocalLength.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indique l'unité de mesure pour FocalPlaneXResolution et FocalPlaneYResolution. Cette valeur est identique à ResolutionUnit.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Indique le nombre de pixels dans la direction de la largeur de l'image (X) par FocalPlaneResolutionUnit sur le plan focal de l'appareil.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Indique le nombre de pixels dans la direction de la hauteur de l'image (Y) par FocalPlaneResolutionUnit sur le plan focal de l'appareil.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Indique l'altitude basée sur la référence dans GPSAltitudeRef. L'altitude est exprimée comme une valeur RATIONAL. L'unité de référence est le mètre.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Indique l'altitude utilisée comme altitude de référence. Si la référence est le niveau de la mer et que l'altitude est au-dessus du niveau de la mer, la valeur 0 est donnée. Si l'altitude est en dessous du niveau de la mer, la valeur 1 est donnée et l'altitude est indiquée comme une valeur absolue dans la balise GPSAltitude.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


Une chaîne de caractères enregistrant le nom de la zone GPS. Le premier octet indique le code de caractère utilisé, suivi du nom de la zone GPS.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Indique le GPS DOP (degré de précision des données). Une valeur HDOP est enregistrée lors d'une mesure bidimensionnelle, et PDOP lors d'une mesure tridimensionnelle.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


Une chaîne de caractères enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné). Le format est AAAA:MM:JJ.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Indique l'azimut vers le point de destination. L'intervalle des valeurs est de 0.00 à 359.99.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Indique la référence utilisée pour donner l'azimut vers le point de destination. 'T' désigne la direction vraie et 'M' la direction magnétique.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Indique la distance au point de destination.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Indique l'unité utilisée pour exprimer la distance au point de destination. 'K', 'M' et 'N' représentent respectivement les kilomètres, les miles et les nœuds.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Indique la latitude du point de destination. La latitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, les minutes et les secondes. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque les degrés et les minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait dd/1,mmmm/100,0/1.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Indique si la latitude du point de destination est nord ou sud. La valeur ASCII 'N' indique la latitude nord, et 'S' la latitude sud.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Indique la longitude du point de destination. La longitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, les minutes et les secondes. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque les degrés et les minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait ddd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Indique si la longitude du point de destination est orientée à l'est ou à l'ouest. Le caractère ASCII 'E' indique l'est, et 'W' l'ouest.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Indique si une correction différentielle est appliquée au récepteur GPS.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


Le pointeur ifd GPS.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Indique la direction de l'image lors de sa capture. L'intervalle des valeurs est de 0.00 à 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Indique la référence pour donner la direction de l'image lors de sa capture. 'T' désigne la direction vraie et 'M' la direction magnétique.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indique la latitude. La latitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, les minutes et les secondes. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque les degrés et les minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait dd/1,mmmm/100,0/1.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Indique si la latitude est nord ou sud.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Indique la longitude. La longitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, les minutes et les secondes. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque les degrés et les minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait ddd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Indique si la longitude est orientée à l'est ou à l'ouest.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Indique les données de levé géodésique utilisées par le récepteur GPS.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Indique le mode de mesure GPS. - 2D ou 3D.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


Une chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation. Le premier octet indique le code de caractère utilisé, suivi du nom de la méthode.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Indique les satellites GPS utilisés pour les mesures. Cette balise peut être utilisée pour décrire le nombre de satellites, leur numéro d'ID, l'angle d'élévation, l'azimut, le SNR et d'autres informations en notation ASCII. Le format n'est pas spécifié. Si le récepteur GPS est incapable de prendre des mesures, la valeur de la balise doit être définie sur NULL.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Indique la vitesse du mouvement du récepteur GPS.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Indique l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. 'K', 'M' et 'N' représentent respectivement les kilomètres par heure, les miles par heure et les nœuds.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Indique l'état du récepteur GPS lorsque l'image est enregistrée.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Indique l'heure en UTC (Temps Universel Coordonné). Le TimeStamp est exprimé sous forme de trois valeurs RATIONAL donnant l'heure, la minute et la seconde.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Indique la direction du mouvement du récepteur GPS. L'intervalle des valeurs est de 0.00 à 359.99.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Indique la référence pour donner la direction du mouvement du récepteur GPS. 'T' désigne la direction vraie et 'M' la direction magnétique.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Indique la version de GPSInfoIFD.

### GainControl {#GainControl}
```
public static final int GainControl
```


Cette balise indique le degré d'ajustement global du gain de l'image.

### Gamma {#Gamma}
```
public static final int Gamma
```


Valeur gamma

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Informations sur la valeur de vitesse ISO telle que définie dans la norme ISO 12232.

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Cette balise indique la valeur de latitude yyy de la vitesse ISO telle que définie dans la norme ISO 12232.

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Cette balise indique la valeur de latitude zzz de la vitesse ISO telle que définie dans la norme ISO 12232.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Une chaîne de caractères donnant le titre de l'image. Cela peut être un commentaire tel que "1988 company picnic" ou similaire.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Le nombre de lignes de données d'image.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


L'identifiant unique de l'image.

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Le nombre de colonnes de données d'image, égal au nombre de pixels par ligne.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


Le décalage vers le premier octet (SOI) des données de vignette JPEG compressées. Ceci n'est pas utilisé pour les données JPEG de l'image principale.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


Le nombre d'octets des données de vignette JPEG compressées. Ceci n'est pas utilisé pour les données JPEG de l'image principale. Les vignettes JPEG ne sont pas divisées mais sont enregistrées comme un flux JPEG continu du SOI à l'EOI. Les marqueurs Appn et COM ne doivent pas être enregistrés. Les vignettes compressées doivent être enregistrées dans un maximum de 64 Koctets, y compris toutes les autres données à enregistrer dans APP1.

### LensMake {#LensMake}
```
public static final int LensMake
```


Cette balise enregistre le fabricant de l'objectif.

### LensModel {#LensModel}
```
public static final int LensModel
```


Cette balise enregistre le nom du modèle de l'objectif et le numéro du modèle.

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Cette balise enregistre le numéro de série de l'objectif interchangeable

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Cette balise indique la distance focale minimale, la distance focale maximale, le nombre F minimal à la distance focale minimale et le nombre F minimal à la distance focale maximale

### LightSource {#LightSource}
```
public static final int LightSource
```


Le type de source lumineuse.

### Make {#Make}
```
public static final int Make
```


Le fabricant de l'équipement d'enregistrement. Il s'agit du fabricant du DSC, du scanner, du numériseur vidéo ou de tout autre équipement ayant généré l'image. Lorsque le champ est laissé vide, il est considéré comme inconnu.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Une balise pour les fabricants d'éditeurs Exif afin d'enregistrer toute information souhaitée. Le contenu dépend du fabricant, mais cette balise ne doit pas être utilisée à d'autres fins que celle prévue.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


La valeur d'ouverture maximale.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


Le mode de mesure.

### Model {#Model}
```
public static final int Model
```


Le nom ou le numéro de modèle de l'équipement. Il s'agit du nom ou du numéro de modèle du DSC, du scanner, du numériseur vidéo ou de tout autre équipement ayant généré l'image. Lorsque le champ est laissé vide, il est considéré comme inconnu.

### OECF {#OECF}
```
public static final int OECF
```


Indique la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524.

### Orientation {#Orientation}
```
public static final int Orientation
```


L'orientation de l'image vue en termes de lignes et de colonnes.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Indique la vitesse ISO et la latitude ISO de l'appareil photo ou du dispositif d'entrée tel que spécifié dans la norme ISO 12232.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


La composition des pixels.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la largeur valide de l'image significative doit être enregistrée dans cette balise, qu'il y ait ou non des données de remplissage ou un marqueur de redémarrage.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la hauteur valide de l'image significative doit être enregistrée dans cette balise.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Indique si les composants des pixels sont enregistrés au format chunky ou planar. Si ce champ n'existe pas, la valeur par défaut TIFF de 1 (chunky) est supposée.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


La chromaticité des trois couleurs primaires de l'image. Normalement cette balise n'est pas nécessaire, car l'espace couleur est spécifié dans la balise d'information d'espace couleur ColorSpace.

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Indique l'indice d'exposition recommandé

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


La valeur du point noir de référence et la valeur du point blanc de référence. Aucun défaut n'est fourni dans le TIFF, mais les valeurs ci-dessous sont présentées comme défauts ici. L'espace couleur est déclaré dans une balise d'information d'espace couleur, la valeur par défaut étant celle qui offre les caractéristiques d'image optimales d'interopérabilité dans ces conditions.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


Le fichier audio associé.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


L'unité de mesure de XResolution et YResolution. La même unité est utilisée pour XResolution et YResolution. Si la résolution de l'image est inconnue, 2 (pouces) est désignée.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Le nombre de lignes par bande. Il s'agit du nombre de lignes de l'image dans une bande lorsqu'une image est divisée en bandes.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Le nombre de composants par pixel. Comme cette norme s'applique aux images RGB et YCbCr, la valeur définie pour cette balise est 3.

### Saturation {#Saturation}
```
public static final int Saturation
```


Cette balise indique la direction du traitement de saturation appliqué par l'appareil photo lors de la prise de vue.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Cette balise indique le type de scène qui a été photographié. Elle peut également être utilisée pour enregistrer le mode dans lequel l'image a été prise.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indique le type de scène. Si un DSC a enregistré l'image, la valeur de cette balise doit toujours être réglée sur 1, indiquant que l'image a été photographiée directement.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Indique le type de capteur d'image sur l'appareil photo ou le dispositif d'entrée.

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Type de sensibilité photographique

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Cette balise indique la direction du traitement de netteté appliqué par l'appareil photo lors de la prise de vue de l'image

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


La valeur de la vitesse d'obturation.

### Software {#Software}
```
public static final int Software
```


Cette balise enregistre le nom et la version du logiciel ou du firmware de l'appareil photo ou du dispositif d'entrée d'image utilisé pour générer l'image. Le format détaillé n'est pas spécifié, mais il est recommandé de suivre l'exemple ci-dessous. Lorsque le champ est laissé vide, il est considéré comme inconnu.

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Cette balise enregistre le tableau de fréquence spatiale de l'appareil photo ou du dispositif d'entrée ainsi que les valeurs SFR dans les directions de la largeur de l'image, de la hauteur de l'image et de la direction diagonale, comme spécifié dans la norme ISO 12233.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Indique la sensibilité spectrale de chaque canal de l'appareil photo utilisé.

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Indique la sensibilité de sortie standard de l'appareil photo

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Le nombre total d'octets dans chaque bande.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Pour chaque bande, le décalage en octets de cette bande. Il est recommandé de choisir cela de façon que le nombre d'octets par bande ne dépasse pas 64 Koctets. Balise auxiliaire.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Cette balise indique l'emplacement et la zone du sujet principal dans la scène globale.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


La distance au sujet, donnée en mètres.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Cette balise indique la distance au sujet.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indique l'emplacement du sujet principal dans la scène. La valeur de cette balise représente le pixel au centre du sujet principal par rapport au bord gauche, avant le traitement de rotation selon la balise Rotation.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTime.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeDigitized.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeOriginal.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Une fonction de transfert pour l'image, décrite sous forme tabulaire. Normalement cette balise n'est pas nécessaire, car l'espace couleur est spécifié dans la balise d'information d'espace couleur ColorSpace.

### UserComment {#UserComment}
```
public static final int UserComment
```


Une balise pour les utilisateurs Exif afin d'écrire des mots‑clés ou des commentaires sur l'image en plus de ceux dans ImageDescription, et sans les limitations de jeu de caractères de la balise ImageDescription.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Cette balise indique le mode de balance des blancs réglé lors de la prise de vue de l'image.

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


La chromaticité du point blanc de l'image. Normalement cette balise n'est pas nécessaire, car l'espace couleur est spécifié dans la balise d'information d'espace couleur ColorSpace.

### XResolution {#XResolution}
```
public static final int XResolution
```


Le nombre de pixels par ResolutionUnit dans la direction de la largeur de l'image. Lorsque la résolution de l'image est inconnue, 72 [dpi] est désigné.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


Les coefficients matriciels pour la transformation des données d'image de RGB vers YCbCr.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


La position des composants de chrominance par rapport au composant de luminance. Ce champ est destiné uniquement aux données compressées JPEG ou aux données YCbCr non compressées. La valeur par défaut TIFF est 1 (centré) ; mais lorsque Y:Cb:Cr = 4:2:2, il est recommandé dans cette norme d’utiliser 2 (co‑situé) pour enregistrer les données, afin d’améliorer la qualité de l’image lorsqu’elle est affichée sur des systèmes TV. Lorsque ce champ n’existe pas, le lecteur doit supposer la valeur par défaut TIFF. Dans le cas où Y:Cb:Cr = 4:2:0, la valeur par défaut TIFF (centré) est recommandée. Si le lecteur n’a pas la capacité de prendre en charge les deux types de YCbCrPositioning, il doit suivre la valeur par défaut TIFF quel que soit la valeur de ce champ. Il est préférable que les lecteurs puissent prendre en charge à la fois le positionnement centré et co‑situé.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Le rapport d'échantillonnage des composantes de chrominance par rapport à la composante de luminance.

### YResolution {#YResolution}
```
public static final int YResolution
```


Le nombre de pixels par ResolutionUnit dans la direction ImageLength. La même valeur que XResolution est désignée.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
booléen
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
booléen
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
booléen
### isDefined(Class<?> arg0, String arg1) {#isDefined-java.lang.Class----java.lang.String-}
```
public static boolean isDefined(Class<?> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
booléen
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
booléen
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

