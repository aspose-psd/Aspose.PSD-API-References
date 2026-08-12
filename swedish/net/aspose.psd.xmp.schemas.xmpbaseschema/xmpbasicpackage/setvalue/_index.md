---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD för .NET API‑referens"
description: "XmpBasicPackage method. Sätter värdet"
type: docs
weight: 120
url: /sv/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Ställer in värdet.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | String | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| värde | IXmlValue | Värdet att lägga till. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


