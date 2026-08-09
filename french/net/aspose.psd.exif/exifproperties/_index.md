---
title: "Énumération ExifProperties"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énumération Aspose.PSD.Exif.ExifProperties. Liste des balises Exif"
type: docs
weight: 1010
url: /fr/net/aspose.psd.exif/exifproperties/
---
{{< psd/tize >}}
## ExifProperties enumeration

Liste des balises Exif

```csharp
public enum ExifProperties : ushort
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| ImageWidth | `256` | Le nombre de colonnes des données d'image, égal au nombre de pixels par ligne. |
| ImageLength | `257` | Le nombre de lignes des données d'image. |
| BitsPerSample | `258` | Le nombre de bits par composant d'image. Dans cette norme chaque composant de l'image est de 8 bits, ainsi la valeur pour cette balise est 8. |
| Compression | `259` | Le schéma de compression utilisé pour les données d'image. Lorsqu'une image principale est compressée en JPEG, cette désignation n'est pas nécessaire et est omise. |
| PhotometricInterpretation | `262` | La composition des pixels. |
| ImageDescription | `270` | Une chaîne de caractères donnant le titre de l'image. Cela peut être un commentaire tel que "1988 company picnic" ou similaire. |
| Make | `271` | Le fabricant de l'équipement d'enregistrement. Il s'agit du fabricant du DSC, du scanner, du numériseur vidéo ou de tout autre équipement ayant généré l'image. Lorsque le champ est laissé vide, il est considéré comme inconnu. |
| Model | `272` | Le nom ou le numéro de modèle de l'équipement. Il s'agit du nom ou du numéro de modèle du DSC, du scanner, du numériseur vidéo ou de tout autre équipement ayant généré l'image. Lorsque le champ est laissé vide, il est considéré comme inconnu. |
| Orientation | `274` | L'orientation de l'image vue en termes de lignes et de colonnes. |
| SamplesPerPixel | `277` | Le nombre de composants par pixel. Comme cette norme s'applique aux images RGB et YCbCr, la valeur définie pour cette balise est 3. |
| XResolution | `282` | Le nombre de pixels par ResolutionUnit dans la direction ImageWidth. Lorsque la résolution de l'image est inconnue, 72 [dpi] est désigné. |
| YResolution | `283` | Le nombre de pixels par ResolutionUnit dans la direction ImageLength. La même valeur que XResolution est désignée. |
| PlanarConfiguration | `284` | Indique si les composants de pixels sont enregistrés dans un format chunky ou planar. Si ce champ n'existe pas, la valeur par défaut TIFF de 1 (chunky) est supposée. |
| ResolutionUnit | `296` | L'unité de mesure de XResolution et YResolution. La même unité est utilisée pour XResolution et YResolution. Si la résolution de l'image est inconnue, 2 (pouces) est désignée. |
| TransferFunction | `301` | Une fonction de transfert pour l'image, décrite sous forme tabulaire. Normalement cette balise n'est pas nécessaire, car l'espace couleur est spécifié dans la balise d'information d'espace couleur ColorSpace. |
| Software | `305` | Cette balise enregistre le nom et la version du logiciel ou du firmware de l'appareil photo ou du dispositif d'entrée d'image utilisé pour générer l'image. Le format détaillé n'est pas spécifié, mais il est recommandé de suivre l'exemple ci-dessous. Lorsque le champ est laissé vide, il est considéré comme inconnu. |
| DateTime | `306` | La date et l'heure de création de l'image. Dans la norme Exif, il s'agit de la date et l'heure de modification du fichier. |
| Artist | `315` | Cette balise enregistre le nom du propriétaire de l'appareil photo, du photographe ou du créateur de l'image. Le format détaillé n'est pas spécifié, mais il est recommandé d'écrire l'information comme dans l'exemple ci-dessous pour faciliter l'interopérabilité. Lorsque le champ est laissé vide, il est considéré comme inconnu. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| WhitePoint | `318` | La chromaticité du point blanc de l'image. Normalement cette balise n'est pas nécessaire, car l'espace couleur est spécifié dans la balise d'information d'espace couleur ColorSpace. |
| PrimaryChromaticities | `319` | La chromaticité des trois couleurs primaires de l'image. Normalement cette balise n'est pas nécessaire, car l'espace couleur est spécifié dans la balise d'information d'espace couleur ColorSpace. |
| YCbCrCoefficients | `529` | Les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr. |
| YCbCrSubSampling | `530` | Le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance. |
| YCbCrPositioning | `531` | Position des composants de chrominance par rapport au composant de luminance. Ce champ est désigné uniquement pour les données compressées en JPEG ou les données YCbCr non compressées. La valeur par défaut TIFF est 1 (centré) ; mais lorsque Y:Cb:Cr = 4:2:2, il est recommandé dans cette norme d'utiliser 2 (co‑situé) pour enregistrer les données, afin d'améliorer la qualité de l'image lorsqu'elle est affichée sur des systèmes TV. Lorsque ce champ n'existe pas, le lecteur doit supposer la valeur par défaut TIFF. Dans le cas Y:Cb:Cr = 4:2:0, la valeur par défaut TIFF (centré) est recommandée. Si le lecteur n'a pas la capacité de prendre en charge les deux types de YCbCrPositioning, il doit suivre la valeur par défaut TIFF quel que soit la valeur de ce champ. Il est préférable que les lecteurs \" soient capables de prendre en charge à la fois le positionnement centré et co‑situé. |
| ReferenceBlackWhite | `532` | La valeur du point noir de référence et la valeur du point blanc de référence. Aucun défaut n'est fourni dans TIFF, mais les valeurs ci‑dessous sont données comme défauts ici. L'espace colorimétrique est déclaré dans une balise d'information d'espace colorimétrique, la valeur par défaut étant celle qui donne les caractéristiques d'image optimales Interoperabilité dans ces conditions. |
| Copyright | `33432` | Informations sur le droit d'auteur. Dans cette norme, la balise est utilisée pour indiquer les droits d'auteur du photographe et de l'éditeur. Il s'agit de la mention de droit d'auteur de la personne ou de l'organisation revendiquant les droits sur l'image. La déclaration de droit d'auteur Interoperabilité, incluant la date et les droits, doit être écrite dans ce champ ; par exemple, "Copyright, John Smith, 19xx. Tous droits réservés.". Dans cette norme, le champ enregistre les droits d'auteur du photographe et de l'éditeur, chacun étant enregistré dans une partie séparée de la déclaration. Lorsqu'il existe une distinction claire entre les droits d'auteur du photographe et de l'éditeur, ils doivent être écrits dans l'ordre photographe suivi du droit d'auteur de l'éditeur, séparés par NULL (dans ce cas, comme la déclaration se termine également par un NULL, il y a deux codes NULL). Lorsque seul le droit d'auteur du photographe est fourni, il est terminé par un code NULL. Lorsque seul le droit d'auteur de l'éditeur est fourni, la partie du droit d'auteur du photographe consiste en un espace suivi d'un code NULL terminateur, puis le droit d'auteur de l'éditeur est donné. Lorsque le champ est laissé vide, il est considéré comme inconnu. |
| ExposureTime | `33434` | Temps d'exposition, donné en secondes. |
| FNumber | `33437` | Le nombre F. |
| ExposureProgram | `34850` | La classe du programme utilisé par l'appareil photo pour régler l'exposition lors de la prise de la photo. |
| SpectralSensitivity | `34852` | Indique la sensibilité spectrale de chaque canal de l'appareil photo utilisé. |
| PhotographicSensitivity | `34855` | Indique la vitesse ISO et la latitude ISO de l'appareil photo ou du dispositif d'entrée tel que spécifié dans la norme ISO 12232. |
| OECF | `34856` | Indique la fonction de conversion opto‑électrique (OECF) spécifiée dans la norme ISO 14524. |
| ExifVersion | `36864` | La version EXIF. |
| DateTimeOriginal | `36867` | La date et l'heure auxquelles les données d'image originales ont été générées. |
| DateTimeDigitized | `36868` | La date et l'heure de numérisation. |
| ComponentsConfiguration | `37121` | La configuration des composants. |
| CompressedBitsPerPixel | `37122` | Spécifique aux données compressées ; indique le nombre de bits compressés par pixel. |
| ShutterSpeedValue | `37377` | La valeur de la vitesse d'obturation. |
| ApertureValue | `37378` | La valeur de l'ouverture de l'objectif. |
| BrightnessValue | `37379` | La valeur de la luminosité. |
| ExposureBiasValue | `37380` | La valeur du biais d'exposition. |
| MaxApertureValue | `37381` | La valeur de l'ouverture maximale. |
| SubjectDistance | `37382` | La distance au sujet, donnée en mètres. |
| MeteringMode | `37383` | Le mode de mesure. |
| LightSource | `37384` | Le type de source lumineuse. |
| Flash | `37385` | Indique l'état du flash lors de la prise de la photo. |
| FocalLength | `37386` | La longueur focale réelle de l'objectif, en mm. |
| SubjectArea | `37396` | Cette balise indique l'emplacement et la zone du sujet principal dans la scène globale. |
| MakerNote | `37500` | Une balise pour les fabricants d'éditeurs Exif afin d'enregistrer toute information souhaitée. Le contenu dépend du fabricant, mais cette balise ne doit pas être utilisée à d'autres fins que son usage prévu. |
| UserComment | `37510` | Une balise pour les utilisateurs Exif afin d'écrire des mots‑clés ou des commentaires sur l'image en plus de ceux présents dans ImageDescription, et sans les limitations de code de caractères de la balise ImageDescription. |
| SubsecTime | `37520` | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTime. |
| SubsecTimeOriginal | `37521` | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeDigitized. |
| FlashpixVersion | `40960` | La version du format Flashpix prise en charge par un fichier FPXR. |
| ColorSpace | `40961` | La balise d'information d'espace couleur (ColorSpace) est toujours enregistrée comme le spécificateur d'espace couleur. |
| RelatedSoundFile | `40964` | Le fichier audio associé. |
| FlashEnergy | `41483` | Indique l'énergie du flash au moment de la capture de l'image, mesurée en Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Cette balise enregistre la table de fréquence spatiale de l'appareil photo ou du dispositif d'entrée ainsi que les valeurs SFR dans les directions de la largeur de l'image, de la hauteur de l'image et de la diagonale, comme spécifié dans la norme ISO 12233. |
| FocalPlaneXResolution | `41486` | Indique le nombre de pixels dans la direction de la largeur de l'image (X) par unité de résolution du plan focal (FocalPlaneResolutionUnit) sur le plan focal de l'appareil. |
| FocalPlaneYResolution | `41487` | Indique le nombre de pixels dans la direction de la hauteur de l'image (Y) par unité de résolution du plan focal (FocalPlaneResolutionUnit) sur le plan focal de l'appareil. |
| FocalPlaneResolutionUnit | `41488` | Indique l'unité de mesure de FocalPlaneXResolution et FocalPlaneYResolution. Cette valeur est identique à celle de ResolutionUnit. |
| SubjectLocation | `41492` | Indique l'emplacement du sujet principal dans la scène. La valeur de cette balise représente le pixel au centre du sujet principal par rapport au bord gauche, avant le traitement de rotation conformément à la balise Rotation. |
| ExposureIndex | `41493` | Indique l'indice d'exposition sélectionné sur l'appareil photo ou le dispositif d'entrée au moment de la capture de l'image. |
| SensingMethod | `41495` | Indique le type de capteur d'image de l'appareil photo ou du dispositif d'entrée. |
| FileSource | `41728` | La source du fichier. |
| SceneType | `41729` | Indique le type de scène. Si un DSC a enregistré l'image, la valeur de cette balise doit toujours être réglée à 1, indiquant que l'image a été photographiée directement. |
| CFAPattern | `41730` | Indique le motif géométrique du tableau de filtres couleur (CFA) du capteur d'image lorsqu'un capteur couleur à puce unique est utilisé. Cela ne s'applique pas à toutes les méthodes de détection. |
| CustomRendered | `41985` | Cette balise indique l'utilisation d'un traitement spécial sur les données d'image, tel qu'un rendu orienté vers la sortie. Lorsque ce traitement spécial est effectué, le lecteur doit désactiver ou minimiser tout traitement supplémentaire. |
| ExposureMode | `41986` | Cette balise indique le mode d'exposition réglé lors de la prise de vue. En mode de bracketing automatique, l'appareil photo prend une série de cadres de la même scène avec des réglages d'exposition différents. |
| WhiteBalance | `41987` | Cette balise indique le mode de balance des blancs réglé lors de la prise de vue. |
| DigitalZoomRatio | `41988` | Cette balise indique le rapport de zoom numérique lors de la prise de vue. Si le numérateur de la valeur enregistrée est 0, cela indique qu'aucun zoom numérique n'a été utilisé. |
| FocalLengthIn35MmFilm | `41989` | Cette balise indique la longueur focale équivalente en supposant un appareil photo à film de 35 mm, en mm. Une valeur de 0 signifie que la longueur focale est inconnue. Notez que cette balise diffère de la balise FocalLength. |
| SceneCaptureType | `41990` | Cette balise indique le type de scène qui a été photographié. Elle peut également être utilisée pour enregistrer le mode dans lequel l'image a été prise. |
| GainControl | `41991` | Cette balise indique le degré d'ajustement global du gain de l'image. |
| Contrast | `41992` | Cette balise indique la direction du traitement de contraste appliqué par l'appareil photo lors de la prise de vue. |
| Saturation | `41993` | Cette balise indique la direction du traitement de saturation appliqué par l'appareil photo lors de la prise de vue. |
| Sharpness | `41994` | Cette balise indique la direction du traitement de netteté appliqué par l'appareil photo lors de la prise de vue |
| DeviceSettingDescription | `41995` | Cette balise indique les informations sur les conditions de prise de vue d'un modèle d'appareil photo particulier. La balise est utilisée uniquement pour indiquer les conditions de prise de vue dans le lecteur. |
| SubjectDistanceRange | `41996` | Cette balise indique la distance au sujet. |
| ImageUniqueID | `42016` | L'identifiant unique de l'image. |
| GPSVersionID | `0` | Indique la version de GPSInfoIFD. |
| GPSLatitudeRef | `1` | Indique si la latitude est nord ou sud. |
| GPSLatitude | `2` | Indique la latitude. La latitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, des fractions de minutes sont données jusqu'à deux décimales, le format serait dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Indique si la longitude est orientée à l'est ou à l'ouest. |
| GPSLongitude | `4` | Indique la longitude. La longitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, des fractions de minutes sont données jusqu'à deux décimales, le format serait ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Indique l'altitude utilisée comme altitude de référence. Si la référence est le niveau de la mer et que l'altitude est au-dessus du niveau de la mer, la valeur 0 est donnée. Si l'altitude est en dessous du niveau de la mer, la valeur 1 est donnée et l'altitude est indiquée comme une valeur absolue dans la balise GPSAltitude. |
| GPSAltitude | `6` | Indique l'altitude basée sur la référence dans GPSAltitudeRef. L'altitude est exprimée sous forme d'une valeur RATIONAL. L'unité de référence est le mètre. |
| GPSTimestamp | `7` | Indique l'heure en UTC (Temps Universel Coordonné). Le TimeStamp est exprimé sous forme de trois valeurs RATIONAL donnant l'heure, la minute et la seconde. |
| GPSSatellites | `8` | Indique les satellites GPS utilisés pour les mesures. Cette balise peut être utilisée pour décrire le nombre de satellites, leur numéro d'ID, l'angle d'élévation, l'azimut, le SNR et d'autres informations en notation ASCII. Le format n'est pas spécifié. Si le récepteur GPS est incapable de prendre des mesures, la valeur de la balise doit être définie sur NULL. |
| GPSStatus | `9` | Indique l'état du récepteur GPS lorsque l'image est enregistrée. |
| GPSMeasureMode | `10` | Indique le mode de mesure GPS. - 2 ou 3 dimensions. |
| GPSDOP | `11` | Indique le DOP GPS (degré de précision des données). Une valeur HDOP est écrite lors d'une mesure bidimensionnelle, et PDOP lors d'une mesure tridimensionnelle. |
| GPSSpeedRef | `12` | Indique l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. 'K', 'M' et 'N' représentent respectivement les kilomètres par heure, les miles par heure et les nœuds. |
| GPSSpeed | `13` | Indique la vitesse du déplacement du récepteur GPS. |
| GPSTrackRef | `14` | Indique la référence pour donner la direction du déplacement du récepteur GPS. 'T' désigne la direction vraie et 'M' la direction magnétique. |
| GPSTrack | `15` | Indique la direction du déplacement du récepteur GPS. L'intervalle des valeurs va de 0,00 à 359,99. |
| GPSImgDirectionRef | `16` | Indique la référence pour donner la direction de l'image lorsqu'elle est capturée. 'T' désigne la direction vraie et 'M' la direction magnétique. |
| GPSImgDirection | `17` | Indique la direction de l'image lorsqu'elle a été capturée. L'intervalle des valeurs va de 0,00 à 359,99. |
| GPSMapDatum | `18` | Indique les données d'arpentage géodésique utilisées par le récepteur GPS. |
| GPSDestLatitudeRef | `19` | Indique si la latitude du point de destination est une latitude nord ou sud. La valeur ASCII 'N' indique la latitude nord, et 'S' indique la latitude sud. |
| GPSDestLatitude | `20` | Indique la latitude du point de destination. La latitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Indique si la longitude du point de destination est orientée à l'est ou à l'ouest. Le caractère ASCII 'E' indique l'est, et 'W' indique l'ouest. |
| GPSDestLongitude | `22` | Indique la longitude du point de destination. La longitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Indique la référence utilisée pour donner le relèvement vers le point de destination. 'T' désigne la direction vraie et 'M' la direction magnétique. |
| GPSDestBearing | `24` | Indique le relèvement vers le point de destination. L'intervalle des valeurs va de 0.00 à 359.99. |
| GPSDestDistanceRef | `25` | Indique l'unité utilisée pour exprimer la distance au point de destination. 'K', 'M' et 'N' représentent respectivement les kilomètres, les miles et les nœuds. |
| GPSDestDistance | `26` | Indique la distance au point de destination. |
| GPSProcessingMethod | `27` | Une chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation. Le premier octet indique le code de caractères utilisé, suivi du nom de la méthode. |
| GPSAreaInformation | `28` | Une chaîne de caractères enregistrant le nom de la zone GPS. Le premier octet indique le code de caractères utilisé, suivi du nom de la zone GPS. |
| GPSDateStamp | `29` | Une chaîne de caractères enregistrant les informations de date et d'heure relatives à l'UTC (Temps Universel Coordonné). Le format est AAAA:MM:JJ. |
| GPSDifferential | `30` | Indique si une correction différentielle est appliquée au récepteur GPS. |
| StripOffsets | `273` | Pour chaque bande, le décalage en octets de cette bande. Il est recommandé de choisir cela de façon que le nombre d'octets par bande ne dépasse pas 64 Koctets. Balise auxiliaire. |
| JPEGInterchangeFormat | `513` | Le décalage vers l'octet de démarrage (SOI) des données de vignette JPEG compressées. Ceci n'est pas utilisé pour les données JPEG de l'image principale. |
| JPEGInterchangeFormatLength | `514` | Le nombre d'octets des données de vignette JPEG compressées. Ceci n'est pas utilisé pour les données JPEG de l'image principale. Les vignettes JPEG ne sont pas divisées mais sont enregistrées comme un flux JPEG continu du SOI à l'EOI. Les marqueurs Appn et COM ne doivent pas être enregistrés. Les vignettes compressées doivent être enregistrées dans un maximum de 64 Koctets, y compris toutes les autres données à enregistrer dans APP1. |
| ExifIfdPointer | `34665` | Un pointeur vers l'IFD Exif. Interopérabilité, l'IFD Exif a la même structure que celle de l'IFD spécifié dans le TIFF. Ordinairement, cependant, il ne contient pas de données d'image comme dans le cas du TIFF. |
| GPSIfdPointer | `34853` | Le pointeur IFD GPS. |
| RowsPerStrip | `278` | Le nombre de lignes par bande. Il s'agit du nombre de lignes dans l'image d'une bande lorsqu'une image est divisée en bandes. |
| StripByteCounts | `279` | Le nombre total d'octets dans chaque bande. |
| PixelXDimension | `40962` | Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la largeur valide de l'image significative doit être enregistrée dans cette balise, qu'il y ait ou non des données de remplissage ou un marqueur de redémarrage. |
| PixelYDimension | `40963` | Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la hauteur valide de l'image significative doit être enregistrée dans cette balise. |
| Gamma | `42240` | Valeur gamma |
| SensitivityType | `34864` | Type de sensibilité photographique |
| StandardOutputSensitivity | `34865` | Indique la sensibilité de sortie standard de l'appareil photo |
| RecommendedExposureIndex | `34866` | Indique l'indice d'exposition recommandé |
| ISOSpeed | `34867` | Informations sur la valeur de vitesse ISO telle que définie dans la norme ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Cette balise indique la valeur de latitude yyy de la vitesse ISO telle que définie dans la norme ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Cette balise indique la valeur de latitude zzz de la vitesse ISO telle que définie dans la norme ISO 12232 |
| CameraOwnerName | `42032` | Contient le nom du propriétaire de l'appareil photo |
| BodySerialNumber | `42033` | Contient le numéro de série du boîtier de l'appareil photo |
| LensMake | `42035` | Cette balise enregistre le fabricant de l'objectif |
| LensModel | `42036` | Cette balise enregistre le nom du modèle et le numéro du modèle de l'objectif |
| LensSerialNumber | `42037` | Cette balise enregistre le numéro de série de l'objectif interchangeable |
| LensSpecification | `42034` | Cette balise indique la distance focale minimale, la distance focale maximale, le nombre F minimal à la distance focale minimale et le nombre F minimal à la distance focale maximale |

### Voir aussi

* namespace [Aspose.PSD.Exif](../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../)


