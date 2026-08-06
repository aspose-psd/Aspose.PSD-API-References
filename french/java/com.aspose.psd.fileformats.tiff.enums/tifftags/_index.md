---
title: "TiffTags"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "L'énumération des tags TIFF."
type: docs
weight: 25
url: /fr/java/com.aspose.psd.fileformats.tiff.enums/tifftags/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffTags extends System.Enum
```

L'énumération des tags TIFF.
## Champs

| Champ | Description |
| --- | --- |
| [Artist](#Artist) | Créateur de l'image. |
| [BadFaxLines](#BadFaxLines) | Lignes avec un nombre de pixels incorrect. |
| [BitsPerSample](#BitsPerSample) | Bits par canal (échantillon). |
| [CellLength](#CellLength) | [obsolète depuis TIFF rev. |
| [CellWidth](#CellWidth) | [obsolète depuis TIFF rev. |
| [CleanFaxData](#CleanFaxData) | Informations de ligne régénérées. |
| [ClipPath](#ClipPath) | ClipPath. |
| [ColorMap](#ColorMap) | Carte RGB pour image à palette. |
| [ColorResponseUnit](#ColorResponseUnit) | [obsolète depuis TIFF rev. |
| [Compression](#Compression) | Technique de compression de données. |
| [ConsecutiveBadFaxLines](#ConsecutiveBadFaxLines) | Maximum de lignes défectueuses consécutives. |
| [Copyright](#Copyright) | Chaîne de droit d'auteur. |
| [DateTime](#DateTime) | Date et heure de création. |
| [DocumentName](#DocumentName) | Nom du document qui contient l'image. |
| [DotRange](#DotRange) | Codes de points à 0 % et 100 %. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExifIfdPointer](#ExifIfdPointer) | Un pointeur vers l'IFD Exif. |
| [ExtraSamples](#ExtraSamples) | Informations sur les échantillons supplémentaires. |
| [FillOrder](#FillOrder) | Ordre des données au sein d'un octet. |
| [FreeByteCounts](#FreeByteCounts) | [obsolète depuis TIFF rev. |
| [FreeOffsets](#FreeOffsets) | [obsolète depuis TIFF rev. |
| [GrayResponseCurve](#GrayResponseCurve) | [obsolète depuis TIFF rev. |
| [GrayResponseUnit](#GrayResponseUnit) | [obsolète depuis TIFF rev. |
| [HalftoneHints](#HalftoneHints) | Informations de surbrillance + ombre. |
| [HostComputer](#HostComputer) | Machine où créé. |
| [IccProfile](#IccProfile) | Le profil de périphérique ICC intégré |
| [ImageDescription](#ImageDescription) | Informations sur l'image. |
| [ImageLength](#ImageLength) | Hauteur de l'image en pixels. |
| [ImageWidth](#ImageWidth) | Largeur de l'image en pixels. |
| [Indexed](#Indexed) | Indexé. |
| [InkNames](#InkNames) | Noms ASCII des encres. |
| [InkSet](#InkSet) | Encres dans l'image séparée. |
|  | [JpegACtables](#JpegACtables) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Décalages des coefficients AC. |
|  | [JpegDCtables](#JpegDCtables) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Décalages de la table DCT. |
|  | [JpegInerchangeFormat](#JpegInerchangeFormat) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Pointeur vers le marqueur SOI. |
|  | [JpegInterchangeFormatLength](#JpegInterchangeFormatLength) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Longueur du flux JFIF |
|  | [JpegLosslessPredictors](#JpegLosslessPredictors) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Prédicteur de procédé sans perte. |
|  | [JpegPointTransform](#JpegPointTransform) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Transformation de point sans perte. |
|  | [JpegProc](#JpegProc) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Algorithme de traitement JPEG. |
|  | [JpegQTables](#JpegQTables) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Décalages de la matrice Q. |
|  | [JpegRestartInterval](#JpegRestartInterval) | [obsolète par Technical Note \#2 qui spécifie un schéma JPEG-in-TIFF révisé] |

Longueur de l'intervalle de redémarrage. |
| [JpegTables](#JpegTables) | Flux de table JPEG. |
| [Make](#Make) | Nom du fabricant du scanner. |
| [MaxSampleValue](#MaxSampleValue) | [obsolète depuis TIFF rev. |
| [MinSampleValue](#MinSampleValue) | [obsolète depuis TIFF rev. |
| [Model](#Model) | Nom/numéro du modèle du scanner. |
| [NumberOfInks](#NumberOfInks) | Nombre d'encres. |
| [OpiImageid](#OpiImageid) | ID d'image OPI. |
| [OpiProxy](#OpiProxy) | Proxy OPI. |
| [Orientation](#Orientation) | [obsolète depuis TIFF rev. |
| [OsubfileType](#OsubfileType) | [obsolète depuis TIFF rev. |
| [PageName](#PageName) | Nom de la page dont provient l'image. |
| [PageNumber](#PageNumber) | Numéros de pages du multi-page. |
| [Photometric](#Photometric) | Interprétation photométrique. |
| [PhotoshopResources](#PhotoshopResources) | Ressources d'image Photoshop. |
| [PlanarConfig](#PlanarConfig) | Organisation du stockage. |
| [Predictor](#Predictor) | Schéma de prédiction avec LZW. |
| [PrimaryChromaticities](#PrimaryChromaticities) | Chromaticités primaires. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Informations de colorimétrie. |
| [Refpts](#Refpts) | Points de référence de l'image. |
| [ResolutionUnit](#ResolutionUnit) | Unités de résolution. |
| [RowsPerStrip](#RowsPerStrip) | Lignes par bande de données. |
| [SampleFormat](#SampleFormat) | Format d'échantillon de données. |
| [SamplesPerPixel](#SamplesPerPixel) | Échantillons par pixel. |
| [SmaxSampleValue](#SmaxSampleValue) | Valeur maximale d'échantillon variable. |
| [SminSampleValue](#SminSampleValue) | Valeur minimale d'échantillon variable. |
| [Software](#Software) | Nom et version. |
| [StripByteCounts](#StripByteCounts) | Décomptes d'octets pour les bandes. |
| [StripOffsets](#StripOffsets) | Décalages vers les bandes de données. |
| [SubFileType](#SubFileType) | Descripteur de données de sous-fichier. |
| [SubIfd](#SubIfd) | Descripteurs de sous-image. |
| [T4Options](#T4Options) | TIFF 6.0 alias de nom propre pour GROUP3OPTIONS. |
| [T6Options](#T6Options) | Options pour le codage fax CCITT Group 4. |
| [TargetPrinter](#TargetPrinter) | Cible de séparation. |
| [Thresholding](#Thresholding) | [obsolète depuis TIFF rev. |
| [TileByteCounts](#TileByteCounts) | Comptes d'octets pour les tuiles. |
| [TileLength](#TileLength) | Hauteur de la tuile en pixels. |
| [TileOffsets](#TileOffsets) | Décalages vers les tuiles de données. |
| [TileWidth](#TileWidth) | Largeur de la tuile en pixels. |
| [TransferFunction](#TransferFunction) | Informations de colorimétrie. |
| [TransferRange](#TransferRange) | Variable TransferRange |
| [WhitePoint](#WhitePoint) | Point blanc de l'image. |
| [XPAuthor](#XPAuthor) | Auteur de l'image, utilisé par Windows Explorer. |
| [XPComment](#XPComment) | Commentaire sur l'image, utilisé par Windows Explorer. |
| [XPKeywords](#XPKeywords) | Mots-clés de l'image, utilisés par Windows Explorer. |
| [XPSubject](#XPSubject) | Sujet de l'image, utilisé par Windows Explorer. |
| [XPTitle](#XPTitle) | Informations sur l'image, utilisées par Windows Explorer. |
| [Xclippathunits](#Xclippathunits) | XClipPathUnits. |
| [XmlPacket](#XmlPacket) | Paquet XML. |
| [Xposition](#Xposition) | Décalage de page X de l'image côté gauche. |
| [Xresolution](#Xresolution) | Pixels/résolution en x. |
| [YcbcrCoefficients](#YcbcrCoefficients) | Transformation RGB -> YCbCr. |
| [YcbcrPositioning](#YcbcrPositioning) | Positionnement du sous-échantillonnage. |
| [YcbcrSubSampling](#YcbcrSubSampling) | Facteurs de sous-échantillonnage YCbCr. |
| [Yclippathunits](#Yclippathunits) | YClipPathUnits. |
| [Yposition](#Yposition) | Décalage de page Y de l'image côté gauche. |
| [Yresolution](#Yresolution) | Pixels/résolution en y. |
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
### Artist {#Artist}
```
public static final int Artist
```


Créateur de l'image.

### BadFaxLines {#BadFaxLines}
```
public static final int BadFaxLines
```


Lignes avec un nombre de pixels incorrect.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Bits par canal (échantillon).

### CellLength {#CellLength}
```
public static final int CellLength
```


[obsoleted by TIFF rev. 5.0]

Hauteur de la matrice de tramage.

### CellWidth {#CellWidth}
```
public static final int CellWidth
```


[obsoleted by TIFF rev. 5.0]

Largeur de la matrice de tramage.

### CleanFaxData {#CleanFaxData}
```
public static final int CleanFaxData
```


Informations de ligne régénérées.

### ClipPath {#ClipPath}
```
public static final int ClipPath
```


ClipPath. Introduit après la révision 6.0 du TIFF par la note technique 2 d'Adobe TIFF.

### ColorMap {#ColorMap}
```
public static final int ColorMap
```


Carte RGB pour image à palette.

### ColorResponseUnit {#ColorResponseUnit}
```
public static final int ColorResponseUnit
```


[obsoleted by TIFF rev. 6.0]

Précision de la courbe de couleur.

### Compression {#Compression}
```
public static final int Compression
```


Technique de compression de données.

### ConsecutiveBadFaxLines {#ConsecutiveBadFaxLines}
```
public static final int ConsecutiveBadFaxLines
```


Maximum de lignes défectueuses consécutives.

### Copyright {#Copyright}
```
public static final int Copyright
```


Chaîne de droits d'auteur. Cette balise est répertoriée dans le TIFF révision 6.0 avec une propriété inconnue.

### DateTime {#DateTime}
```
public static final int DateTime
```


Date et heure de création.

### DocumentName {#DocumentName}
```
public static final int DocumentName
```


Nom du document qui contient l'image.

### DotRange {#DotRange}
```
public static final int DotRange
```


Codes de points à 0 % et 100 %.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Un pointeur vers l'IFD Exif.

### ExtraSamples {#ExtraSamples}
```
public static final int ExtraSamples
```


Informations sur les échantillons supplémentaires.

### FillOrder {#FillOrder}
```
public static final int FillOrder
```


Ordre des données au sein d'un octet.

### FreeByteCounts {#FreeByteCounts}
```
public static final int FreeByteCounts
```


[obsoleted by TIFF rev. 5.0]

Tailles des blocs libres.

### FreeOffsets {#FreeOffsets}
```
public static final int FreeOffsets
```


[obsoleted by TIFF rev. 5.0]

Décalage d'octet vers le bloc libre.

### GrayResponseCurve {#GrayResponseCurve}
```
public static final int GrayResponseCurve
```


[obsoleted by TIFF rev. 6.0]

Courbe de réponse en niveaux de gris.

### GrayResponseUnit {#GrayResponseUnit}
```
public static final int GrayResponseUnit
```


[obsoleted by TIFF rev. 6.0]

Précision de la courbe en niveaux de gris.

### HalftoneHints {#HalftoneHints}
```
public static final int HalftoneHints
```


Informations de surbrillance + ombre.

### HostComputer {#HostComputer}
```
public static final int HostComputer
```


Machine où créé.

### IccProfile {#IccProfile}
```
public static final int IccProfile
```


Le profil de périphérique ICC intégré

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Informations sur l'image.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Hauteur de l'image en pixels.

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Largeur de l'image en pixels.

### Indexed {#Indexed}
```
public static final int Indexed
```


Indexé. Introduit après la révision 6.0 du TIFF par la note technique 3 d'Adobe TIFF.

### InkNames {#InkNames}
```
public static final int InkNames
```


Noms ASCII des encres.

### InkSet {#InkSet}
```
public static final int InkSet
```


Encres dans l'image séparée.

### JpegACtables {#JpegACtables}
```
public static final int JpegACtables
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Décalages des coefficients AC.

### JpegDCtables {#JpegDCtables}
```
public static final int JpegDCtables
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Décalages de la table DCT.

### JpegInerchangeFormat {#JpegInerchangeFormat}
```
public static final int JpegInerchangeFormat
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Pointeur vers le marqueur SOI.

### JpegInterchangeFormatLength {#JpegInterchangeFormatLength}
```
public static final int JpegInterchangeFormatLength
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Longueur du flux JFIF

### JpegLosslessPredictors {#JpegLosslessPredictors}
```
public static final int JpegLosslessPredictors
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Prédicteur de procédure sans perte.

### JpegPointTransform {#JpegPointTransform}
```
public static final int JpegPointTransform
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Transformation de point sans perte.

### JpegProc {#JpegProc}
```
public static final int JpegProc
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Algorithme de traitement JPEG.

### JpegQTables {#JpegQTables}
```
public static final int JpegQTables
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Décalages de la matrice Q.

### JpegRestartInterval {#JpegRestartInterval}
```
public static final int JpegRestartInterval
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme]

Longueur de l'intervalle de redémarrage.

### JpegTables {#JpegTables}
```
public static final int JpegTables
```


Flux de table JPEG. Introduit après la révision 6.0 du TIFF.

### Make {#Make}
```
public static final int Make
```


Nom du fabricant du scanner.

### MaxSampleValue {#MaxSampleValue}
```
public static final int MaxSampleValue
```


[obsoleted by TIFF rev. 5.0]

Valeur d'échantillon maximale.

### MinSampleValue {#MinSampleValue}
```
public static final int MinSampleValue
```


[obsoleted by TIFF rev. 5.0]

Valeur d'échantillon minimale.

### Model {#Model}
```
public static final int Model
```


Nom/numéro du modèle du scanner.

### NumberOfInks {#NumberOfInks}
```
public static final int NumberOfInks
```


Nombre d'encres.

### OpiImageid {#OpiImageid}
```
public static final int OpiImageid
```


OPI ImageID. Introduit après la révision 6.0 du TIFF par la note technique d'Adobe TIFF.

### OpiProxy {#OpiProxy}
```
public static final int OpiProxy
```


OPI Proxy. Introduit après la révision 6.0 du TIFF par la note technique d'Adobe TIFF.

### Orientation {#Orientation}
```
public static final int Orientation
```


[obsoleted by TIFF rev. 5.0]

Orientation de l'image.

### OsubfileType {#OsubfileType}
```
public static final int OsubfileType
```


[obsoleted by TIFF rev. 5.0]

Type de données dans le sous-fichier.

### PageName {#PageName}
```
public static final int PageName
```


Nom de la page dont provient l'image.

### PageNumber {#PageNumber}
```
public static final int PageNumber
```


Numéros de pages du multi-page.

### Photometric {#Photometric}
```
public static final int Photometric
```


Interprétation photométrique.

### PhotoshopResources {#PhotoshopResources}
```
public static final int PhotoshopResources
```


Ressources d'image Photoshop.

### PlanarConfig {#PlanarConfig}
```
public static final int PlanarConfig
```


Organisation du stockage.

### Predictor {#Predictor}
```
public static final int Predictor
```


Schéma de prédiction avec LZW.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


Chromaticités primaires.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


Informations de colorimétrie.

### Refpts {#Refpts}
```
public static final int Refpts
```


Points de référence d'image. Balise privée enregistrée auprès d'Island Graphics.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


Unités de résolution.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Lignes par bande de données.

### SampleFormat {#SampleFormat}
```
public static final int SampleFormat
```


Format d'échantillon de données.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Échantillons par pixel.

### SmaxSampleValue {#SmaxSampleValue}
```
public static final int SmaxSampleValue
```


Valeur maximale d'échantillon variable.

### SminSampleValue {#SminSampleValue}
```
public static final int SminSampleValue
```


Valeur minimale d'échantillon variable.

### Software {#Software}
```
public static final int Software
```


Nom et version.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Décomptes d'octets pour les bandes.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Décalages vers les bandes de données.

### SubFileType {#SubFileType}
```
public static final int SubFileType
```


Descripteur de données de sous-fichier.

### SubIfd {#SubIfd}
```
public static final int SubIfd
```


Descripteurs de sous-image.

### T4Options {#T4Options}
```
public static final int T4Options
```


TIFF 6.0 alias de nom propre pour GROUP3OPTIONS. Options pour l'encodage fax CCITT Group 3. 32 bits de drapeaux.

### T6Options {#T6Options}
```
public static final int T6Options
```


Options pour l'encodage fax CCITT Group 4. 32 bits de drapeaux. TIFF 6.0 alias de nom propre pour GROUP4OPTIONS.

### TargetPrinter {#TargetPrinter}
```
public static final int TargetPrinter
```


Cible de séparation.

### Thresholding {#Thresholding}
```
public static final int Thresholding
```


[obsoleted by TIFF rev. 5.0]

Seuillage utilisé sur les données.

### TileByteCounts {#TileByteCounts}
```
public static final int TileByteCounts
```


Comptes d'octets pour les tuiles.

### TileLength {#TileLength}
```
public static final int TileLength
```


Hauteur de la tuile en pixels.

### TileOffsets {#TileOffsets}
```
public static final int TileOffsets
```


Décalages vers les tuiles de données.

### TileWidth {#TileWidth}
```
public static final int TileWidth
```


Largeur de la tuile en pixels.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Informations de colorimétrie.

### TransferRange {#TransferRange}
```
public static final int TransferRange
```


Variable TransferRange

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


Point blanc de l'image.

### XPAuthor {#XPAuthor}
```
public static final int XPAuthor
```


Auteur de l'image, utilisé par Windows Explorer. Le  TiffTags.XPAuthor  est ignoré par Windows Explorer si la balise [Artist](../../com.aspose.psd.fileformats.tiff.enums/tifftags\#Artist) existe.

### XPComment {#XPComment}
```
public static final int XPComment
```


Commentaire sur l'image, utilisé par Windows Explorer.

### XPKeywords {#XPKeywords}
```
public static final int XPKeywords
```


Mots-clés de l'image, utilisés par Windows Explorer.

### XPSubject {#XPSubject}
```
public static final int XPSubject
```


Sujet de l'image, utilisé par Windows Explorer.

### XPTitle {#XPTitle}
```
public static final int XPTitle
```


Informations sur l'image, utilisées par Windows Explorer. Le  TiffTags.XPTitle  est ignoré par Windows Explorer si la balise [ImageDescription](../../com.aspose.psd.fileformats.tiff.enums/tifftags\#ImageDescription) existe.

### Xclippathunits {#Xclippathunits}
```
public static final int Xclippathunits
```


XClipPathUnits. Introduit après la révision 6.0 de TIFF par la note technique Adobe TIFF 2.

### XmlPacket {#XmlPacket}
```
public static final int XmlPacket
```


Paquet XML. Introduit après la révision 6.0 de TIFF par la spécification Adobe XMP, janvier 2004.

### Xposition {#Xposition}
```
public static final int Xposition
```


Décalage de page X de l'image côté gauche.

### Xresolution {#Xresolution}
```
public static final int Xresolution
```


Pixels/résolution en x.

### YcbcrCoefficients {#YcbcrCoefficients}
```
public static final int YcbcrCoefficients
```


Transformation RGB -> YCbCr.

### YcbcrPositioning {#YcbcrPositioning}
```
public static final int YcbcrPositioning
```


Positionnement du sous-échantillonnage.

### YcbcrSubSampling {#YcbcrSubSampling}
```
public static final int YcbcrSubSampling
```


Facteurs de sous-échantillonnage YCbCr.

### Yclippathunits {#Yclippathunits}
```
public static final int Yclippathunits
```


YClipPathUnits. Introduit après la révision 6.0 de TIFF par la note technique Adobe TIFF 2.

### Yposition {#Yposition}
```
public static final int Yposition
```


Décalage de page Y de l'image côté gauche.

### Yresolution {#Yresolution}
```
public static final int Yresolution
```


Pixels/résolution en y.

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

