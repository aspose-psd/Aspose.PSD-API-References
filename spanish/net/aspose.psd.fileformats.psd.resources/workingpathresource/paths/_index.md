---
title: "WorkingPathResource.Paths"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad WorkingPathResource. Obtiene o establece los registros de ruta"
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.resources/workingpathresource/paths/
---
{{< psd/tize >}}
## WorkingPathResource.Paths property

Obtiene o establece los registros de ruta.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Property Value

Las rutas.

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

* class [VectorPathRecord](../../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/)
* class [WorkingPathResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


