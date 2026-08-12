---
title: "VectorShapeOriginSettings.IsTransformPresent"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad VectorShapeOriginSettings. Obtiene un valor que indica si esta instancia tiene la propiedad de transformación"
type: docs
weight: 100
url: /es/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsTransformPresent property

Obtiene un valor que indica si esta instancia tiene la propiedad transform.

```csharp
public bool IsTransformPresent { get; }
```

### Property Value

`true` si esta instancia tiene la propiedad de transformación; de lo contrario, `false`.

## Ejemplos

El siguiente código demuestra la capacidad de redimensionar capas de forma que contienen rutas vectoriales.

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ver también

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


