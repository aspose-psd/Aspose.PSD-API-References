---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "PsdOptions eigenschap. Haalt op of stelt een waarde in die aangeeft of metadata moet worden bijgewerkt. Als de waarde true is, wordt de metadata bijgewerkt tijdens het opslaan van een afbeelding"
type: docs
weight: 110
url: /nl/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Haalt op of stelt een waarde in die aangeeft of [update metadata]. Als de waarde true is, wordt de metadata bijgewerkt tijdens het opslaan van een afbeelding.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` als [update metadata]; anders `false`.

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

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


