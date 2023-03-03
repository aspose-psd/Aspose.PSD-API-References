---
title: JpegExifData.SerializeExifData
second_title: Référence de l'API Aspose.PSD pour .NET
description: JpegExifData méthode. Sérialise les données EXIF. Écrit les valeurs et le contenu des balises. La balise de taille la plus influente est le contenu de la balise Thumbnail.
type: docs
weight: 270
url: /fr/net/aspose.psd.exif/jpegexifdata/serializeexifdata/
---
## JpegExifData.SerializeExifData method

Sérialise les données EXIF. Écrit les valeurs et le contenu des balises. La balise de taille la plus influente est le contenu de la balise Thumbnail.

```csharp
public byte[] SerializeExifData()
```

### Return_Value

Les données EXIF sérialisées.

### Remarques

La taille globale du segment doit être inférieure ou égale à MaxExifSegmentSize octets afin de produire une image jpeg correcte. Astuce : essayez de réduire la taille de la vignette ou de modifier sa compression au cas où vous auriez une trop grande taille de section EXIF.

### Voir également

* class [JpegExifData](../)
* espace de noms [Aspose.PSD.Exif](../../jpegexifdata/)
* Assemblée [Aspose.PSD](../../../)


