---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "XmpBasicPackage methode. Stelt de waarde in"
type: docs
weight: 120
url: /nl/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Stelt de waarde in.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | String | De tekenreeksrepresentatie van de sleutel die wordt geïdentificeerd met de toegevoegde waarde. |
| waarde | IXmlValue | De waarde om aan toe te voegen. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


