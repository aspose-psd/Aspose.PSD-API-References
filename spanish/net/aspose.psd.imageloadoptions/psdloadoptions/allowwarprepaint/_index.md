---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PsdLoadOptions. Obtiene o establece si se guarda la imagen renderizada con o sin una transformación de deformación"
type: docs
weight: 30
url: /es/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Obtiene o establece si se debe guardar con la imagen renderizada, con o sin una transformación de deformación.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` renderiza la imagen con transformación de deformación `false`.

## Ejemplos

El siguiente código demuestra la renderización del efecto Warp.

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

### Ver también

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


