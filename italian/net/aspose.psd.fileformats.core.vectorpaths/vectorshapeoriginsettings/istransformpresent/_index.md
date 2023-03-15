---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: Aspose.PSD per riferimento API .NET
description: VectorShapeOriginSettings proprietà. Ottiene un valore che indica se questa istanza ha la proprietà transform.
type: docs
weight: 100
url: /it/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
## VectorShapeOriginSettings.IsTransformPresent property

Ottiene un valore che indica se questa istanza ha la proprietà transform.

```csharp
public bool IsTransformPresent { get; }
```

### Valore della proprietà

`VERO` se questa istanza ha la proprietà transform; Altrimenti,`falso` .

### Esempi

Il codice seguente dimostra la possibilità di ridimensionare un livello di forma che contiene percorsi vettoriali.

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

### Guarda anche

* class [VectorShapeOriginSettings](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* assemblea [Aspose.PSD](../../../)


