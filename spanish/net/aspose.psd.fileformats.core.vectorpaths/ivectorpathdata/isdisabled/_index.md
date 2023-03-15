---
title: IVectorPathData.IsDisabled
second_title: Referencia de API de Aspose.PSD para .NET
description: IVectorPathData propiedad. Obtiene o establece un valor que indica si esta instancia está deshabilitada.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/
---
## IVectorPathData.IsDisabled property

Obtiene o establece un valor que indica si esta instancia está deshabilitada.

```csharp
public bool IsDisabled { get; set; }
```

### El valor de la propiedad

`verdadero` si esta instancia está deshabilitada; de lo contrario,`FALSO` .

### Ejemplos

Este ejemplo demuestra la compatibilidad del recurso 'WorkingPathResource' en PsdImage.ImageResources para el correcto funcionamiento de la operación Recortar.

```csharp
[C#]

// Recorta la imagen y guarda.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Buscar el recurso WorkingPathResource.
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

// Carga la imagen guardada y verifica los cambios.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Buscar el recurso WorkingPathResource.
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
* espacio de nombres [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* asamblea [Aspose.PSD](../../../)


