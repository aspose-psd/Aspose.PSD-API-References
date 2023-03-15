---
title: WorkingPathResource.WorkingPathResource
second_title: Referencia de API de Aspose.PSD para .NET
description: WorkingPathResource constructor. Inicializa una nueva instancia delWorkingPathResource clase.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

Inicializa una nueva instancia del[`WorkingPathResource`](../) clase.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| dataBytes | Byte[] | Los datos de la ruta del vector. |

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

* class [WorkingPathResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* asamblea [Aspose.PSD](../../../)


