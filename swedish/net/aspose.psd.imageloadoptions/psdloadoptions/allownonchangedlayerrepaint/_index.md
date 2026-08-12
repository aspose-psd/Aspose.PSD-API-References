---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdLoadOptions-egenskap. Hämtar eller anger om originala lagerpixlar ska bevaras under rendering om lagret inte har modifierats."
type: docs
weight: 20
url: /sv/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Hämtar eller anger om ursprungliga lagerpixlar ska bevaras under rendering om lagret inte har ändrats.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` för att behålla de ursprungliga pixlarna i oförändrade lager; annars, `false`.

## Exempel

Följande kod demonstrerar det nya beteendet som förhindrar automatisk ommålning av lager innan ändringar.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### Se även

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


