---
title: "IColorConverter"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le convertisseur de couleur."
type: docs
weight: 116
url: /fr/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

Le convertisseur de couleur.
## Méthodes

| Méthode | Description |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Convertit les données fournies au format de sortie. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Convertit les données fournies au format de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Le format source. |
| données | byte[] | Les données source. |
| décalage | int | Le décalage en octets où la copie des données doit commencer. |
| bitStart | int | Le début du bit. Notez que cette valeur n'est pas alignée sur un octet, il s'agit du bit réel où la copie doit commencer. |
| samplesCount | int | Le nombre d'échantillons. |
| linesCount | int | Le nombre de lignes. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Le format de destination. |
| outputData | byte[] | Les données de sortie. |
| outputOffset | int | Le décalage de sortie où la copie des données doit commencer. |

**Returns:**
int - Le nombre d'octets convertis.
