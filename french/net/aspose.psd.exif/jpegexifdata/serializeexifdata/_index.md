---
title: "JpegExifData.SerializeExifData"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode JpegExifData. Sérialise les données EXIF. Écrit les valeurs et le contenu des balises. La balise de taille la plus influente est le contenu de la balise Thumbnail."
type: docs
weight: 270
url: /fr/net/aspose.psd.exif/jpegexifdata/serializeexifdata/
---
{{< psd/tize >}}
## JpegExifData.SerializeExifData method

Sérialise les données EXIF. Écrit les valeurs et le contenu des balises. La balise de taille la plus influente est le contenu de la balise Miniature.

```csharp
public byte[] SerializeExifData()
```

### Valeur de retour

Les données EXIF sérialisées.

## Remarques

La taille totale du segment doit être inférieure ou égale à MaxExifSegmentSize octets afin de produire une image jpeg correcte. Astuce : essayez de réduire la taille de la miniature ou de modifier sa compression si vous avez une section EXIF trop grande.

### Voir aussi

* class [JpegExifData](../)
* namespace [Aspose.PSD.Exif](../../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../../)


