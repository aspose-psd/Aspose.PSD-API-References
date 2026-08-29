---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdLoadOptions-egenskap. Hämtar eller anger om bilden ska sparas med den renderade bilden med eller utan en warp‑transformering."
type: docs
weight: 30
url: /sv/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Hämtar eller anger om man ska spara med den renderade bilden, med eller utan en warp‑transformering.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` rendera bilden med warp‑transformering `false`.

## Exempel

Följande kod demonstrerar rendering av Warp‑effekten.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### Se även

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


