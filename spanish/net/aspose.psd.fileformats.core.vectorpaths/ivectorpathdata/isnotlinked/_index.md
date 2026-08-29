---
title: "IVectorPathData.IsNotLinked"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad IVectorPathData. Obtiene o establece un valor que indica si esta instancia no está vinculada"
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/
---
{{< psd/tize >}}
## IVectorPathData.IsNotLinked property

Obtiene o establece un valor que indica si esta instancia no está vinculada.

```csharp
public bool IsNotLinked { get; set; }
```

### Property Value

`true` si esta instancia no está vinculada; de lo contrario, `false`.

## Ejemplos

Este ejemplo demuestra el soporte del recurso 'WorkingPathResource' en PsdImage.ImageResources para el correcto funcionamiento de la operación de recorte.

```csharp
[C#]

// Recortar imagen y guardar.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Buscar recurso WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Recortar y guardar.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Cargar imagen guardada y verificar los cambios.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Buscar recurso WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### Ver también

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


