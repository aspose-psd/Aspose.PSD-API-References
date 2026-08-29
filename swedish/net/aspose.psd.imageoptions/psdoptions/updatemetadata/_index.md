---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdOptions egenskap. Hämtar eller anger ett värde som indikerar om metadata ska uppdateras. Om värdet är true kommer metadata att uppdateras vid sparande av en bild"
type: docs
weight: 110
url: /sv/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Hämtar eller anger ett värde som indikerar om [update metadata]. Om värdet är true uppdateras metadata vid sparande av en bild.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` om [uppdatera metadata]; annars, `false`.

## Exempel

Följande kod demonstrerar användning av UpdateMetadata-alternativet för att uppdatera CreatorTool-värdet i xmp-data.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Om du vill att creator-verktyget ska ändras, se till att egenskapen \"UpdateMetadata\" är satt till true. Den är satt till true som standard.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Sparar bilden.
    image.Save(path, psdOptions);

    // Kontrollerar creator-verktyg i kod.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Här kommer den uppdaterade creator-verktygsinformationen.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Se även

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


