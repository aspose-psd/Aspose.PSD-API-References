---
title: "IVectorPathData.Version"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad IVectorPathData. Obtiene o establece la versión"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/
---
{{< psd/tize >}}
## IVectorPathData.Version property

Obtiene o establece la versión.

```csharp
public int Version { get; set; }
```

### Property Value

La versión.

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


