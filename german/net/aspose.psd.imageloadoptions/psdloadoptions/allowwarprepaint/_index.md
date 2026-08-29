---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdLoadOptions‑Eigenschaft. Gibt an bzw. legt fest, ob das gerenderte Bild mit oder ohne Warp‑Transformation gespeichert wird"
type: docs
weight: 30
url: /de/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Liest oder setzt, ob mit dem gerenderten Bild gespeichert werden soll, mit oder ohne Verzerrungs-Transformation.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` Bild mit Warp‑Transformation rendern `false`.

## Beispiele

Der folgende Code demonstriert die Warp‑Effekt‑Renderung.

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

### Siehe auch

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


