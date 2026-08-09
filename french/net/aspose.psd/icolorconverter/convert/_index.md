---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode IColorConverter. Convertit les données fournies au format de sortie"
type: docs
weight: 10
url: /fr/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

Convertit les données fournies au format de sortie.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Le format source. |
| données | Byte[] | Les données source. |
| offset | Int32 | Le décalage en octets où la copie des données doit commencer. |
| bitStart | Int32 | Le début du bit. Notez que cette valeur n'est pas alignée sur un octet, mais correspond au bit réel où la copie doit commencer. |
| samplesCount | Int32 | Le nombre d'échantillons. |
| linesCount | Int32 | Le nombre de lignes. |
| destFormat | PixelDataFormat | Le format de destination. |
| outputData | Byte[] | Les données de sortie. |
| outputOffset | Int32 | Le décalage de sortie où la copie des données doit commencer. |

### Valeur de retour

Le nombre d'octets convertis.

### Voir aussi

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


