---
title: "JpegExifData.SerializeExifData"
second_title: "Aspose.PSD för .NET API‑referens"
description: "JpegExifData metod. Serialiserar EXIF-data. Skriver taggarnas värden och innehåll. Den mest påverkande storlekstaggen är innehållet i Thumbnail-taggen"
type: docs
weight: 270
url: /sv/net/aspose.psd.exif/jpegexifdata/serializeexifdata/
---
{{< psd/tize >}}
## JpegExifData.SerializeExifData method

Serialiserar EXIF-data. Skriver taggvärdena och innehållet. Den mest påverkande storlekstaggen är innehållet i miniatyrtaggen.

```csharp
public byte[] SerializeExifData()
```

### Returvärde

Den serialiserade EXIF-datan.

## Anmärkningar

Den totala segmentstorleken måste vara mindre än eller lika med MaxExifSegmentSize byte för att producera en korrekt jpeg-bild. Tips: försök minska miniatyrbildens storlek eller ändra dess komprimering om du har för stor EXIF-sektionsstorlek.

### Se även

* class [JpegExifData](../)
* namespace [Aspose.PSD.Exif](../../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../../)


