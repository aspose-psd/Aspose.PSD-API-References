---
title: "Enum TiffTags"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags enum. L'énumération des balises tiff"
type: docs
weight: 4640
url: /fr/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

L'énumération des balises TIFF.

```csharp
public enum TiffTags
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| SubFileType | `254` | Descripteur de données du sous-fichier. |
| OsubfileType | `255` | [obsolète depuis TIFF rev. 5.0] Type de données dans le sous-fichier. |
| ImageWidth | `256` | Largeur de l'image en pixels. |
| ImageLength | `257` | Hauteur de l'image en pixels. |
| BitsPerSample | `258` | Bits par canal (échantillon). |
| Compression | `259` | Technique de compression des données. |
| Photometric | `262` | Interprétation photométrique. |
| Thresholding | `263` | [obsolète depuis TIFF rev. 5.0] Seuillage utilisé sur les données. |
| CellWidth | `264` | [obsolète depuis TIFF rev. 5.0] Largeur de la matrice de tramage. |
| CellLength | `265` | [obsolète depuis TIFF rev. 5.0] Hauteur de la matrice de tramage |
| FillOrder | `266` | Ordre des données dans un octet. |
| DocumentName | `269` | Nom du document qui contient l'image. |
| ImageDescription | `270` | Informations sur l'image. |
| Make | `271` | Nom du fabricant du scanner. |
| Model | `272` | Nom/numéro du modèle du scanner. |
| StripOffsets | `273` | Décalages vers les bandes de données. |
| Orientation | `274` | [obsoleted by TIFF rev. 5.0] Orientation de l'image. |
| SamplesPerPixel | `277` | Échantillons par pixel. |
| RowsPerStrip | `278` | Lignes par bande de données. |
| StripByteCounts | `279` | Décomptes d'octets pour les bandes. |
| MinSampleValue | `280` | [obsoleted by TIFF rev. 5.0] Valeur minimale d'échantillon. |
| MaxSampleValue | `281` | [obsoleted by TIFF rev. 5.0] Valeur maximale d'échantillon. |
| Xresolution | `282` | Pixels/résolution en x. |
| Yresolution | `283` | Pixels/résolution en y. |
| PlanarConfig | `284` | Organisation du stockage. |
| PageName | `285` | Nom de la page d'où provient l'image. |
| Xposition | `286` | Décalage X de la page de l'image à gauche. |
| Yposition | `287` | Décalage Y de la page de l'image à gauche. |
| FreeOffsets | `288` | [obsoleted by TIFF rev. 5.0] Décalage d'octet vers le bloc libre. |
| FreeByteCounts | `289` | [obsoleted by TIFF rev. 5.0] Tailles des blocs libres. |
| GrayResponseUnit | `290` | [obsoleted by TIFF rev. 6.0] Précision de la courbe en niveaux de gris. |
| GrayResponseCurve | `291` | [obsoleted by TIFF rev. 6.0] Courbe de réponse en niveaux de gris. |
| T4Options | `292` | Nom propre TIFF 6.0 alias pour GROUP3OPTIONS. Options pour le codage fax CCITT Group 3. 32 bits de drapeaux. |
| T6Options | `293` | Options pour le codage fax CCITT Group 4. 32 bits de drapeaux. Nom propre TIFF 6.0 alias pour GROUP4OPTIONS. |
| ResolutionUnit | `296` | Unités de résolutions. |
| PageNumber | `297` | Numéros de page du multi-page. |
| ColorResponseUnit | `300` | [obsoleted by TIFF rev. 6.0] Précision de la courbe de couleur. |
| TransferFunction | `301` | Informations de colorimétrie. |
| Software | `305` | Nom &amp; version. |
| DateTime | `306` | Date et heure de création. |
| Artist | `315` | Créateur de l'image. |
| HostComputer | `316` | Machine où créé. |
| Predictor | `317` | Schéma de prédiction avec LZW. |
| WhitePoint | `318` | Point blanc de l'image. |
| PrimaryChromaticities | `319` | Chromaticités primaires. |
| ColorMap | `320` | Carte RGB pour image pallette. |
| HalftoneHints | `321` | Informations de surbrillance + ombre. |
| TileWidth | `322` | Largeur de tuile en pixels. |
| TileLength | `323` | Hauteur de tuile en pixels. |
| TileOffsets | `324` | Décalages vers les tuiles de données. |
| TileByteCounts | `325` | Comptes d'octets pour les tuiles. |
| BadFaxLines | `326` | Lignes avec un nombre de pixels incorrect. |
| CleanFaxData | `327` | Informations de ligne régénérée. |
| ConsecutiveBadFaxLines | `328` | Maximum de lignes défectueuses consécutives. |
| SubIfd | `330` | Descripteurs de sous-image. |
| InkSet | `332` | Encres dans l'image séparée. |
| InkNames | `333` | Noms ASCII des encres. |
| NumberOfInks | `334` | Nombre d'encres. |
| DotRange | `336` | Codes de points à 0% et 100%. |
| TargetPrinter | `337` | Cible de séparation. |
| ExtraSamples | `338` | Informations sur les échantillons supplémentaires. |
| SampleFormat | `339` | Format d'échantillon de données. |
| SminSampleValue | `340` | Variable MinSampleValue. |
| SmaxSampleValue | `341` | Variable MaxSampleValue. |
| TransferRange | `342` | Variable TransferRange |
| ClipPath | `343` | ClipPath. Introduit après la révision 6.0 du TIFF par la technote 2 d'Adobe TIFF. |
| Xclippathunits | `344` | XClipPathUnits. Introduit après la révision 6.0 du TIFF par la technote 2 d'Adobe TIFF. |
| Yclippathunits | `345` | YClipPathUnits. Introduit après la révision 6.0 du TIFF par la technote 2 d'Adobe TIFF. |
| Indexed | `346` | Indexed. Introduit après la révision 6.0 du TIFF par la Technote 3 d'Adobe TIFF. |
| JpegTables | `347` | Flux de table JPEG. Introduit après la révision 6.0 du TIFF. |
| OpiProxy | `351` | OPI Proxy. Introduit après la révision 6.0 du TIFF par la technote d'Adobe TIFF. |
| JpegProc | `512` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Algorithme de traitement JPEG. |
| JpegInerchangeFormat | `513` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Pointeur vers le marqueur SOI. |
| JpegInterchangeFormatLength | `514` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Longueur du flux JFIF |
| JpegRestartInterval | `515` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Longueur de l'intervalle de redémarrage. |
| JpegLosslessPredictors | `517` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Prédicteur de traitement sans perte. |
| JpegPointTransform | `518` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Transformation de point sans perte. |
| JpegQTables | `519` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Décalages de la matrice Q. |
| JpegDCtables | `520` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Décalages de la table DCT. |
| JpegACtables | `521` | [obsolète selon la Technical Note #2 qui spécifie un schéma JPEG-in-TIFF révisé] Décalages des coefficients AC. |
| YcbcrCoefficients | `529` | Transformation RGB → YCbCr. |
| YcbcrSubSampling | `530` | Facteurs de sous-échantillonnage YCbCr. |
| YcbcrPositioning | `531` | Positionnement du sous-échantillonnage. |
| ReferenceBlackWhite | `532` | Informations de colorimétrie. |
| XmlPacket | `700` | Paquet XML. Introduit après la révision 6.0 du TIFF par la spécification Adobe XMP, janvier 2004. |
| OpiImageid | `32781` | OPI ImageID. Introduit après la révision 6.0 du TIFF par la technote d'Adobe TIFF. |
| Refpts | `32953` | Points de référence de l'image. Balise privée enregistrée auprès d'Island Graphics. |
| Copyright | `33432` | Chaîne de droits d'auteur. Cette balise est répertoriée dans le TIFF révision 6.0 avec une propriété inconnue. |
| PhotoshopResources | `34377` | Ressources d'image Photoshop. |
| IccProfile | `34675` | Le profil de périphérique ICC intégré |
| ExifIfdPointer | `34665` | Un pointeur vers l'IFD Exif. |
| XPTitle | `40091` | Informations sur l'image, utilisées par l'Explorateur Windows. Le XPTitle est ignoré par l'Explorateur Windows si la balise ImageDescription existe. |
| XPComment | `40092` | Commentaire sur l'image, utilisé par l'Explorateur Windows. |
| XPAuthor | `40093` | Auteur de l'image, utilisé par l'Explorateur Windows. Le XPAuthor est ignoré par l'Explorateur Windows si la balise Artist existe. |
| XPKeywords | `40094` | Mots-clés de l'image, utilisés par l'Explorateur Windows. |
| XPSubject | `40095` | Sujet de l'image, utilisé par l'Explorateur Windows. |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


