---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "XmpBasicPackage eigenschap. Haalt het Object op of stelt het in met de opgegeven sleutel"
type: docs
weight: 20
url: /nl/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Haalt het Object op of stelt het in met de opgegeven sleutel.

```csharp
public override object this[string key] { get; set; }
```

| Parameter | Beschrijving |
| --- | --- |
| sleutel | De sleutel die de waarde identificeert. |

### Retourwaarde

Retourneert het Object met de opgegeven sleutel.

### Property Value

Het Object.

## Voorbeelden

De volgende code toont het gebruik van de UpdateMetadata-optie om de CreatorTool-waarde in xmp-gegevens bij te werken.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Als je wilt dat de creator-tool verandert, zorg er dan voor dat de eigenschap "UpdateMetadata" op true is ingesteld. Deze staat standaard op true.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Afbeelding opslaan.
    image.Save(path, psdOptions);

    // Controleren van de creator-tool in code.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Hier zal de bijgewerkte informatie over de creator‑tool staan.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Zie ook

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


