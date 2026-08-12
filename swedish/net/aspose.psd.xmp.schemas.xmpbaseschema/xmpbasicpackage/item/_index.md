---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD för .NET API‑referens"
description: "XmpBasicPackage egenskap. Hämtar eller sätter Object med den angivna nyckeln"
type: docs
weight: 20
url: /sv/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Hämtar eller anger objektet med den angivna nyckeln.

```csharp
public override object this[string key] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| nyckel | Nyckeln som identifierar värdet. |

### Returvärde

Returnerar Object med den angivna nyckeln.

### Property Value

Objectet.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


